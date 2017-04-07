---
# required metadata

title: What are Enrollment Managers?
titleSuffix: Intune for Education
description: Learn how to use Enrollment Managers in Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 04/17/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: b496bc02-714e-4391-b533-4c9bdcf57483
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: [ALIAS]
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# What are Enrollment Managers in Intune for Education?

There are many [roles](core-concepts.md#role-based-access-controls) that Intune for Education uses to make sure you've got the right access assigned to the right IT staff. One commonly-used role is the _Enrollment Manager_.

  ![Dashboard left hand side](./media/dashboard-002-left-sidebar-list.png)

The Enrollment Manager has one job: to help you enroll multiple devices at speed. When you select __Enrollment Managers__ from the sidebar, it will show you the list of currently authorized Enrollment Managers.

  ![Current enrollment managers list, one person represented](./media/enroll-mgrs-001-current-list-of-mgrs.png)

Select the person to assign a Enrollment Manager permissions to, then select __Save__.

## Removing Enrollment Managers

You use the same list to remove individual's Enrollment User access. Locate the name of the Enrollment Manager you wish to remove, then select **Remove Enrollment Permissions**.

  ![Remove enrollment permissions button selected while viewing an individual enrollment manager's page](./media/enroll-mgrs-003-remove-enrollment-permissions.png)

Even though that user is no longer an Enrollment Manager, the devices that they enrolled while they were enrollment manager will remain managed by Intune for Education.
