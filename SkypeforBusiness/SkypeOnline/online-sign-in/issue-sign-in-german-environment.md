---
title: Error when sign in to Skype for Business in a German Office 365 environment
description: Describes a scenario that can occur when some Skype for Business clients try to connect to the German version of Office 365. Provides a workaround.
author: Norman-sun
manager: dcscontentpm
localization_priority: Normal
search.appverid: 
- MET150
audience: ITPro
ms.service: skype-for-business-online
ms.topic: article
ms.author: v-swei
ms.custom: CSSTroubleshoot
appliesto:
- Skype for Business
---

# Error when you sign in to Skype for Business in a German Office 365 environment

## Symptoms

When you try to sign in the first time to Microsoft Skype for Business in the German version of Microsoft Office 365, you receive the following error message:

**Your sign in request is being redirected to the following server:**

**Outlook.de**

**We can't verify if the server should be trusted. Do you want to continue signing in?**

![sign-in window](./media/issue-sign-in-german-environment/sign-in-window.png)

## Cause

This issue occurs because some specific Skype for Business client versions are incompatible with the German version of Office 365.

## Workaround

To work around this issue on your Windows client computer, use the workarounds that are listed in the following Microsoft Knowledge Base article:

[2833618 "Lync cannot verify that the server is trusted for your sign-in address" message during client sign-in](https://support.microsoft.com//help/4012361)

## Status

Information about this issue will be released soon for mobile clients.

## More information

Still need help? Go to [Microsoft Community](https://answers.microsoft.com/).
