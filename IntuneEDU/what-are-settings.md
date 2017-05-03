---
# required metadata

title: What are settings?
titleSuffix: Intune for Education
description: Learn how to manage settings through Intune for Education policies.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/02/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: lpatha
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education


---

# What are settings?

_Settings_ are what you use to define how your users can work with their devices. This can either modify how the device responds to a user trying to take action, or by simply stopping a user from doing something on a device. Intune for Education settings allow you to manage features on school devices.

Settings are applied to groups. Since groups are set up as hierarchies, with one group above another, any [settings applied to a group are inherited by all of its subgroups](settings-inheritance.md). This makes it easier to apply settings to large groups of users, apps, and devices.

## Manage settings

There are three ways to manage settings in Intune for Education:

* __Express Configuration__: A selection of the most commonly used school settings are made available in [Express Configuration](how-do-i-manage-settings.md#manage-settings-with-express-configuration) so your students can be safe and productive using devices in classrooms.

* __Groups__: All settings can be managed for every individual group. This is an expanded list of settings compared to the ones available in Express Configuration. Find out what [settings are available to you here](available-settings.md).

* __Tenant Settings__: Tenant Settings affect all users and devices you have under management. These settings have can only be managed by certain admins with the [appropriate level of access to your tenant](what-are-tenants.md).

Settings can be set up and assigned to users and devices through Groups. Settings assigned to users in a group will stick with the user, no matter what device they are using. Settings assigned to devices in a group will be applied on the device no matter who logs on to the device.

## Find out more

- [Find out more about how to protect apps and data with the full management experience in Intune](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
