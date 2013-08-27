.. Wise Board by Silica Architech  documentation master file, created by
   sphinx-quickstart on Thu Jul 25 11:13:41 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Wise Board by Silica Architech's documentation!
===============================================================

:Version: 1.0.0
:Copyright: (C)2013 Silica an Avnet company
:Date: 30 july 2013

.. image:: _jn_images/silica.png
.. image:: _jn_images/nxplogo.gif
.. image:: _jn_images/jennic.gif

.. index:: index

**INTRODUCTION**
****************

| Silica Wise Board is useful system to evaluate a basic IEE802.15.4 network using JN5168 wireless module. 
| Wise board has a single built-in USB dongle. Simply switching serial channel from terminal application to programming software, you can perform two alternate functions:
| a - Evaluate network with simple serial monitor (using a PC terminal such as HyperTerminal)
| b - Program Firmware into JN5168 module (using JN-SW-4007-Flash-Programmer v1.8.9)

*If you want, you can use separate USB-TTL adapter connected with 6 pin strip on RSR933 board. In this case, you can have two separate serial channel, first (USBdongle) for programming and second (6 pin strip) for Serial Monitor. See* :ref:`serial`

Wise board is also designed as a plugin for SerizII board. **Wise "ready to run" kit** is specially designed for quick use and fast evaluate  network functionallity. All you have to do is plug End-Node on SerizII board, plug Coordinator on PC USB port, start HyperTerminal and enjoy!!

| Firmware application was developed with JN-SW-4041-SDK-Toolchain-v.1.1 (Eclipse based). 
| You must also install JN-SW-4065-JN516x-JenNet-IP-SDK-v857 software library. 
| Firmware project is included in Wise_Jennic.zip file.
| Reference guide are included into Install.zip and are:
|   1) JN-UG-3064 - Software Developer’s Kit Installation and User Guide
|   2) JN-UG-3007 - JN51xx Flash Programmer User Guide

Install.zip also include JN-SW-4041-SDK-Toolchain-v.1.1.exe and JN-SW-4065-JN516x-JenNet-IP-SDK-v857.exe to install developement suite.

| For JN5168 modules programming, you must install FlashGUI programmer from JN-SW-4007 (included in Install.zip). Please, note that JN-UG-3007 refers to Flash GUI programmer version 1.8.4, and JN-SW-4047 contains new release 1.8.9 of Flash GUI programmer. See release note document included in JN-SW-4047 package. The release 1.8.9 must be installed for JN516x modules programming.
| Install.zip and Wise_Jennic.zip files can be downloaded from Wise section of Silica ArchiTech web page (registration needed)
| **Installing Jennic Developement Suite** chapter will guide you through the basic steps of the installation procedure of Jennic Developement Suite

We suggest you to read first the Quick Start Guide to perform a correct Firmware setup. 

:ref:`quick`

This guide explains how to use this application and provides an overview of on the structure of the project firmware

.. toctree::
 :maxdepth: 3
   
 JenInst
 quick
 ready
 PrjFiles
 Monitor
 tip

 
 

 
 
We also suggest you to see documentation `JN516x Wireless Microcontrollers <http://www.nxp.com/techzones/wireless-connectivity/jn51xx/jn516x.html>`_ for any specific further detail.

* :ref:`search`

