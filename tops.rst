.. _link_ncm:

=====================
Neural Compute Module
=====================

NPU
===

In short, Neural Processing Unit (NPU) is a computing technology that runs Artificial Intelligence and Machine learning algorithms locally on the the hardware or silicon.

.. image:: /images/ai-hard1.png

.. image:: /images/ai-hard2.png

Edgeble NCM
===========

Edgeble NCM, Neural Compute Modules (NCM) are hardware AI compute module accelerators designed to compute deep learning inferences at the edge device by reducing the latency and increasing the responsiveness. These NCM's is built on top of high-performance NPUs with a holistic computing system that has the capability to process high-rate video and graphics by operating -40°C to +85°C temperatures with 2TOPS, and 6TOPS speeds.

+-------+----------+---------+------------+--------------------+-------------------+
|  TOPS | Partcode |   SoC   |    Grade   |      Hardware      |     Software      |
+-------+----------+---------+------------+--------------------+-------------------+
|       |   NCM6A  |  RK3588 |   Consumer |                    |                   |
|       +----------+---------+------------+                    | :ref:`link_6tops` |
| 6TOPS |   NCM6A  | RK3588J | Industrial |   :ref:`link_ncm6` |                   |
|       +----------+---------+------------+                    | :ref:`link_6tops` |
|       |   NCM6A  | RK3588M | Automotive |                    |                   |
+-------+----------+---------+------------+--------------------+-------------------+
|       |   NCM1A  | RK3568  |  Consumer  |                    |                   |
| 1TOPS +----------+---------+------------+   :ref:`link_ncm1` | :ref:`link_1tops` |
|       |   NCM1A  | RK3568J | Industrial |                    | :ref:`link_1tops` |
+-------+----------+---------+------------+--------------------+-------------------+
|       |   NCM2A  | RV1126  |  Consumer  |                    |                   |
| 2TOPS +----------+---------+------------+   :ref:`link_ncm1` | :ref:`link_1tops` |
|       |   NCM2A  | RV1126K | Industrial |                    | :ref:`link_1tops` |
+-------+----------+---------+------------+--------------------+-------------------+
