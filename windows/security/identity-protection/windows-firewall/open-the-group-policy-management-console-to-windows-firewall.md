---
title: Open the Group Policy Management Console to Windows Defender Firewall with Advanced Security (Windows 10)
description: Open the Group Policy Management Console to Windows Defender Firewall with Advanced Security
ms.assetid: 5090b2c8-e038-4905-b238-19ecf8227760
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
author: brianlic-msft
ms.date: 08/17/2017
---

# Open the Group Policy Management Console to Windows Defender Firewall with Advanced Security

**Applies to**
-   Windows 10
-   Windows Server 2016

To open a GPO to Windows Defender Firewall:

1.  Open the Group Policy Management console.

2.  In the navigation pane, expand **Forest:** *YourForestName*, expand **Domains**, expand *YourDomainName*, expand **Group Policy Objects**, right-click the GPO you want to modify, and then click **Edit**.

3.  In the navigation pane of the Group Policy Object Editor, navigate to **Computer Configuration** > **Administrative Templates** > **Network** > **Network Connections** > **Windows Defender Firewall**.