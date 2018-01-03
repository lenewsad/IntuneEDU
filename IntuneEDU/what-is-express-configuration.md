---
# required metadata

title: What is Express Configuration?
titleSuffix: Intune for Education
description: Use Express Configuration to quickly set up your groups in Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope:
 - IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: travisj
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# What is Express Configuration?

Express Configuration is one of the tiles that you see when you first sign in to [Intune for Education](https://intuneeducation.portal.azure.com).

  ![The Express Configuration tile, which says Launch Express Configuration - Click here to choose apps and settings for a group.](./media/express-config-001-launch-tile.png)

Express Configuration helps you quickly provide users and devices with the apps and settings they need. It's not something that you're limited to just using once; you can use it anytime you want to make changes to any group you manage. We’ve chosen some apps and default settings that we think you’ll find useful. You can change these choices to fit your needs.

## Choose a group

You’ll start by selecting a group to configure.

  ![The choose group screen, which asks users to select a group.](./media/express-config-004-choose-group.png)

A _group_ in Intune for Education is a collection of devices or users that are organized to make it easy to understand who or what you're configuring in the console. This could be devices (like _Sixth Grade Computer Cart_) or users (like _Fourth Grade Students_ or _Biology Teachers_). Intune for Education comes preset with groups based on the school information you've provided. We've got more information about groups available in our [groups articles](what-are-groups.md).

We recommend that you start by assigning settings that you know **All Users** will need, like password requirements or blocking pop-ups in Microsoft Edge.

Select a group to set up, then choose **Next** to continue.

## Choose apps

Now, you'll choose apps to assign to this group.

  ![The app assignment screen. Apps are organized for assignment by different types, including web apps and Microsoft Store for Education apps.](./media/express-config-005-choose-apps.png)

There are a few types of apps that you can install on devices:

* [Web apps](how-to-add-apps.md#add-web-apps)
* [Desktop apps](how-to-add-apps.md#add-desktop-apps)
* [Microsoft Store for Education apps](acquire-store-apps.md)

Intune for Education also displays [popular apps from the Microsoft Store for Education](how-to-add-apps.md#add-popular-apps) from across all Intune for Education users.

Select apps to assign to this group, then choose **Next** to continue.

## Choose settings

Next, you’ll choose the settings you want to apply to the devices or users in your group.

  ![The choose settings screen. Settings are organized into a collapsed list, including divisions such as device sharing, basic device settings, app settings, browser settings, and more.](./media/express-config-006-choose-settings.png)

Express Configuration shows you settings that you may want to get your groups ready to go. We've chosen these settings to make it easier for your users to quickly begin using their devices. You don't have to make any modifications if you want to use our recommendations, or you can customize these settings to meet specific needs.

You can change Express Configuration selections at any time to fit any changes you need to make, and customize your settings even further using the full [list of settings available as part of Intune for Education](available-settings.md).

## Finish up

After you make your selections, you have a chance to review the apps and settings you've chosen. You can then choose the **Finish** button or go back to any steps to modify these settings.

  ![The review your choices screen. It shows the apps and settings selected during Express Configuration.](./media/express-config-007-save-changes.png)

After you choose **Finish**, you can **Configure more groups** or be **All done**.

  ![The completion screen. It shows the configure more groups and completed options. The All Done option offers a short explanation of what's next in the process, including adding devices to Intune for Education by joining them to Azure Active Directory.](./media/express-config-008-all-done.png)

When you are done, you will be taken to the Intune for Education dashboard where you can continue to manage your devices, users, and apps. You can come back to Express Configuration any time from the dashboard or the navigation menu to add, remove, or modify apps and settings for any group.

## Next steps

After you have set up your groups with the apps and settings they need, you're ready to start using devices with Intune for Education.

## Find out more
- [Find out more about the settings available in the full management experience in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
