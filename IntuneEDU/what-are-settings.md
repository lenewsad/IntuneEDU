---
# required metadata

title: What are policy settings?
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

# What are configuration settings?
All settings are managed on a per-group basis. You can manage the simple list of settings settings using [Express Configuration](how-do-i-manage-settings.md#manage-settings-in-express-configuration) or view a full list of settings for [working with groups](how-do-i-manage-settings.md#manage-settings-for-groups).


## Are there any other kinds of settings?
The only settings in Intune for Education that you cannot use here are tenant settings. Configuration settings modify user, app, and device behavior for your organization. Find out how to manage [tenant settings for your subscription](what-are-tenants.md).


## Manage settings

Settings are managed on a per-group basis. You can manage the simple list of useful settings using [Express Configuration](how-do-i-manage-settings.md#manage-settings-in-express-configuration) or view a full list of settings for [working with groups](what-are-settings.md#manage-settings-for-groups).

Device settings apply to all devices in their group. Settings that are **Not configured** allow the user to define their settings on their devices themselves.

> [!NOTE]
> Intune for Education settings such as **Block** or **Allow** override the device’s settings. For example, if a device has a camera and that camera is enabled by default, but the group setting for that device has Camera set to **Block**, [then the camera on the device will be turned off](settings-inheritance.md).


## Find out more

-
