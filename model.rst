.. _link_utrain:

==================
Pre-trained Models
==================

uTrain
======

.. image:: /images/model/utrain-v1.png

- Model builder: Build the model, unless if the specific use-case does not have a default models. 
- Model Conversion: Convert the trained model into an RKNN format model.
- Model Optimisation: Optimized way of RKNN trained model.

Note: RKNN format model is what RKNPU understandable model format.

Conversion
==========

Deployment
----------

Status
------

+-------------------+-----------+-------+---------+
|      Function     |   Model   | Image |  Stream |
+-------------------+-----------+-------+---------+
| Object Detection  |   Yolov5  |  OK   |   WIP   |
+-------------------+-----------+-------+---------+
| Weld Character    |  3rdparty |  WIP  |         |
+-------------------+-----------+-------+---------+
| Plant Character   |  3rdparty |  WIP  |         |
+-------------------+-----------+-------+---------+

Reference
---------

- `rknpu2 <https://github.com/rockchip-linux/rknpu2>`_
- `rknn-toolkit2 <https://github.com/rockchip-linux/rknn-toolkit2>`_
