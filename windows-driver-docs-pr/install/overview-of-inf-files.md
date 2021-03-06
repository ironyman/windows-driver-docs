---
title: Overview of INF Files
description: Overview of INF Files
ms.assetid: 94682cba-1f68-416f-af74-99ede81eadc7
keywords:
- INF files WDK device installations
- INF files WDK device installations , creating
- Device setup WDK device installations , INF files
- device installations WDK , INF files
- installing devices WDK , INF files
- Install a driver by using an INF file
ms.date: 04/20/2017
ms.localizationpriority: medium
---

# Overview of INF Files

Windows uses setup information (INF) files to install the following components for a device:

-   One or more drivers that support the device.

-   Device-specific configuration or settings to bring the device online.

An INF file is a text file that contains all the information that [device installation components](https://msdn.microsoft.com/library/windows/hardware/ff541277) used to install a driver. Windows installs drivers using INF files. This information includes the following:

-   Driver name and location
-   Driver version information
-   Registry information

You can use an *INX* file to automatically create an INF file. An INX file is an INF file that contains string variables that represent version information. The Build utility and the [Stampinf](https://msdn.microsoft.com/library/windows/hardware/ff552786) tool replace the string variables in INX files with text strings that represent a specific hardware architecture or framework version. For more information about INX files, see [Using INX Files to Create INF Files](https://msdn.microsoft.com/library/windows/hardware/ff545473).


See [INF File Sections and Directives](inf-file-sections-and-directives.md) for a complete description of INF file format.
