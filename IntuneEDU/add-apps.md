---
# required metadata

title: Add apps
titleSuffix: Intune for Education
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
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
 - IntuneEDU

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer:
#ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

# How do I add apps to Intune for Education?

Before you can install apps to your school's devices with Intune for Education, those apps must be added to your Intune for Education account.

Intune for Education supports the following types of apps:
- Web apps, such as [Microsoft Word Online](https://office.live.com/start/Word.aspx)
- Microsoft Store for Business apps, which are any [Universal apps distributed through the Store](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- Desktop (Win32) apps, such as [standalone Microsoft Office](https://products.office.com/products)

After you add apps, you can [install the apps](install-apps.md) on groups of devices.

## Add web apps

A _web app_ is an app that is accessed by users exclusively in a browser. They are easy to assign because all you have to send to users are links to websites, rather than sending any install files to their devices.

You can assign web apps as links in the Start menu of Windows 10 devices using Intune for Education. To assign an app, you must first add it to Intune for Education in the **Manage apps** section.

  ![The add a new web app page, which prompts users for the information described in the procedure below.](./media/apps-001-add-webapp.png)

1. In the [Intune for Education](https://intuneeducation.portal.azure.com) console, choose **Apps**.


2. Under **Web apps**, select **+ New app**, then enter the following details:
 - **URL** - The URL of the app that you want to assign
 - **App name** - The name of the app displayed in the Start menu on devices
 - **Icon** - Upload a PNG or JPG from your computer to use as an icon for the app

3. Choose **Save**. Your web app is now ready.

4. You can now [install the app on devices](install-apps.md).

You can edit the app at any time by choosing **Edit**, which re-opens its details page.

## Add desktop apps

You can install desktop apps through the same interface on the **Apps** page. This process is similar to installing a web app, but involves the install file that web apps don't require.

![The new desktop app screen.](./media/apps-005-add-desktop-app.png)

1. In the [Intune for Education](https://intuneeducation.portal.azure.com) console, choose **Apps**.

2. Under **Desktop apps**, select **+ New app**. This will open the **New desktop app** screen, then enter the following details:
 - **App file** - Upload an MSI installer for the app
 - **App name** - The name of the app to appear on devices
 - **Description** - A description of the app to help you with quickly identifying which app it is
 - **Publisher** - The name of the app publisher, to help you with quickly identifying who developed the app
 - **Icon** - Upload a PNG or JPG from your computer to use as an icon for the app

3. Choose **Save and upload file**.

  ![The add new desktop app screen, with all fields filled out for sample app, evernote.](./media/apps-006-filled-out-desktop-app.png)

4. The app will then upload to Intune for Education. Once the upload is complete, you can [install the app on devices](install-apps.md).

> [!NOTE]
> Sometimes you may run into an error that says "The app doesn't have an install file" or "No app installation file was added". This means that the file didn't upload properly. Try to save and upload the file again to fix this error.

## Add popular apps

You can install popular educational apps with a single click. Our goal is to make it easy for you to find and install your favorite apps for your users. We recommend these apps because they are frequently useful to educators. You can find these apps in Express Configuration, or under the **Manage apps** tile.

  ![A selection of popular apps during the add apps process in Express Configuration.](./media/apps-007-popular-apps.png)

The Intune for Education portal shows the top 12 educational web apps and top 12 educational Microsoft Store for Business apps that you haven’t added under **Apps** management.

> [!TIP]
> If you haven't set up your Microsoft Store for Business account to add apps to Intune for Education, you can find out how to do that [here](acquire-store-apps.md).

1. In the [Intune for Education](https://intuneeducation.portal.azure.com) console, choose  **Manage Apps** > **Add apps** > **Quick add popular apps**. A list of **Web apps** and **Windows Store apps** is displayed.

  ![The quick add popular apps screen.](./media/apps-008-add-popular-apps.png)

2. Select the apps you want to add, then choose **Add apps**.

  ![Selecting multiple popular apps to add to the portal.](./media/apps-009-select-multiple-popular-apps.png)

3. Your apps will add in the background and appear in the left hand sidebar when ready.

  ![Your apps are being added screen.](./media/apps-010-your-popular-apps-are-being-added.png)

><!-- [&larr; **Add apps**](.\add-apps.md)      [**Install apps** &rarr;](.\install-apps.md) -->
