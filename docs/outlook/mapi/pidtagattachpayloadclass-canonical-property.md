---
title: "PidTagAttachPayloadClass Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagAttachPayloadClass
api_type:
- HeaderDef
ms.assetid: bc4de217-8241-45e7-9e97-8f0c1b16691a
description: "Contains the value of a MIME X-Payload-Class header field. MIME readers must copy this header field value to the value of the corresponding property."
---

# PidTagAttachPayloadClass Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the value of a MIME X-Payload-Class header field.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_ATTACH_PAYLOAD_CLASS, PR_ATTACH_PAYLOAD_CLASS_A, PR_ATTACH_PAYLOAD_CLASS_W  <br/> |
|Identifier:  <br/> |0x371A  <br/> |
|Data type:  <br/> |PT_STRING8, PT_UNICODE  <br/> |
|Area:  <br/> |Outlook application  <br/> |
   
## Remarks

To set the value of these properties, MIME clients should write an X-Payload-Class header field to a MIME entity that will be analyzed as an attachment.
  
MIME readers must copy this header field value to the value of the corresponding property. MIME readers should ignore this header field when it appears on a MIME entity that is analyzed as a message or message body, rather than as an attachment.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXCMAIL]](https://msdn.microsoft.com/library/b60d48db-183f-4bf5-a908-f584e62cb2d4%28Office.15%29.aspx)
  
> Converts from Internet standard email conventions to message objects.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

