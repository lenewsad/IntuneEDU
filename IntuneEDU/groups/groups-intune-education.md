---
# required metadata

title: What are groups?  | Intune for Education | Microsoft Docs
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
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468

---

# Groups in Intune for Education

Groups are used to manage users and devices in Intune for Education. You can group a set of students or a set of devices to apply settings and assign apps to the group. When you create groups, consider how you will apply the settings and apps to users and devices.

Intune for Education provides a set of default groups when your tenant is created. These default groups represent the broadest categories of users and devices in your school or school district. A few default groups that Intune for Education provides cannot be modified. You can, however, rename, move or delete the groups as needed.

## Create a new group

To create a new group:
1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2.	Select **Create Group**.
3.	Enter a **Group Name**.
4.	Click **Create Group**.

## Create a subgroup
You can create subgroups under any group except certain default groups.  

**To create a subgroup**
1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group beneath which you want to create a subgroup.
3.	Click **Create subgroup** either in the ellipses menu or in the task list.
3.	Enter the **Group Name**.
4.	Select **Create Group**.
5.	Subgroup appears under the group you selected.

## Edit membership of a group
You can edit both device or user members of an existing group.

**Edit devices in a group**
1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group whose device membership you want to edit.
3. Click the **Devices** tab.
4. Click the **Edit devices** button.
5.	Select the appropriate option:
- Click **Add Devices** to add more devices from a list
- Click **X** next to a device to delete a device
6.	Click **Ok** to save your changes.

## Rename a group

1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group that needs to be renamed.
3.	Click **Rename** either in the ellipses menu or in the task list.
4.	Enter the new **Name**.
5.	Select **OK** to save your changes.

## Move an existing group
You can move a group within the group structure:
1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group that needs to be Moved
3.	Click **Move group** either in the ellipses menu list or by clicking **Move group** button.
4.	Select the group location to which you want to move the group by either searching a group name or by selecting it in the hierarchy.
5.	Select **Ok** to save your changes.

> [!NOTE]
> If the group you selected is a member of more than one group, moving that group removes it from all other groups. The group you select will become its only location.  

## Delete a group

1.	In the [Intune for Education portal](https://manage.windowsazure.com), click the **Manage Groups** workplace.  The **Groups** blade opens.
2. Select the group you want to delete
2.	Click **Delete group** either in the ellipses menu or task list.

>[!div class="step-by-step"]

><!-- [&larr; **Add apps**](.\add-apps.md) -->     [**Install apps** &rarr;](.\install-apps.md)
