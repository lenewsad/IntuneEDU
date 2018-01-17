---
# required metadata

title: "How do I delegate group management?"
titleSuffix: Intune for Education
description: Learn how to manage roles for groups in Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 01/17/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 9319be2e-cb7e-43c1-98fe-64281c8c09fd
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: rashok
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# What is delegating group management?

Your IT staff need to manage groups of students, teachers, and administrators in your school. Since group admins only need to manage specific groups, *delegating* access to different groups of admins makes sure those admins aren't making unauthorized changes. Admin groups are comprised of admins that do this kind of work.

## What can admins do to their delegated groups?

All admin roles have permission to access certain areas in Intune for Education. When delegating an admin group access to these areas, you are automatically assigning a built-in admin role with the right permission for managing school devices and apps.

Group admins are able to take a few different types of actions:

- View information about devices, users, and apps
- Assign, create, delete, view, and update device and user settings
- Assign, create, delete, view, and update apps
- View reports
- Take remote actions on devices, including resetting to factory settings, rebooting, locking an unlocked device, and forcing a sync

If you want to change the permissions or create a custom set of permissions, then you need to go to [the full management experience in Intune](group-admin-delegate.md#find-out-more).

## How do I assign admin groups?

1. Open the group that you want to allow the group admins to manage.
2. Open the **Group admins** tab on that group.
3. Click the **Add admins** button, then select **Choose group**.

Once you complete these steps, any of your group admins should be able to manage this group.

## Find out more

  - [Role-based administration control with Intune](https://docs.microsoft.com/intune/role-based-access-control)
