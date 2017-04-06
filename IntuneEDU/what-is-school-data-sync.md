---
# required metadata

title: What is School Data Sync?
titleSuffix: Intune for Education
description: Use School Data Sync to import school groups and people into Azure AD.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 04/17/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope:
 - IntuneEDU

 # optional metadata

 #ROBOTS:
 #audience:
 #ms.devlang:
 #ms.reviewer:
 #ms.suite: ems
 #ms.tgt_pltfrm:
 #ms.custom:

---

# What is School Data Sync?

You can use Microsoft's School Data Sync (SDS) to import school records from an existing Student Information System (SIS) data with Intune for Education.

SDS duplicates the information from your SIS and stores it in Azure Active Directory (AD). Azure AD is a Microsoft management system that helps you organize students and devices. You can then use this data with Intune for Education to deploy apps and manage testing. [Learn more about how to deploy SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).

## How do I import data using SDS?

You can import information into SDS by using one of the following:
- [CSV files](https://support.office.com/article/Follow-these-steps-71d5fe4a-aa51-4f35-9b53-348898a390a1) - Manually export and compile comma-separated value (.csv) files
- [PowerSchool API](https://support.office.com/article/Follow-these-steps-851b5edc-558f-43a9-9122-b2d63458cb8f) - An SIS provider that simplifies syncing with Azure AD
- [Clever API](https://support.office.com/article/Follow-these-steps-f3d92fde-3ad0-48f3-80a1-1ad0ac4a3fae) - An identity management solution that syncs directly with Azure AD
- [OneRoster](https://support.office.com/article/Follow-these-steps-f43cbb2a-b502-497d-a8b1-783dc05a57ab) - A CSV format that you can export and convert to sync with Azure AD

You can also sync your Active Directory data to Azure AD by using AD Connect. [Learn more about AD Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).

## Find out more

- [Find out more about the full experience of syncing on-premises school data to Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect)
- [Find out more about Microsoft School Data Sync](https://sds.microsoft.com)
