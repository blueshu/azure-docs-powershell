---
title: Overview of Azure PowerShell
description: An overview of the Azure PowerShell Az module, with information on how to install and get started.
author: sptramer
ms.author: sttramer
manager: carmonm
ms.devlang: powershell
ms.topic: conceptual
ms.manager: carmonm
ms.date: 10/29/2018
---
# Overview of Azure PowerShell

Azure PowerShell provides a set of cmdlets that use the [Azure Resource
Manager](/azure/azure-resource-manager/resource-group-overview) model for managing your Azure
resources. Azure PowerShell uses .NET Standard, making it available for Windows, macOS, and Linux.
Azure PowerShell is also available from Azure Cloud Shell.

Use [Azure Cloud Shell](/azure/cloud-shell/overview) to run Azure PowerShell in your browser, or
[install locally](install-az-ps.md). Check out the [Get Started](get-started-azureps.md)
article to learn the Azure PowerShell basics and get started with Azure.

For information about the latest Azure PowerShell release, see the [release notes](release-notes-azureps.md).

## About the new Az module

This documentation describes the new Az module for Azure PowerShell. This new module is written from the
ground up in .NET Standard. Using .NET Standard allows Azure PowerShell to run under PowerShell 5.x on Windows
or PowerShell 6 on any platform. The Az module is now the intended way to interact with Azure through PowerShell.
AzureRM will continue to get bug fixes, but no longer receive new features.

Learn the full details about the new module, including how commands have been renamed and the maintenance
plans for AzureRM, in the [Introducing the Azure PowerShell Az module](new-azureps-module-az.md). If you
want to get started with using the new module right away, see [Migrate from AzureRM to Az](migrate-from-azurerm-to-az.md).

The [AzureRM documentation](/powershell/azure/azurerm) is also available.

> [!IMPORTANT]
>
> While the Azure documentation is being updated to reflect the new module cmdlet names, articles may still use
> the AzureRM commands. After installing the Az module, it's recommended that you enable the AzureRM cmdlet aliases
> with `Enable-AzureRmAlias`. See the [Migrate from AzureRM to Az](migrate-from-azurerm-to-az.md) article for more
> details.

## Common scenarios

The following samples can help you learn how to perform common scenarios with Azure PowerShell:

* [Linux Virtual Machines](/azure/virtual-machines/virtual-machines-linux-powershell-samples?toc=/powershell/azure/toc.json)
* [Windows Virtual Machines](/azure/virtual-machines/virtual-machines-windows-powershell-samples?toc=/powershell/azure/toc.json)
* [Web Apps](/azure/app-service-web/app-service-powershell-samples?toc=/powershell/azure/toc.json)
* [SQL Databases](/azure/sql-database/sql-database-powershell-samples?toc=/powershell/azure/toc.json)

## Learn PowerShell basics

If you're unfamiliar with PowerShell, an introduction may be helpful.

* [Installing PowerShell](/powershell/scripting/setup/installing-windows-powershell)
* [Scripting with PowerShell](/powershell/scripting/powershell-scripting)

You can also watch this video:
[PowerShell Basics: (Part 1) Getting Started with PowerShell](https://channel9.msdn.com/Blogs/Taste-of-Premier/PowerShellBasicsPart1).

Or attend the Microsoft Virtual Academy's [Getting Started with PowerShell Jumpstart](https://mva.microsoft.com/liveevents/powershell-jumpstart).

## Build your skills with Microsoft Learn

- [Automate Azure tasks using scripts with PowerShell](/learn/modules/automate-azure-tasks-with-powershell/)
- [More interactive learning...](/learn/browse/?term=powershell)

## Other Azure PowerShell modules

* [Azure Active Directory](/powershell/azure/active-directory/)
* [Azure Information Protection](/powershell/azure/aip/)
* [Azure Service Fabric](/powershell/azure/service-fabric/)
* [Azure ElasticDB](/powershell/azure/elasticdbjobs/)
