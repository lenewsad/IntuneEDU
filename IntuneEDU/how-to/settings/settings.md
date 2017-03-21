---
# required metadata

title: Available settings  | Intune for Education | Microsoft Docs
description:
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 03/24/2017
ms.topic: article
ms.prod:
ms.service:
ms.technology:
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1

---

# Available settings for Intune for Education

Intune for Education allows you to manage the following categories settings.:

- [Basic device settings](#basic-device-settings)
- [Internet browser settings](#internet-browser-settings)
- [Device update settings](#device-update-settings)
- [Windows Defender settings](#windows-defender-settings) (advanced)
- [Networking and connection settings](#networking-and-connectivity)
- [Device sharing](#device-sharing)
- [App settings](#app-settings)
- [Sign in settings](#app-settings)
- [Email settings](#email-settings) (advanced)
- [Edition upgrade settings](#edition-upgrade-settings) (advanced)
- [Sign in settings](#sign-in-settings)
- [Email settings](#email-settings) (advanced)
- [Edition upgrade](#edition-upgrade) (advanced)

Settings marked **(advanced)** are not included in Express Configuration, but you can [manage settings for groups](settings-intune-education.md#manage-settings-for-groups).

## Basic device settings

Intune for Education includes the following basic settings:
- **Camera**: Specify whether the device camera is available.
- **Removable Storage**: Specify whether users can attach removable storage such as USB drives and external hard drives.
- **Date and time**: Specify whether users can change device date and time settings.
- **Device name**: Specify whether users can change the device name.
- **Language settings**: Specify whether users can change device language.
- **Unenroll devices**: Allow users to manually unenroll devices from management.
- **Send diagnostic data**: Collect and send anonymous usage data to Microsoft to help improve Windows.
- Add provisioning packages: Specify whether users can add new provisioning packages containing device configuration settings.
- **Remove provisioning packages**: Specify whether users can remove provisioning packages containing device configuration settings.
- **Location services**: Specify whether apps can use location services to access the device’s location.
- **Internet sharing**: Lets other users connect to the Internet using the device’s Internet connection.
- **Cortana**: Cortana is a digital assistant built into Windows 10 that can answer questions and perform tasks.
- **Device region settings**: Specify whether users can change language and locale settings (ex. English-US)
- **Change power and sleep settings**: Specify whether users can change power and sleep settings on the device.

## Internet browser settings
Intune for Education includes the following internet browser settings:
- **Pop-ups**: Specify whether websites can open a new window.
- **Do-Not-Track headers**: Web browsers can ask that websites not track user data.
- **Cookies and website data**: Cookies can store website settings or track user’s browsing behavior.
- **Autofill form data**:  Autofill remembers data users entered in a field and automatically re-enters it.
- **Password manager**: Web browsers offer to save users’ passwords for sites they visit.
- **Developer tools**: Web browser tools help web developers test and interact with sites.
- **Browser extensions**: Extensions let users customize Edge with added functionality from Microsoft and other sources.
- **InPrivate browsing**: InPrivate browsing won’t save data like browsing history and cookies when you close the web browser.​
- **Access to about:flags page**: The about:flags page contains experimental settings and features.
- **SmartScreen override**: Specify whether users can override warnings about websites blocked by the SmartScreen Filter.
- **SmartScreen override for files**: Specify whether users can ignore SmartScreen Filter warnings and download unverified files.
- **Search suggestions**: Specify SafeSearch settings for web pages viewed in the browser.
- **Send intranet traffic to Internet Explorer**: Specify whether internal (intranet) web sites open in Internet Explorer.
- **Javascript**: Specify whether javascript can run in the Edge Browser.
- **Configure Microsoft Edge homepage settings**: These pages will open as homepages for all users in this group.

## Device update settings

Intune for Education includes the following device update settings:
- **Choose how to install updates**
- **Pre-release Features**: Controls whether Microsoft can install pre-release settings and features on devices

## Windows Defender settings
Intune for Education includes the following Windows Defender settings:
- **Users access to Windows Defender settings**: Lets users modify Windows Defender settings on the device.
- **Real-time monitoring**: Require real-time monitoring for malware, spyware, and other threats.
- **Behavior monitoring**: Require scanning for known patterns of suspicious activity.
- **Network Inspection Service (NIS)**: Collect data about malware and send it to the Microsoft Endpoint Protection Center.
- **Scan all downloaded files**: Enable scanning for files that users download.
- **Scan scripts**: Scan the scripts a website runs in Edge and Internet Explorer.
- **Update frequency**: How frequently Windows Defender checks for and downloads anti-malware updates.
- **Scan file and program activity**: Scans for malware when files or programs are opened and alerts you of suspicious activity.
- **Days before quarantined malware is deleted**: Number of days a file is quarantined before removing (0 = immediately delete).
- **Cloud protection**: Enable Cloud Protection Service to collect information about malware.
- **Prompt users for sample submission**: Specify when files are sent to Microsoft for further analysis.
- **Exclude files with these extensions from scans and real-time protection**: Windows Defender won't scan files with added extensions (for example, .jpg)
- **Exclude processes from scans and real-time protection
Files(i.e. .exe, .com) that shouldn’t be scanned for malware**: Windows Defender won't scan processes. Provide a path to the process.
- **Type of system scan to perform**: Select the type of scan and when it runs.
- **Maximum CPU % usage during system scan**: This keeps malware scans from slowing the device too much.
- **Scan archive files**: Require scans of archives such as .zip and .cab files.
- **Scan incoming emails**: Scan email for malware as it arrives.
- **Scan removable drives during full scan**: Scan external hard drives and USB drives.
- **Scan mapped network drives during full scan**: Scan remote folders this device uses to access data.
- **Scan files opened over the network**: Scan remote files before they are opened.

## Networking and connectivity

Intune for Education includes the following networking and connectivity settings:
- **Cellular roaming data**: Specify whether devices use cellular data plans when roaming.
- **Bluetooth**: Specify whether devices can use Bluetooth service.
- **Bluetooth discoverability**: Specify whether devices are discoverable using Bluetooth.
- **Bluetooth advertising**: Specify whether devices receive advertising over Bluetooth.
- **Allow Wi-Fi**: Specify whether devices can use Wi-Fi.
- **Automatically connect to free Wi-Fi hotspots**: Specify whether devices can automatically connect to Wi-Fi hotspots or if users must logon.

## Device sharing
Intune for Education includes the following device sharing settings:
- **Optimize devices for shared use​**: Optimizes settings for shared devices, letting one user sign in at a time as well as configuring settings like power and updates.
- **Userless sign in**: Specify whether users can sign in with a guest account or whether they must use their username and password.

## App settings
Intune for Education includes the following app settings:
- **Windows Store for Business apps**: Specify whether users in this group can install apps from Windows Store for Business.
- **Private Windows Store for Business apps**: Users can only install apps from your private Windows Store for Business.
- **Automatic app updates**: Windows Store for Business apps are automatically updated.
- **App data-sharing between users**: Specify whether a user's app data can be seen by others on the device (for example, a search history).
- **Trusted Windows Store for Business apps**: Trusted Windows Store for Business apps can be installed.
- **External apps**: Specify whether devices can install apps that aren't downloaded from the Windows Store for Business.

## Sign in settings
Intune for Education includes the following sign-in settings:

- **Sign-in using Microsoft account**: Users sign-in to the device using their Microsoft account
- **Sign-in using non-Microsoft account**: Users sign-in to the device using an account other than their Microsoft account

## Email settings

Allows you to specify whether email settings are configured for this group.

## Edition upgrade

Allows you to specify whether devices are upgraded to a particular edition of Windows 10 and assign a **Product key**.
