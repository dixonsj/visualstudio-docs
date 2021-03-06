---
title: "IDebugCanStopEvent2::GetReason | Microsoft Docs"
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
  - "IDebugCanStopEvent2::GetReason"
helpviewer_keywords: 
  - "IDebugCanStopEvent2::GetReason"
ms.assetid: f5de31ca-7b8d-4029-9cf9-ba860ac66af6
caps.latest.revision: 12
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugCanStopEvent2::GetReason
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugCanStopEvent2::GetReason](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugcanstopevent2-getreason).  
  
Gets the reason why the debug engine (DE) wants to stop.  
  
## Syntax  
  
```cpp#  
HRESULT GetReason(   
   CANSTOP_REASON* pcr  
);  
```  
  
```csharp  
int GetReason(   
   out enum_CANSTOP_REASON pcr  
);  
```  
  
#### Parameters  
 `pcr`  
 [out] Returns a value from the [CANSTOP_REASON](../../../extensibility/debugger/reference/canstop-reason.md) enumeration that describes the reason for this event.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## Remarks  
 This method is typically called before the [CanStop](../../../extensibility/debugger/reference/idebugcanstopevent2-canstop.md) method so the caller can determine whether to pass non-zero (`TRUE`) to the `IDebugCanStopEvent2::CanStop` method.  
  
 The reason for stopping can be either `CANSTOP_ENTRYPOINT`, which means the DE has reached an entry point, or `CANSTOP_STEPIN`, which means the DE has stepped into a function.  
  
## See Also  
 [IDebugCanStopEvent2](../../../extensibility/debugger/reference/idebugcanstopevent2.md)   
 [CANSTOP_REASON](../../../extensibility/debugger/reference/canstop-reason.md)   
 [CanStop](../../../extensibility/debugger/reference/idebugcanstopevent2-canstop.md)

