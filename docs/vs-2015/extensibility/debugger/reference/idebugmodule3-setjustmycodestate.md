---
title: "IDebugModule3::SetJustMyCodeState | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugModule3::SetJustMyCodeState"
helpviewer_keywords: 
  - "IDebugModule3::SetJustMyCodeState"
ms.assetid: 68f8166d-ef64-49ae-ad5e-79604f43bbd4
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugModule3::SetJustMyCodeState
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugModule3::SetJustMyCodeState](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugmodule3-setjustmycodestate).  
  
Marks the module as being user code or not.  
  
## Syntax  
  
```cpp#  
HRESULT SetJustMyCodeState(  
   BOOL fIsUserCode  
);  
```  
  
```csharp  
int SetJustMyCodeState(  
   int fIsUserCode  
);  
```  
  
#### Parameters  
 `fIsUserCode`  
 [in] Nonzero (`TRUE`) if the module should be considered user code, zero (`FALSE`) if it should not.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns error code.  
  
## See Also  
 [IDebugModule3](../../../extensibility/debugger/reference/idebugmodule3.md)

