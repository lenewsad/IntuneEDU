---
# required metadata

title: Express Configuration  | Intune for Education | Microsoft Docs
description:
keywords:
author: NathBarn
ms.author: nathbarn
manager: angrobe
ms.date: 03/24/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376

---

# Express Configuration

Express Configuration in Intune for Education helps you quickly provide a group of users the apps and settings they need. You can use Express Configuration any time you want to modify a group of devices. We’ve chosen some apps and default settings that we think you’ll find useful. You can change these choices to fit your needs.

Express Configuration has the following steps:
  1. [Get school information](#get-school-information)
  2. [Choose a group](#choose-a-group)
  3. [Choose apps](#choose-apps)
  4. [Choose settings](#choose-settings)
  5. [Next steps](#next-steps)

## Get school information

**Optional/Prep-work**: Before you can organize students and devices in Intune for Education, you'll want to sync your School Information System (SIS) with Intune. This makes information about student names, teacher names, and classes available in the Intune for Education console so you can assign specific apps and settings to groups of students and teachers.

There are a variety of ways this can be done, and it only needs to be done once. Express Configuration provides a link to [School Data Sync](school-data-service.md) to get information from your School Information System connected with Intune. This can be done in a variety of ways depending upon the services available to your school or school district.  Schools that use third-party services like PowerSchool or Clever can use those services to sync data with SDS. Or you can export data files from your information service and then import them to SDS. Either way, the information is added to Microsoft's Azure Active Directory service, which helps manage that data for Intune for Education. For more information, see [School Data Sync](school-data-service.md).

## Choose a group

During the Express Configuration process, you’ll start by selecting a group to configure.  A group in Intune for Education is a collection of device organized by their users, usually students and teachers, and divided into schools and classes. Intune for Education comes preset with groups based on the school information you imported. Any device or user assigned to a group receives that group's apps and settings as well as the apps and settings of any parent groups. To get started, you can select **All Users** to provide basic apps and settings that will be available to all teachers and students.

Select a group to set up, then click **Next** to continue.

## Choose apps

Next you choose apps to install on the selected group of devices. When you first run Express Configuration, you'll see any apps that you’re already managing in Intune as well as some recommended apps. You can select the apps to be installed. As with all Express Configuration settings, you can change installed apps later. You can also add apps from other sources such as web apps and apps from the Windows Store.

Select apps to install on selected group, and then click **Next**.

## Choose settings

Next, you’ll choose the device settings you want to apply to your group. During Express Configuration, you’ll see the basics that you might want to get up and running quickly. These settings aren't the full list available in Intune for Education. You can change these selections at any time to fit your needs and later you can view the full list in the Intune for Education console to fine-tune settings.

Settings available include:
- App settings
- Internet browser settings
- Networking and connection settings
- Sign in settings
- Basic device settings
- Device update settings

## Finish up

Once you've made your selections, you'll have a chance to review the apps and settings you've chosen. You can then click the **Finish** button or go back to any steps to modify these configurations.

After clicking **Finish**, you can **set up more groups** or be **done for now**. When you are done, you will be taken to the Intune for Education dashboard where you can continue to manage your devices, users and apps. You can come back to Express Configuration any time from the dashboard or the navigation menu to add, remove, or modify apps and settings for a group.

## Next steps

Once you have your groups setup with the apps and settings they need, you're ready to start using devices with Intune for Education.

>[!div class="step-by-step"]

><!-- [&larr; **Add apps**](.\add-apps.md) -->     [**Use devices** &rarr;](.\add-devices.md)
