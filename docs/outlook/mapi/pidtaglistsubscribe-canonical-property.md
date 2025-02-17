---
title: "PidTagListSubscribe Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagListSubscribe
api_type:
- HeaderDef
ms.assetid: 97387a82-8e40-4c76-818c-2229fac12e01
description: "Contains the value of a Multipurpose Internet Mail Extensions (MIME) message's List-Subscribe header field."
---

# PidTagListSubscribe Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the value of a Multipurpose Internet Mail Extensions (MIME) message's List-Subscribe header field.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_LIST_SUBSCRIBE, PR_LIST_SUBSCRIBE_A, PR_LIST_SUBSCRIBE_W  <br/> |
|Identifier:  <br/> |0x1044  <br/> |
|Data type:  <br/> |PT_STRING8, PT_UNICODE  <br/> |
|Area:  <br/> |Miscellaneous  <br/> |
   
## Remarks

To generate a List-Subscribe header field, clients must set the value of these properties to the desired value. MIME writers must copy the value of these properties to the List-Subscribe header field.
  
To set the value of server-related properties like these, MIME clients must write the header fields as specified in the following table.
  
|**Property**|**Preferred header field name**|**Alternate header field name**|
|:-----|:-----|:-----|
|**PidTagListSubscribe** <br/> |List-Subscribe  <br/> |X-List-Subscribe  <br/> |
   
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

