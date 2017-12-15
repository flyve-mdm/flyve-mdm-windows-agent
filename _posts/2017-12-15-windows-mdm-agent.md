---
layout: post
category: blog
published: false
title: Windows MDM Agent
---
Welcome to the release of Flyve MDM Windows MDM Agent!

We are glad and very proud to present you this brand new application that allows you to manage your Windows device.

This app allows you to implement the following features in the devices of your fleet:

* [Configure and deploy your fleet](#myf)
* [Connectivity Access](#cca)
* [Security Features](#sf)
* [Mobile Fleet Inventory](#mfi)
* [Applications management](#am)

Flyve MDM is a Mobile Device Management software that enables you to secure and manage all the mobile devices of your business or family via a dashboard.

You can join the community in GitHub and participate to contribute, test and correct bugs: [Flyve MDM on GitHub](https://github.com/flyve-mdm)!

The Windows Agent is under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.html).

## Outstanding features

### <a name="myf"></a>Manage your fleet

* Send files

The Agent will receive the files you sent in the Dashboard, helping you to keep your fleet with the required information.

* Locate your devices

You will be able to activate real-time geolocation of the device

* Enable/disable the use of the camera

The Agent can set if the cameras of the devices will be operatives

### <a name="cca"></a>Configure the Connectivity Access

Control the connectivity of the device by enabling or disabling:

* Bluetooth
* Wi-Fi
* USB transfer
* NFC
* Mobile Line
* Hotspot

### <a name="sf"></a>Security Features

Includes a range of powerful features to protect sensitive company data stored on mobile devices, allowing you to manage your mobile fleet security policy with precision.

#### Delete your data in case of loss or theft

The Agent will be able to erase the information of the device, partially or totally

#### Activate mobile device encryption

This allows you to encrypt the information storaged in the device

#### Lock the mobile device

Lock the device so unauthorised individuals can't have access to the business information, also it can control actions to follow when the number of wrong passwords are introduced.

#### Level of complexity of your passwords

Set the complexity of the password according the maximun number of characters, numbers or letters only, as seen fit.

### <a name="mfi"></a>Mobile Fleet Inventory

Gather the most important information of the device, such as battery status, memory, etc.

### <a name="am"></a>Applications Management

This allows you to save time when you require to install or uninstall applications in your Android device, since the Agent will do it automatically according to the instructions given by the dashboard.

## MQ Telemetry Transport

We implemented the MQTT protocol, which is useful for connections with remote locations since it was designed as an extremely lightweight message transport. It is also ideal for mobile applications because of its small size, low power usage, minimised data packets, and efficient distribution of information to one or many receivers. Thanks to it, the Agent is capable of maintaining a connection with the backend.
