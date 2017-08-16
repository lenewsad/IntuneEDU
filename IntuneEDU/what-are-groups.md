---
# required metadata

title: What are groups?
titleSuffix: Intune for Education
description: Learn how to manage groups of devices with Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 08/11/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: lpatha
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# What are groups?

You use _groups_ to manage users, apps, and devices in Intune for Education. You can group users or devices together instead of having to manage each device individually. This lets you easily assign apps and settings to large numbers of users and devices.

When you create groups, consider how you will apply the settings and apps to users and devices. For example, you may need to block apps from using location services for all devices. An alternative to this is how specific groups may need certain things, like giving students taking [AP Computer Science](https://www.tealsk12.org) apps to edit their code.

Settings are applied to groups. Since groups are set up as hierarchies, with one group above another, [any settings applied to a group are inherited by all of its subgroups](settings-inheritance.md). This makes it easier to apply settings to large groups of users, apps, and devices.

Intune for Education automatically creates the __All Devices__ and __All Users__ groups when your tenant is created. These default groups represent the broadest categories of users and devices in your school or school district, and [cannot be moved](what-are-groups.md#why-cant-i-move-certain-groups).

## Group types

There are two types of groups that you can use to organize objects, such as users and devices, in Intune for Education. **Assigned** groups and **Dynamic** groups. 

### Dynamic

- No subgroups
- Convert group types from Assigned to Dynamic

Dynamic groups are built using rules, and do not contain objects in the same way that Assigned groups do. You can't edit the membership of objects in a Dynamic group without going back and editing the rules that determine what objects appear in that group. 

### Assigned

## Managing groups and subgroups

You can create groups by navigating to **Groups**, then selecting **Create Group** from the top of the group list. You can further organize groups by creating *subgroups* under any group, except for __All Devices__ or __All Users__.

  ![The create subgroup page, with the two locations for subgroup creation — at the top of the group name and the sidebar — encircled in red](./media/groups-007-create-subgroup.png)

1. In the [Intune for Education console](https://intuneeducation.portal.azure.com), select **Manage user and device groups**.
2. Select the group beneath which you want to create a subgroup.
3. Click **Create subgroup**, then enter the **Group Name**.

## Making changes to groups

After you've created a group, it's possible that you'll need to edit its membership — for example, if a device needs to transferred to another school in your district.

  ![Editing devices in a group](./media/groups-008-edit-group-membership.png)

1. Select the group whose members you want to edit.
2. Select the **Devices** tab.
3. Select the **Edit devices** button, then choose **Add Devices** to add more devices from a list or the **X** next to a device to delete it.

If you need to rename a group, select the group that needs to be renamed, then the **Rename** button to edit the name.

## Move a group

You can move a group within your group structure, or **hierarchy**.

  ![Move group buttons encircled in red](./media/groups-010-move-groups.png)

1.	In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Manage Groups**.
2. Select the group that needs to be Moved.
3.	Click **Move group** either in the menu list or by choosing the **Move group** button.
4.	Select the group location to which you want to move the group by either searching a group name or by selecting it in the hierarchy.
5.	Select **OK** to save your changes.

## Why can't I change the "All Devices", "All Users", "All Students", or "All Teachers" groups?

Intune for Education provides a set of default groups that are created when your [school's account is created](what-are-tenants.md]. These groups, **All Users** and **All Devices**, cannot be changed as they contain a dynamic list of all users and all devices. The **All Teachers** and **All Students** groups are similarly created after School Data Sync has imported student and teacher data into Intune for Education.

This may rarely cause an issue where you may end up with a subgroup underneath two groups.

  ![Subgroup under multiple groups error message appears](./media/groups-012-subgroup-is-under-two-groups-warning.png)

If this happens, you'll need to choose a single group to place above this subgroup.

## Why can't I edit this group? 

Intune for Education is made to be a streamlined way to manage your devices in your schools. It uses Intune, an enterprise product, to act as the backbone of how it manages apps and groups. Certain admins in your organization will use both the full Intune console and the Intune for Education console to create specialty groups. You will need to ask the IT admin with the most access to your systems to modify these groups. 

## Delete a group

When you delete a group, Intune for Education removes the collection of apps and settings on any device that is a member of that group. Deleting a group will not remove those users or devices from management.

  ![Delete groups buttons encircled in red](./media/groups-011-delete-groups.png)

1.	In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Manage Groups**.
2. Select the group you want to delete
3.	Click **Delete group** either in the task list.

## Find out more

- [Find out more about the full groups management experience in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
