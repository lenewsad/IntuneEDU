---
# required metadata

title: What are groups?
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
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tanmayb
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# What are groups?

Intune for Education uses _groups_ to manage users and devices. You can group users or devices together instead of having to manage each device individually. This lets you easily assign apps and settings to large numbers of users and devices.

When you create groups, consider how you will apply the settings and apps to users and devices. For example, you may need to block apps from using location services for all devices. An alternative to this is how specific groups may need certain things, like giving students taking [AP Computer Science](https://www.tealsk12.org) apps to edit their code.

Intune for Education automatically creates the __All Devices__ and __All Users__ groups when your tenant is created. These default groups represent the broadest categories of users and devices in your school or school district, and [cannot be moved](why-cant-i-move-this-group.md).

## Managing groups and subgroups

You can create groups by navigating to **Groups**, then selecting **Create Group** from the top of the group list. You can further organize groups by creating *subgroups* under any group, except for __All Devices__ or __All Users__.

  ![The create subgroup page, with the two locations for subgroup creation — at the top of the group name and the sidebar — encircled in red](./media/groups-007-create-subgroup.png)

1. In the [Intune for Education console](https://intuneeducation.portal.azure.com), select **Manage user and device groups**.
2. Select the group beneath which you want to create a subgroup.
3. Click **Create subgroup**, then enter the **Group Name**.

## Edit group membership

After you've created a group, it's possible that you'll need to edit its membership — for example, if a device needs to transferred to another school in your district.

  ![Editing devices in a group](./media/groups-008-edit-group-membership.png)

1. In the [Intune for Education portal](https://intuneeducation.portal.azure.com), select **Manage Groups**.
2. Select the group whose members you want to edit.
3. Click the **Devices** tab.
4. Click the **Edit devices** button.
5. Select the appropriate option:
  * Click **Add Devices** to add more devices from a list
  * Click **X** next to a device to delete a device

  Click **OK** to save your changes.

## Rename a group

  ![Rename a group buttons encircled in red](./media/groups-009-rename-group.png)

1.	In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Manage Groups**.
2. Select the group that needs to be renamed.
3.	Click **Rename** either by clicking the **Rename** button.
4.	Enter the new **Name**.
5.	Select **OK** to save your changes.

## Move a group

You can move a group within your group structure, or **hierarchy**.

  ![Move group buttons encircled in red](./media/groups-010-move-groups.png)

1.	In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Manage Groups**.
2. Select the group that needs to be Moved.
3.	Click **Move group** either in the menu list or by choosing the **Move group** button.
4.	Select the group location to which you want to move the group by either searching a group name or by selecting it in the hierarchy.
5.	Select **OK** to save your changes.

## Delete a group
When you delete a group, Intune for Education removes the collection of apps and settings on any device that is a member of that group. Deleting a group will not remove those users or devices from management.

  ![Delete groups buttons encircled in red](./media/groups-011-delete-groups.png)

1.	In the [Intune for Education portal](https://intuneeducation.portal.azure.com), choose **Manage Groups**.
2. Select the group you want to delete
3.	Click **Delete group** either in the task list.

## Find out more

- [Find out more about the full groups management experience in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
