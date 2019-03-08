.. -*- coding: utf-8 -*-

...  Copyright 2019 Six Feet Up, Inc.

     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.

:title: Intro to AWS Greengrass
:event: Indy IoT
:author: Calvin Hendryx-Parker
:pygments: tango
:css: custom.css

.. |space| unicode:: 0xA0 .. non-breaking space
.. |br| raw:: html

    <br />

----

Intro to AWS Greengrass
=======================

Calvin Hendryx-Parker, CTO
++++++++++++++++++++++++++

Six Feet Up, Inc.
-----------------

----

Fully Managed Edge Services
===========================

* Secure Communications
* Group Management of Cores
* OTA Provisioning and Updates

----

Lambda at Your Edge
===================

.. note::

    You install the core on your devices

    You run AWS Lambdas on your devices

----

Offline Operation
=================

* AWS IoT Device Shadows

----

Local Messaging
===============

.. note::

    Local only messaging even with no connection to AWS

    Utilizes the greengrass SDK on the local devices

    Processes rules and deliver messages to other devices or the cloud

----

Local Reource Access
====================

* Serial Ports
* GPIO
* Bluetooth

----

Greengrass Connectors
=====================

Access to third-party APIs
++++++++++++++++++++++++++

On-premises Software
++++++++++++++++++++

----

Run ML Models
=============

* Local Inference

.. note::

     Reduce costs on transfer to the cloud

----

Hardware Support
================

* Raspberry Pi
* Intel Atom
* Nvidia Jetson NX
* ARM v7 and v8
* Intel amd64
* Existing IoT Hardware

.. note::

    Supports many Gateways and exisiting edge devices

----

Greengrass Secrets Manager
==========================

Works with Greengrass Connectors
++++++++++++++++++++++++++++++++

.. note::

    Rotate keys and distribute access to other edge resources

----

Greengrass Pricing
==================

* Free tier for 3 devices for the first year
* Up to 10k devices -- $0.16/month/device

.. note::

     prices for of US East 1 and US West 1
     billed only in whole months
     They get you on everything else

     * transfer
     * storage

----

Resources
=========

* `Getting Started Guide`_
* `FAQs`_


.. _Getting Started Guide: http://docs.aws.amazon.com/greengrass/latest/developerguide/gg-gs.html
.. _FAQs: https://aws.amazon.com/greengrass/faqs/


----

Thanks!
=======

calvin@sixfeetup.com

`@calvinhp`_

.. _@calvinhp: https://twitter.com/calvinhp
