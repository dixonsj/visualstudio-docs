---
title: "Executable for Debugging Session Dialog Box | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-debug"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "vs.debug.exefordebug"
dev_langs: 
  - "FSharp"
  - "VB"
  - "CSharp"
  - "C++"
helpviewer_keywords: 
  - "executable files, specifying when debugging"
  - "DLLs, debugging"
  - "debugger, Executable for Debugging Session dialog box"
  - "Executable for Debugging Session dialog box"
ms.assetid: c0ddbe32-b99f-4425-acf1-f48842804f56
caps.latest.revision: 11
author: "mikejo5000"
ms.author: "mikejo"
manager: "ghogen"
---
# Executable for Debugging Session Dialog Box
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Executable for Debugging Session Dialog Box](https://docs.microsoft.com/visualstudio/debugger/executable-for-debugging-session-dialog-box).  
  
This dialog box appears when you try to debug a DLL for which no executable is specified. Visual Studio cannot launch a DLL directly. Instead, it will launch the specified executable. You can debug the DLL when it is called by the executable.  
  
 **Executable file name**  
 Enter the path name to an executable that calls the DLL you are debugging.  
  
 **URL where the project can be accessed (ATL Server only)**  
 If you are debugging an ATL Server DLL, enter the URL where the project can be found.  
  
 Once entered, these settings are stored in the project Property Pages, so you will not need to enter them again for subsequent debugging sessions. If you need to change the settings, you can open the Property Pages and change the values. For more information on specifying a executable for the debugging session, see [Debugging DLLs](../debugger/how-to-debug-native-dlls.md).  
  
## See Also  
 [Debugging in Visual Studio](../debugger/debugging-in-visual-studio.md)



