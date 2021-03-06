---
title: "ICorDebug::Terminate Method"
ms.date: "03/30/2017"
api_name: 
  - "ICorDebug.Terminate"
api_location: 
  - "mscordbi.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "ICorDebug::Terminate"
helpviewer_keywords: 
  - "Terminate method, ICorDebug interface [.NET Framework debugging]"
  - "ICorDebug::Terminate method [.NET Framework debugging]"
ms.assetid: fffe5616-0896-4426-ab5e-21869b514883
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# ICorDebug::Terminate Method
Terminates the `ICorDebug` object.  
  
> [!NOTE]
>  `Terminate` should not be called until an [ICorDebugManagedCallback::ExitProcess](../../../../docs/framework/unmanaged-api/debugging/icordebugmanagedcallback-exitprocess-method.md) callback has been received for all processes being debugged.  
  
## Syntax  
  
```  
HRESULT Terminate ();  
```  
  
## Remarks  
 `Terminate` must be called when the `ICorDebug` object is no longer needed.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]  
  
## See Also  
 [ICorDebug Interface](../../../../docs/framework/unmanaged-api/debugging/icordebug-interface.md)
