---
# required metadata

title: Add apps  | Intune for Education
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
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: tanmayb
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# Add apps in Intune for Education

Before you start deploying apps with Intune for Education, take some time to familiarize yourself with how apps are deployed and managed. This will help you understand which apps you can deploy to which platform and the required prerequisites. Intune for Education supports the following types of applications:
- Web apps - Links to websites (example)
- Windows Store for Business apps - Universal apps distributed from Microsoft (example)
- Win32 applications (example)

## Add popular apps

Use the following steps to add web apps to Intune for Education:
1. In the [Intune for Education] console, click **Manage Apps**, click **Add apps**, and then **Quick add popular apps**. A list of **Web apps**, **Windows Store apps** are displayed.
2. Select the apps you want to add.
3. Click **Add apps**

## Add web apps

Use the following steps to add web apps to Intune for Education:
1. In the [Intune for Education] console, click **Apps**, click **Add apps**, and then **Web apps**.
2. Specify the URL of one of the following:
- The app store URL of the app that you want to deploy. For example, if you want to deploy the Bing Translator, specify https://www.microsoft.com/store/apps/9wzdncrfj3pg.
To find the URL of the app, use a search engine to find the store page that contains the app. For example, to find the Translator app, you can search for `Windows Store for Business apps translator`.
- A website. Intune will deploy a shortcut icon to the site on the device (known as a web clip).
- An app on the web. Intune will deploy a shortcut icon to the app on the device.

3. Click **Add apps**


<!-- ## Cloud storage space

All apps that you create by using the software installer installation type (for example, a line-of-business app) are packaged and uploaded to Microsoft Intune cloud storage. A trial subscription of Intune includes 2 gigabytes (GB) of cloud-based storage that is used to store managed apps and updates. Your full subscription includes 20 GB of storage space.+  

You can see how much space you are using in the Storage Use node of the Admin workspace.

Requirements for cloud storage space are as follows:
- All app installation files must be in the same folder
- The maximum file size for any file that you upload is 2 GB -->


<!-- ## Support for Universal Windows Platform (UWP) apps

Windows 10 PCs do not require a sideloading key to install line-of-business apps. However, the registry key `HKEY_LOCAL_MACHINE\Software\Policies\Microsoft\Windows\Appx\AllowAllTrustedApps` must have a value of to 1 to enable sideloading.

If this registry key is not configured, Intune will automatically set this value to 1 the first time you deploy an app to the device. If this value is set to 0, Intune cannot automatically change the value, and the deployment of line-of-business apps will fail.

Universal Windows Platform line-of-business apps must be signed with a code-signing certificate that is trusted on each device to which the app is deployed. You can use a certificate from an in-house public key infrastructure (PKI), or a certificate from a third-party public root certificate installed on the device.

On Windows 10 Mobile devices, you can use a non-Symantec code-signing certificate to sign universal .appx apps. For .xap apps, and also .appx packages built for Windows Phone 8.1 that you want to install on Windows 10 Mobile devices, you must use a Symantec code-signing certificate. -->


>[!div class="step-by-step"]

><!-- [&larr; **Add apps**](.\add-apps.md) -->     [**Add apps** &rarr;](.\add-apps.md)
