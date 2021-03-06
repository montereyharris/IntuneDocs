---
# required metadata

title: Send Android logs to Microsoft developers | Microsoft Docs
description:
keywords:
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 01/02/2018
ms.topic: article
ms.prod:
ms.service: microsoft-intune
ms.technology:
ms.assetid: 06767d1c-a012-4288-9921-f9dd2eb4eb8d
searchScope:
 - User help

# optional metadata

ROBOTS:  
#audience:
#ms.devlang:
ms.reviewer: arnab
ms.suite: ems
#ms.tgt_pltfrm:
ms.custom: intune-enduser

---

# Send logs to the Company Portal developers for Android devices

Sometimes the Company Portal app may close unexpectedly. This is an issue that the app developers want to hear about, as it can help us make it work better for you and prevent this kind of thing from happening in the future. This information is kept on your device in a special document called a _diagnostic log_.

If this is happening to you, the Company Portal team needs some information to try and diagnose the root cause. Here’s what we need you to do:

1.	Attempt to make the issue happen again. It’s ok if you can’t, but it might make the next step easier if you can.
2.	Go to __Settings__ > __Privacy__ > __Diagnostics & Usage__ > __Diagnostics & Usage Data__. This is a list of app activities that have happened, ranging from crashes to general usage patterns, and it does not contain any personal information. This list is organized from most recent to oldest. If you were able to reproduce the issue, this should be the first item that appears on the list of app activity on this page. If you were unable to reproduce the issue, scroll down until you find the first item that begins with “Company Portal”, then tap it to open it.
3.	Press and hold, then drag the little blue dots up and down until all of the text in the report has been selected. Tap __Copy__ in the popup menu.
4.	Open your email app, and paste that content into the body of the email. Send that email to
<a href="mailto:wintunedroidfbk@microsoft.com?subject=My Company Portal App Closed Unexpectedly&body=Press and hold, then paste your copied Company Portal app logs here.">wintunedroidfbk@microsoft.com</a>.

Still need help? Contact your company support. For contact information, check the [Company Portal website](https://portal.manage.microsoft.com#HelpDeskDialog).
