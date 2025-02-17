---
title: "IMAPIMessageSiteGetStore"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IMAPIMessageSite.GetStore
api_type:
- COM
ms.assetid: d1ca619e-8bdc-417b-aed6-23dd30e6eafa
description: "Last modified: March 09, 2015"
---

# IMAPIMessageSite::GetStore

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Returns the message store that contains the current message, if such a store exists. This method will return NULL in the _ppStore_ parameter for embedded messages, which are stored in another message instead of directly in a message store. 
  
```cpp
HRESULT GetStore(
  LPMDB FAR * ppStore
);
```

## Parameters

 _ppStore_
  
> [out] A pointer to a pointer to the message store.
    
## Return value

S_OK 
  
> The call succeeded and has returned the expected value or values.
    
S_FALSE 
  
> There is no store that contains the message.
    
## Remarks

For a list of interfaces related to form servers, see [MAPI Form Interfaces](mapi-form-interfaces.md).
  
## MFCMAPI reference

For MFCMAPI sample code, see the following table.
  
|**File**|**Function**|**Comment**|
|:-----|:-----|:-----|
|MyMAPIFormViewer.cpp  <br/> |CMyMAPIFormViewer::GetStore  <br/> |MFCMAPI uses the **IMAPIMessageSite::GetStore** method to get the currently cached pointer to the specified store, if it is available. |
   
## See also



[IMAPIMessageSite : IUnknown](imapimessagesiteiunknown.md)


[MFCMAPI as a Code Sample](mfcmapi-as-a-code-sample.md)
  
[MAPI Form Interfaces](mapi-form-interfaces.md)

