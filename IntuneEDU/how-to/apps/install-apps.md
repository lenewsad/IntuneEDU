---
# required metadata

title: Install apps  | Intune for Education | Microsoft Docs
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

You can install apps on groups of devices using Intune for Education. The app is automatically installed on all devices in targeted groups. Before an app can be deployed, it must be added to Intune for Education. Some popular apps are available by default. Before you can install apps, you must first [add apps](add-apps.md) to Intune for Education.

You can install apps in the following ways:
- [Install apps for a group](#install-apps-for-a-group)
- [Install apps using Express Configuration](#install-apps-with-express-configuration)
- [Select an app to install on multiple groups](#deploy-an-app-to-multiple-groups)

##  Install apps for groups
This method lets you select a group and install one or more apps to the devices in that group.
1. In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group to which you want to deploy apps.
3. Select **Apps** in the taskbar at the top to see a list of available apps.  
4. Select the apps you want to deploy to that group. You can select multiple apps.
5. Click **Save** to deploy the selected apps to that group.

## Install apps with Express Configuration
This method lets you deploy multiple apps to a selected group using the Express Configuration process.
1. In the [Intune for Education portal](https://manage.windowsazure.com), click the **Express Configuration** workplace.  
2. In the Express Configuration workflow, select the **Group** you want to add apps to and then click **Next**.
3. Select the apps you want to deploy to that group, and then click **Next**.

## Install apps to multiple groups
This method lets you select an app and deploy it to one or more groups.
1. In the [Intune for Education portal](https://manage.windowsazure.com), click the **Apps** workplace.
2. In the list of apps on the left, select the app you want to deploy.
3. Select **Groups** from the tasks across the top and then select **Change group assignments**.
4. From the list, select the groups you want to deploy the app.




>[&larr; **Add apps**](.\add-apps.md)     <!-- [**Manage Intune licenses** &rarr;](.\start-with-a-paid-subscription-to-microsoft-intune-step-4.md)  -->
