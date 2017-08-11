---
# required metadata

title: What is School Data Sync?
titleSuffix: Intune for Education
description: Use School Data Sync to import school groups and people into Azure AD.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 08/11/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
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

# What is School Data Sync?

You can use Microsoft's School Data Sync (SDS) to import school records from an existing Student Information System (SIS) data with Intune for Education.

SDS duplicates the information from your SIS and stores it in Azure Active Directory (AD). Azure AD is a Microsoft management system that helps you organize students and devices. You can then use this data with Intune for Education to deploy apps and manage settings. [Learn more about how to deploy SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).

When importing student information from your SIS into Intune for Education with School Data Sync, make sure that you include __Grade__ and __Graduation Year__ if you intend to make [dynamic groups](what-are-groups#managing-groups-and-subgroups) with those properties. This is under __Student options__ > __Select student properties__. You use this information to create a profile.  

## Find out more

- [Find out more about Microsoft School Data Sync](https://sds.microsoft.com)
