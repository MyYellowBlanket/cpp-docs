---
title: "Visual C++ Project Types | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology:  
  - "cpp-ide"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "programs [C++], projects"
  - "project templates [Visual Studio], C++"
  - "TODO comments [C++]"
  - "projects [C++], types"
  - "templates [C++], projects"
  - "applications [C++], projects"
  - "Visual C++ projects, types"
ms.assetid: 7337987e-1e7b-4120-9a4b-94f0401f15e7
caps.latest.revision: 20
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# Visual C++ Project Types
You can use a project template to create the basic program structure, menus, toolbars, icons, references, and `#include` statements that are appropriate for the kind of project you want to create. Visual Studio includes several kinds of Visual C++ project templates and provides wizards for many of them so that you can customize your projects as you create them. Immediately after you create a project, you can build it and run the application—it's good practice to build intermittently as you develop your application.  
  
 You don't have to use a template to create a project, but in most cases it's more efficient to do so because it's easier to modify the provided project files and structure than it is to create them from scratch.  
  
> [!NOTE]
>  You can create a C-language project by using C++ project templates. In the generated project, locate files that have a .cpp file name extension and change it to .c. Then, on the **Project Properties** page for the project (not for the solution), expand **Configuration Properties**, **C/C++** and select **Advanced**. Change the **Compile As** setting to **Compile as C Code (/TC)**.  
  
## Project Templates  
 Visual Studio the following Visual C++ project templates.  
  
### Store Apps  
[C#, VB, and C++ project templates for  Store apps](http://go.microsoft.com/fwlink/p/?LinkID=262279)
  
### ATL  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|ATL Project|[Creating an ATL Project](../atl/reference/creating-an-atl-project.md)|  
  
### CLR  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|Class Library|[Class Library Template (C++)](http://msdn.microsoft.com/en-us/0d779bfa-5c5a-4b10-a9d5-a6791764a78f)|  
|CLR Console Application|[How to: Create CLR Console Applications (C++/CLI)](../dotnet/how-to-create-clr-console-applications-cpp-cli.md)|  
|CLR Empty Project|[CLR Empty Project Template (C++)](http://msdn.microsoft.com/en-us/f57c5572-5581-440f-b684-eec646764f08)|  
  
### General  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|Empty Project|[Creating Solutions and Projects](/visualstudio/ide/creating-solutions-and-projects)|  
|Makefile Project|[Creating a Makefile Project](../ide/creating-a-makefile-project.md)|  
  
### MFC  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|MFC ActiveX Control|[Creating an MFC ActiveX Control](../mfc/reference/creating-an-mfc-activex-control.md)|  
|MFC Application|[Creating an MFC Application](../mfc/reference/creating-an-mfc-application.md)|  
|MFC DLL|[Creating an MFC DLL Project](../mfc/reference/creating-an-mfc-dll-project.md)|  
  
### Test  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|Managed Test Project|[Create a unit test project](/visualstudio/test/create-a-unit-test-project)|  
|Native Unit Test Project|[Unit testing native code with Test Explorer](http://msdn.microsoft.com/en-us/8a09d6d8-3613-49d8-9ffe-11375ac4736c)|  
  
### Win32  
  
|Project template|How to create a project|  
|----------------------|-----------------------------|  
|Win32 Console Project|[Creating a Console Application](../windows/creating-a-console-application.md)|  
|Win32 Project|[Walkthrough: Creating Windows Desktop Applications ](../windows/walkthrough-creating-windows-desktop-applications-cpp.md)|  
  
## TODO Comments  
 Many of the files generated by a project template contain TODO comments to help you identify where you can provide your own source code. For more information about how to add code, see [Adding Functionality with Code Wizards](../ide/adding-functionality-with-code-wizards-cpp.md) and [Working with Resource Files](../windows/working-with-resource-files.md).  
  
## See Also  
 [Creating Desktop Projects By Using Application Wizards](../ide/creating-desktop-projects-by-using-application-wizards.md)   
 [Using Projects to Create Applications](http://msdn.microsoft.com/en-us/3339fa90-bac2-4b95-8361-662a2e0e7dfe)   
 [CLR Projects](../ide/files-created-for-clr-projects.md)
