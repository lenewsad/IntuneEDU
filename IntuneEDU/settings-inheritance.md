---
# required metadata

title: What is group inheritance?
titleSuffix: Intune for Education
description: Learn how to manage groups of devices with Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/02/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
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

# What is settings inheritance?

Settings are applied to groups. Since groups are set up as hierarchies, with one group above another, any settings applied to a group are inherited by all of its subgroups. This makes it easier to apply settings to large groups of users, apps, and devices.

  ![A tree of groups of and subgroups.](./media/groups-002-inheritance.png)

This means that for any group with a subgroup underneath it, the subgroup will automatically inherit whatever changes you make to the group above it. This is called _inheritance_.

## What if settings inheritance doesn't work for part of my school or organization?

Let's assume that you're configuring devices for a school district, and that you've organized all devices as __School District__ > __School__ > __Grade__ > __Cart Number__. Halfway through the year, one of the schools adds a computer lab, so there's now a group of devices that doesn't work according to your current setup — for example, they can only remain logged in for only 30 minutes before automatically logging out. This is where overriding settings comes into play.

  ![Are you sure you want to override settings?](./media/groups-003-beginning-to-deviate-from-inheritance.png)

If the __Computer Lab__ group under the __School__ group needs to have different settings, you can override the inheritance of settings from the group to the subgroup.

  ![Beginning to deviate from inheritance.](./media/groups-004-are-you-sure-you-want-to-override-settings.png)

Overriding inheritance means that you must manually manage that group's settings. When you break this chain, all inheritance is broken — including for any new settings you apply to groups higher up in the list.

You can also restore inheritance and the settings from groups to back to subgroups.

  ![Resetting inheritance](./media/groups-005-reset-inheritance.png)

When you do this, Intune for Education will reset the settings to show what the settings were for the higher-level group.

## What happens if I apply multiple settings to the same user or device?

When multiple settings have been applied to the same group, each setting is analyzed individually by Intune for Education. Certain settings that force users to take action to make their devices comply with your settings will always take precedence over other settings.

Consider a subgroup, *Twelfth Grade AP Computer Science*, to the group *Twelfth Grade*. You know that the AP computer science class will need to download some JavaScript files that do not need security scanning, but you want to make sure that the whole grade does not try to do the same. If you do not override settings inheritance, the more restrictive *Twelfth Grade* setting will be applied to the users in *Twelfth Grade AP Computer Science*.

## Can I ever have settings that don't work together?

Intune for Education will allow you to apply a wide range of settings to your Windows 10 devices. This can sometimes cause an issue where one of your settings may conflict with another setting. You can see settings that are actively conflicting in the [settings conflict report](what-are-reports.md)

## Find out more

- [Find out more about the full groups experience in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
