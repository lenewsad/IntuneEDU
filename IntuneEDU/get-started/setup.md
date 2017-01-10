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

Express Configuration in Intune for Education helps you quickly provide a group of users the apps and settings they need. You can use Express Configuration any time you want to modify a group of devices. We’ve chosen some apps and default settings that we think you’ll find useful to apply to the group you are configuring. You can change these choices to fit your needs.

Express Configuration doesn't use all the settings available in Intune for Education. Instead, it gives you the basics you’ll want to configure to get started. Once you finish Express Configuration, you'll be ready to go, and you can manage additional settings from the Intune for Education dashboard.

Express Configuration has the following steps:
  1. [Get school information](#get-school-information)
  2. [Choose a group](#choose-a-group)
  3. [Choose apps](#choose-apps)
  4. [Choose settings](#choose-settings)
  5. [Next steps](#next-steps)

## Get school information

Before you can organize students and devices in Intune for Education, you'll want to sync your School Information System (SIS) with Intune.  Express Configuration provides a link to [School Data Sync](get-started/school-data-service.md) to get student and teacher information from your School Information System connected with Intune. This can be done in a variety of ways depending upon the services available to your school or school district.  Schools that use third-party services like PowerSchool or Clever can use those services to sync data. Or you can export data files. Either way, the information is added to Microsoft's Azure Active Directory service, which helps manage that data for Intune for Education. For more information on syncing data, see [School Data Sync](get-started/school-data-service.md).

## Choose a group

During the Express Configuration process, you’ll start by selecting a group to configure. Intune for Education comes preset with groups based on the information you imported. Any device assigned to a group receives that group's apps and settings as well as the apps and settings of any parent groups. To get stated, you can select **All Users** to provide basic apps and settings that will be available to all teachers and students.

Select a group to manage, then click **Next** to continue.

## Choose apps

Next you choose apps to install on the selected group of devices. Some recommended apps are displayed when you first run Express Configuration. You can select the apps to be installed. As with all Express Configuration settings, you can change installed apps later. You can also add apps from other sources such as web apps and apps from the Windows Store.

Select apps to install on selected group, and then click **Next**.

## Choose settings

Next, you’ll choose the device settings you want to apply to your group. These settings aren't the full list available in Intune for Education. During Express Configuration, you’ll see the basics that you might want to get up and running quickly. You can change these selections at any time to fit your needs.

Settings available include:
- App settings
- Internet browser settings
- Networking and connections settings
- Sign in settings
- Basic device settings
- Device update settings

## Finish up

Once you've made your selections, you'll have a chance to review the apps and settings you've chosen. You can then click the **Finish** button or go back to any steps to modify these configurations.

After clicking **Finish**, you can **set up more groups** or be **done for now**. Remember you can come back to Express Configuration any time to manage a group's apps and settings.

## Next steps

Once you have your groups setup with the apps and settings they need, you're ready to start using devices with Intune for Education.

>[!div class="step-by-step"]

><!-- [&larr; **Add apps**](.\add-apps.md) -->     [**Use devices** &rarr;](.\use-devices.md)
