---
# required metadata

title: Available settings
titleSuffix: Intune for Education
description:
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 04/17/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tanmayb
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Available settings for Intune for Education

Managing settings is one of the key ways you can secure your Windows 10 devices and create the right kinds of access to enhance the learning experience. Intune for Education provides many settings that allow you to customize these experiences, both for individual groups and their subgroups.

Most settings are set up to either **Block** or **Allow** access to a certain device feature, where **Not configured** is the device's default setting or a user-chosen setting.

> [!NOTE]
> These user, app, and device settings differ from [tenant settings](tenant-settings.md).

You can find these settings by first selecting a **group**, then choosing **Settings**.

  ![The settings page for a group](./media/settings-001-list-of-settings.png)

Much of the information in the **What it does** column can also be found in the Intune for Education console; this format is designed to make it easier for you to search through the settings for specific items.

## Basic device settings

|Setting|What it does|
|---|---|
|Camera|Block user access to the device camera.|
|Removable storage|Block users from using removable storage such as USB drives and external hard drives.|
|Date and time|Block users from changing the device date and time settings.|
|Device name|Block users from changing the device name.|
|Language settings|Block users from changing the device language.|
|Unenroll devices|Block users from manually unenrolling devices from management.|
|Send diagnostic data|Define whether to collect and send anonymous usage data to Microsoft to help improve Windows.|
|Add provisioning packages|Block users from adding add new provisioning packages containing device configuration settings.|
|Remove provisioning packages|Block users from removing provisioning packages containing device configuration settings.|
|Location services|Block apps from using location services to access the device’s location.|
|Internet Sharing|Block users from using Internet Sharing to share the device’s Internet connection.|
|Cortana|Block Cortana, the digital assistant built into Windows 10 that can answer questions and perform tasks.|
|Device region settings|Block users from changing region settings, such as country and language.|
|Save files to local hard drive|Block users from saving files locally.|
|Power and sleep settings|Block users from changing power and sleep settings.|
|Start menu size|Define whether to force the Start menu to appear full screen.|
|Windows Spotlight|Block all Windows Spotlight features on these devices.|
|OneDrive Sync|Block OneDrive Sync for these devices and users.|

## Microsoft Edge settings

|Setting|What it does|
|---|---|
|Pop-ups|Block websites from opening new windows.|
|Do-Not-Track headers|Require Microsoft Edge to ask that websites not track user data.|
|Cookies|Cookies can store website settings or track user’s browsing behavior.|
|Automatically fill form entries|Block saving data entered in a form field online.|
|Password manager|Block users from using the password manager to save passwords.|
|Developer tools|Block users from accessing developer tools.|
|Browser extensions|Block users from using extensions to customize Edge with added functionality from Microsoft and other sources.|
|InPrivate browsing|Block users from using InPrivate browsing, which stops Edge from saving data like browsing history and cookies.|
|Access to about:flags page|Block access to the about:flags page, which contains experimental settings and features.|
|SmartScreen override|Block users from ignoring warnings about websites blocked by the SmartScreen Filter.|
|SmartScreen override for files|Block users from ignoring SmartScreen Filter warnings about downloading unverified files.|
|Block adult content using a strict SafeSearch filter|Setting to “Block” will use a strict rather than moderate SafeSearch filter to block adult content.|
|Search suggestions|Block Edge from suggesting possible websites as you type a URL or search term.|
|Intranet traffic in Internet Explorer|If set to “Block”, internal traffic will be sent to Edge instead of Internet Explorer.|
|JavaScript|Block JavaScript from running in Edge.|
|Default search engine|Select Bing, Yahoo, or Google as the default search engine for Microsoft Edge. If you or another admin has set up a custom search engine in the full Intune experience, you can define that custom search engine as the default here.|
|Configure Microsoft Edge homepages|Choose what homepages open every time someone begins a new session browsing with Microsoft Edge.|
|Configure Microsoft Edge favorites|Choose websites to appear in the Microsoft Edge favorites list.|
|Block editing favorites|Block users from editing Edge browser favorites.|

## User access to device settings

|Setting|What it does|
|---|---|

## Device update settings

|Setting|What it does|
|---|---|

## Windows Defender settings

> [!NOTE]
> Certain Windows Defender settings are available at the [tenant](tenant-settings.md) level.

