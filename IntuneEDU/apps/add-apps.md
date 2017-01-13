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

Before you can install apps to your devices with Intune for Education, those apps must be added. Intune for Education supports the following types of applications:
- Web apps - Links to websites
- Windows Store for Business apps - Universal apps distributed from Microsoft
<!-- - Win32 applications (example) -->

## Popular apps

For your convenience, you can install popular educational apps with a single click. Before trying to install any applications be sure to check the list of preset apps available in Express Setup or under the **Manage applications**. The Intune for Education service shows the top-12 educational web apps and top-12 educational Windows Store for Business apps that you haven’t added under **Apps** management. Our goal is to make it easy for you to install your favorite apps to your users.

## Add popular apps
You can deploy web apps as links to in the Start menu of Windows 10 devices using Intune for Education. To deploy an app, you must first add it to Intune for Education in the **Manage apps** section.

Use the following steps to add web apps to Intune for Education:
1. In the [Intune for Education](https://manage.windowsazure.com) console, click **Manage Apps**, click **Add apps**, and then **Quick add popular apps**. A list of **Web apps** and **Windows Store apps** are displayed.
2. Select the apps you want to add.
3. Click **Add apps**

## Add web apps

Use the following steps to add web apps:
1. In the [Intune for Education](https://manage.windowsazure.com) console, click **Apps**, click **Add apps**, and then **+ Web apps**.
2. Specify the following:
- **URL** - The app store URL of the app that you want to deploy
- **App name** - The name of the app displayed in the Start menu on devices
- **Icon** - The icon for the app if you want to replace the default or an icon is not pre-populated
3. Click **Save**.  Your web app is now ready.
4. You can now [install the app on devices](install-apps.md).

You can edit the application at any time by clicking **Edit** which re-opens the web app details.

## Add Windows Store for Business apps
Apps that you own in Windows Store for Business are automatically available in Intune for Education. Any time you make changes to your app ownership, whether  buying new apps or revoking purchases, that change is reflected in Intune for Education.

To add a new Windows Store for Business apps:
1. In the [Intune for Education](https://manage.windowsazure.com) console, click **Apps**.
2. Click the **+ New Windows Store App** to open your Windows Store for Business account. You can search for app you want to add. Once you find it, go ahead and buy the required number of licenses for the app.
3. Intune for Education will be updated to show your purchase.  This might take up to 12 hours.
4. You can now [install the app on devices](install-apps.md).

>[!div class="step-by-step"]

><!-- [&larr; **Add apps**](.\add-apps.md) -->     [**Install apps** &rarr;](.\install-apps.md)
