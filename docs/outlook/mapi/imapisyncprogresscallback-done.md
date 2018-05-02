---
title: "IMAPISyncProgressCallbackDone"
 
 
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IMAPISyncProgressCallback.Done
api_type:
- COM
ms.assetid: aaa8eb56-f22f-4c5a-a224-807ff001e0ca
description: "Last modified: July 23, 2011"
---

# IMAPISyncProgressCallback::Done

 **Last modified:** July 23, 2011 
  
 * **Applies to:** Outlook * 
  
 Informs Microsoft Outlook that synchronization is complete. 
  
```
HRESULT Done(
  HANDLE hThreadDoneEvent, 
  HRESULT hResult
);
```

## Parameters

 **hThreadDoneEvent**
  
> An event that is passed back to allow Microsoft Outlook to close the handle. It can be NULL.
    
 **hResult**
  
> An HRESULT indicating final status of the progress.
    
## Return value

S_OK 
  
> The call succeeded and has returned the expected value or values.
    
## See also

#### Reference

[IMAPISyncProgressCallback : IUnknown](imapisyncprogresscallbackiunknown.md)
