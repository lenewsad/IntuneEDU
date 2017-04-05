---
# required metadata

title: Install apps
titleSuffix: Intune for Education
description: Learn how to manage apps with Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 03/24/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: 635a5cc7-7dd4-45f9-9b18-3eddb76d0c74
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tanmayb
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Install apps in Intune for Education

Installing apps on Windows 10 devices is one of the ways that Intune for Education can help your users get more done. Apps are installed onto devices after being assigned to a group. Some popular apps are available by default, but if the app you want to assign isn't, you need to [add it to Intune for Education](add-apps.md) before it can be assigned.

Intune for Education offers multiple ways to install apps onto devices.

##  Install apps for groups
This method lets you select a group and install one or more apps to the devices in that group.

1. In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose > **Manage Groups** to open the **Groups** blade.
2. Choose the group to which you want to deploy apps.
3. Choose **Apps** in the taskbar at the top to see a list of available apps.  
4. Choose the apps you want to deploy to that group. You can choose multiple apps.
5. Choose **Save** to deploy the selected apps to that group.

## Install apps with Express Configuration
This method lets you deploy multiple apps to a selected group using the [Express Configuration](what-is-express-configuration.md) process.

1. In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Express Configuration**.  
2. Choose the **Group** you want to add apps to. Choose **Next**.
3. Choose the apps you want to deploy to that group. Choose **Next**.

## Install apps to multiple groups
This method lets you select an app and deploy it to one or more groups.

1. In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Apps**.
2. In the list of apps on the left, choose the app you want to deploy.
3. Choose **Groups** from the tasks across the top, and then choose **Change group assignments**.
4. From the list, choose the groups you want to deploy the app to.
