---
title: "IDebugStackFrame2::GetThread | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugStackFrame2::GetThread"
helpviewer_keywords: 
  - "IDebugStackFrame2::GetThread"
ms.assetid: cbeef85b-3dd7-4f97-adc2-c4d197d979fc
caps.latest.revision: 10
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
---
# IDebugStackFrame2::GetThread
Gets the thread associated with a stack frame.  
  
## Syntax  
  
```cpp  
HRESULT GetThread (   
   IDebugThread2** ppThread  
);  
```  
  
```csharp  
int GetThread (   
   out IDebugThread2 ppThread  
);  
```  
  
#### Parameters  
 `ppThread`  
 [out] Returns an [IDebugThread2](../../../extensibility/debugger/reference/idebugthread2.md) object that represents the thread.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugStackFrame2](../../../extensibility/debugger/reference/idebugstackframe2.md)   
 [IDebugThread2](../../../extensibility/debugger/reference/idebugthread2.md)