---
# required metadata

title: How should I enroll my devices?
titleSuffix: Intune for Education
description: Get advice for ways to enroll your devices in to Intune for Education.
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/02/2017
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 45160df9-126d-4c51-a0d3-0e9fad0fe929
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
#ms.reviewer: [ALIAS]
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom: intune-education

---

# How should I enroll devices?

There are a few ways that you can enroll devices into management by Intune for Education. You can use all of them interchangeably, but some may make more sense for you based on the size of your district, number of staff helping to enroll, and who will be receiving the devices. For example, you could give teachers their devices and tell them to enroll the devices themselves, while you could set up a quicker route for bulk enrollment using a USB key.

1. You can use the [Set up School PCs](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) app to quickly set up PCs for students. Set up School PCs makes it easy to set up Windows 10 PCs with Microsoft's recommended education settings, using a quick USB setup. This app guides you through the creation of a student PC provisioning package and helps you save it to a USB drive. From there, just plug the USB drive into student PCs running Windows 10 Creators Update (version 1703).

2. You can tell the users you're distributing the devices to that they should enroll the devices themselves. This will allow users to automatically join their machines to Azure AD.

3. You can have your [enrollment manager](what-are-enrollment-managers.md) enroll the devices for a group of users. This will automatically join their machines to Azure AD.

You will need to turn on [certain settings](https://docs.microsoft.com/education/windows/set-up-students-pcs-to-join-domain) if you should choose to manually join user's machines via Azure AD.

## Find out more

- [Download the **Set Up School PCs** app from the Microsoft Store](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40)
- [Find out more about setting up Windows devices for education](https://docs.microsoft.com/education/windows/set-up-windows-10)
