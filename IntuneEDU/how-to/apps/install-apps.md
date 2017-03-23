---
# required metadata

title: Install apps 
titleSuffix: Intune for Education
description:
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

You can install apps on groups of devices using Intune for Education. The app is automatically installed on all devices in targeted groups. Before an app can be deployed, it must be added to Intune for Education. Some popular apps are available by default. Before you can install apps, you must first [add apps](add-apps.md) to Intune for Education. <!--- Linda: The 3rd sentence is repetitive if you've been reading the content in order as I have--but we know that won't always be the case. Having some kind of graphic as I suggested in another topic might be a more interesting way of saying "You are here" and "you need to have done X already." Just a thought. --->

You can install apps in the following ways: <!---This is a kind of in-page TOC which is not allowed by the PR guidelines Tyson just went over with us. I see what you're trying to do, but you may get push back. -->
- [Install apps for a group](#install-apps-for-a-group)
- [Install apps using Express Configuration](#install-apps-with-express-configuration)
- [Select an app to install on multiple groups](#deploy-an-app-to-multiple-groups)

##  Install apps for groups
This method lets you select a group and install one or more apps to the devices in that group.
1. In the [Intune for Education portal](https://manage.windowsazure.com)<!---Is this the right URL?--->, choose > **Manage Groups** to open the**Groups** blade.
2. Choose the group to which you want to deploy apps.
3. Choose **Apps** in the taskbar at the top to see a list of available apps.  
4. Choose the apps you want to deploy to that group. You can choose multiple apps.
5. Choose **Save** to deploy the selected apps to that group.

## Install apps with Express Configuration
This method lets you deploy multiple apps to a selected group using the Express Configuration process.
1. In the [Intune for Education portal](https://manage.windowsazure.com), choose **Express Configuration**.  
2. Choose the **Group** you want to add apps to. Choose **Next**.
3. Choose the apps you want to deploy to that group. Choose **Next**. <!---Is this really the last step? --->

## Install apps to multiple groups
This method lets you select an app and deploy it to one or more groups.
1. In the [Intune for Education portal](https://manage.windowsazure.com), choose **Apps**.
2. In the list of apps on the left, choose the app you want to deploy.
3. Choose **Groups** from the tasks across the top, and then choose **Change group assignments**.
4. From the list, choose the groups you want to deploy the app to. <!---is this really the last step? --->




>[&larr; **Add apps**](.\add-apps.md)     <!-- [**Manage Intune licenses** &rarr;](.\start-with-a-paid-subscription-to-microsoft-intune-step-4.md)  -->
