---
title: "FindAppConfigFile Task | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: 
  - "VB"
  - "CSharp"
  - "C++"
  - "jsharp"
helpviewer_keywords: 
  - "FindAppConfigFile task [MSBuild]"
  - "MSBuild, FindAppConfigFile task"
ms.assetid: e292de3e-7482-4426-83ce-d921061808bf
caps.latest.revision: 8
author: mikejo5000
ms.author: mikejo
manager: "ghogen"
---
# FindAppConfigFile Task
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [FindAppConfigFile Task](https://docs.microsoft.com/visualstudio/msbuild/findappconfigfile-task).  
  
  
Finds the app.config file, if any, in the provided lists.  
  
## Parameters  
 The following table describes the parameters of the `FindAppConfigFile` task.  
  
|Parameter|Description|  
|---------------|-----------------|  
|`AppConfigFile`|Optional <xref:Microsoft.Build.Framework.ITaskItem>`[]` output parameter.<br /><br /> Specifies the first matching item found in the list, if any.|  
|`PrimaryList`|Required <xref:Microsoft.Build.Framework.ITaskItem>`[]` parameter.<br /><br /> Specifies the primary list to search through.|  
|`SecondaryList`|Required <xref:Microsoft.Build.Framework.ITaskItem>`[]` parameter.<br /><br /> Specifies the secondary list to search through.|  
|`TargetPath`|Required `String` parameter.<br /><br /> Specifies the value to add as metadata.|  
  
## Remarks  
 In addition to having the parameters that are listed in the table, this task inherits parameters from the <xref:Microsoft.Build.Tasks.TaskExtension> class, which itself inherits from the <xref:Microsoft.Build.Utilities.Task> class. For a list of these additional parameters and their descriptions, see [TaskExtension Base Class](../msbuild/taskextension-base-class.md).  
  
## See Also  
 [Tasks](../msbuild/msbuild-tasks.md)   
 [Task Reference](../msbuild/msbuild-task-reference.md)



