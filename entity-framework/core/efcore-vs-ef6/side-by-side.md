---
title: EF6.x and EF Core in the Same Application
author: rowanmiller
ms.author: rowmil
manager: rowanmiller
ms.date: 10/27/2016
ms.topic: article
ms.assetid: 8a715e14-dff3-47ea-b48f-b8280977ddfb
ms.prod: entity-framework
uid: core/efcore-vs-ef6/side-by-side
---
# EF6.x and EF Core in the Same Application

> [!WARNING]
> This documentation is for EF Core. For EF6.x and earlier release see [http://msdn.com/data/ef](http://msdn.com/data/ef).

It is possible to use EF Core and EF6.x in the same application. EF Core and EF6.x have the same type names that differ only by namespace, so this may complicate code that attempts to use both EF Core and EF6.x in the same code file.

If you are porting an existing application that has multiple EF models, then you can selectively port some of them to EF Core, and continue using EF6.x for the others.
