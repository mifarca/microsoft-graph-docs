---
title: "chatMessageReaction resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# chatMessageReaction resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|reactionType|String|**TODO: Add Description**|
|user|[identitySet](../resources/identityset.md)|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.chatMessageReaction"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.chatMessageReaction",
  "reactionType": "String",
  "createdDateTime": "String (timestamp)",
  "user": {
    "@odata.type": "microsoft.graph.identitySet"
  }
}
```
