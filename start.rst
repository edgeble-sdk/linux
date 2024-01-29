===============
Getting Started
===============

OpenAIA
======

.. image:: /images/openaia-v1.png

- *Neural Compute Modules:* NCM's are Compute or System On Modules (COM/SOM) built on top of High Performace, Ultra Vision AI Accelerators with on-module WiFi and Camera accessing for Edge AI-enabled solutions. See :ref:`link_ncm`

- *Open Source BSP:* Board Supported Packages delivers Boot firmware and Linux Kernel in the form Debian distribution via Debos and Embedded Rootfilesystems via Yocto/OE layers. See :ref:`link_bsp`.

- *GPU/VPU:* Set of Open Source and closed acceleration tools for accessing Video, Graphics to the user-space.

- *Pre-trained Model:* State-of-the-art pre-trained model management tools that delivers single API to access user-defined models. uTrain has a built-in model conversion (NPU-based models to user-defined models) and optimization algorithms. See :ref:`link_utrain`.

- *Update/Fleet:* Robust, Fast, Fail-safe secure deployment tools that are used to deliver Continous Intigration and Delivery (CI/CD) to the NCM's via DevOps loop for pre-trained and re-trained models from uTrain. See :ref:`link_update`.

Development
==========

Stack
-----

.. image:: /images/project-v1.png


Process
-------

Milestones
----------

.. image:: /images/milestone-v1.png

Status
------


Rules
-----

- Rule 1: Repo must clone with ssh not https
- Rule 2: Upload your ssh public key in your github settings
- Rule 3: Send only Github PR for review, inter-course repo sharing won't accept.
- Rule 4: Default edgeble dockers are private so access them via token. See :ref:`link_token`