|Setting|What it does|
|---|---|
|Block user access to Windows Defender settings|Block users from modifying Windows Defender settings on the device.|
|Real-time monitoring|Enable always-on scanning for malware, spyware, and other threats.|
|Behavior monitoring|Enable Defender to check for certain known patterns of suspicious activity.|
|Network Inspection Service|Helps protect devices against network-based exploits by using the signatures of known vulnerabilities from the Microsoft Endpoint Protection Center to help detect and block malicious traffic.|
|Scan all downloaded files|Automatically scan all downloaded files for malware.|
|Scan scripts run in Microsoft web browsers|Scan all scripts a website attempts to run in Edge and Internet Explorer.|
|Update frequency|Define how frequently Defender checks for and downloads anti-malware updates.|
|Scan file and program activity|Scan for malware when files or programs are opened and alerts users of suspicious activity.|
|Days before quarantined malware is removed|Define the number of days that a file is saved before removing (0 = immediately delete).|
|Cloud-based protection|Get real-time protection when Defender sends info to Microsoft about potential security threats. This feature works best with “Prompt users for sample submission” set to automatically send samples.|
|Prompt users for sample submission|Define whether files that might need further analysis are automatically sent to Microsoft.|
|Detect and block potentially unwanted applications|Defender will alert the user and block potentially unwanted software that attempts to install itself on devices.|
|Exclude files with these extensions from scans and real-time protection|Define the types of files you want users to be able to access without scanning for security threats.|

## Wireless settings

|Setting|What it does|
|---|---|
|Cellular roaming data|Block devices from using cellular data plans when roaming.|
|Bluetooth|Block devices from using Bluetooth.|
|Bluetooth discoverability|Block devices from being set as discoverable using Bluetooth.|
|Bluetooth advertising|Block devices from receiving advertising over Bluetooth.|
|Wi-Fi|Block devices from using Wi-Fi.|
|Automatically connect to open Wi-Fi hotspots|If you've enabled **Wi-Fi**, you can choose whether to block devices from automatically connecting to Wi-Fi hotspots.|
|Automatically detect proxy settings|If you've set up proxy to handle device network traffic, you can choose whether devices automatically detect the proxy settings when connected.|
|Use proxy script|Enable the use of a proxy script for your devices. If you **Allow** this setting, you will need to provide a **Setup script address**.|
|Use manual proxy server configuration|If you've set up a manual proxy, you can define settings for it here. If you **Allow** this setting, you will need to provide the **Proxy server address**, **Port**, **Proxy exceptions**, and whether to **Use proxy server for local (intranet) connections**.|


## Device sharing settings

|Setting|What it does|
|---|---|
|Optimize devices for shared use|Configures recommended settings for shared devices, such as power and update management, and allowing multiple users to sign on to the same device.|
|Block guest users|If you've enabled **Optimize devices for shared use**, then you can also choose whether to block guest users from signing in to devices. If blocked, only domain users can sign in.|
|Fast user switching|Allow users to quickly switch between user accounts from the Start menu.|

## App settings

|Setting|What it does|
|---|---|
|Microsoft Store for Business apps|Block users from installing apps from Microsoft Store for Business.|
|Require Microsoft Store for Business apps to be installed from private store|Only allow users to install apps from the Microsoft Store for Business that your organization has set up.|
|Trusted apps|Define whether users can install trusted apps signed by Microsoft.|
|Untrusted apps|Define whether users can install unsigned apps or apps signed by external sources that are not trusted by Microsoft.|
|Automatic app updates|Block Microsoft Store for Business apps from being updated automatically.|
|Shared app data between users|Allow multiple users of shared devices to share app data.|

## Sign-in settings

|Setting|What it does|
|---|---|
|Sign in using Microsoft account|Block users from signing in with their Microsoft account.|
|Sign in using non-Microsoft account|Block users from signing in with any account other than their Microsoft account. Use this setting if you want to force users to sign in with, among other Microsoft accounts, their Office 365 account.|

## Windows interface customizations
|---|---|

## Email settings

Choose whether email settings are configured for this group.

## Wi-Fi settings

## Edition upgrade

Allows you to specify whether devices are upgraded to a particular edition of Windows 10 and assign a **Product key**.

## Find out more

- [Find out more about the full Windows 10 settings management experience available in Intune](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune)
