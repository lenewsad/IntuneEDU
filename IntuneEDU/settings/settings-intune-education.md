---
# required metadata

title: What are settings  | Intune for Education | Microsoft Docs
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
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101

---

# Settings in Intune for Education
Intune for Education helps you manage devices in your schools with groups of settings that are applied to those devices. Devices can be used to enable or disable device components like built-in cameras, removable storage, or location services. They can also manage software settings like disabling browser pop-ups, limiting which apps can be installed, or fine-tuning Windows Defender to protect devices from malware.

## Manage settings

Settings are managed on a per-group basis. You can manage the simple list of useful settings using [Express Setup](#manage-settings-in-express-setup) or view a full list of settings for a group for fine-tuning from [Groups management](#manage-settings-for-groups).

## Manage settings in Express setup

Use the following steps to manage simplified list of settings in Intune for Education:
1. In the [Intune for Education](https://manage.windowsazure.com) console, click **Launch Express Setup**. Review the **Welcome** page and click **Get started**.
2. Review the **Get school information** page. If you've already added school information, and then click **Next**.
3. Select the group whose settings you want to manage, and then click **Next**.
4. Review the list of apps, and then click **Next**.
5. On the **Settings** page, expand the categories of available settings:
  - [Basic device settings](#basic-device-settings)
  - [Internet browser settings](#internet-browser-settings)
  - [Device update settings](#device-update-settings)
  - [Networking and connection settings](#networking-and-connection-settings)
  - [App settings](#app-settings)
  - [Sign in settings](#sign-in-settings)

  Expand a category and toggle the control to modify settings, and then click **Next**.
6. Review your choices and then click **Finish** to save your changes update them on devices in the selected group.

### Manage settings for groups

Use the following steps to manage the full list of settings in Intune for Education:
1. In the [Intune for Education](https://manage.windowsazure.com) console, in the left-side navigation menu, click **Groups**.
2. Select the group whose settings you want to manage. For a complete list, see [Available settings](settings.md).
3. Click **Settings** at the top of the page to view the full list of available settings.
4. Expand categories and modify individual settings for the selected group.
5. Click **Save** to save the changes for that group. Settings are automatically sent to devices in that group.
