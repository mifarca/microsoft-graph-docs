---
title: "personAnniversary resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# personAnniversary resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [itemFacet](../resources/itemfacet.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List anniversaries](../api/profile-list-anniversaries.md)|[personAnniversary](../resources/personanniversary.md) collection|Get the personAnniversaries from the anniversaries navigation property.|
|[Create anniversaries](../api/profile-post-anniversaries.md)|[personAnniversary](../resources/personanniversary.md)|Create a new anniversaries object.|
|[Update anniversaries](../api/profile-update-anniversaries.md)|[personAnniversary](../resources/personanniversary.md)|Update the properties of an anniversaries object.|
|[Get anniversaries](../api/profile-get-personanniversary.md)|[personAnniversary](../resources/personanniversary.md)|Read the properties and relationships of a [personAnniversary](../resources/personanniversary.md) object.|
|[Delete anniversaries](../api/profile-delete-anniversaries.md)|None|Delete a [personAnniversary](../resources/personanniversary.md) object.|
|[List personAnniversaries](../api/personanniversary-list.md)|[personAnniversary](../resources/personanniversary.md) collection|Get a list of the [personAnniversary](../resources/personanniversary.md) objects and their properties.|
|[Create personAnniversary](../api/personanniversary-create.md)|[personAnniversary](../resources/personanniversary.md)|Create a new [personAnniversary](../resources/personanniversary.md) object.|
|[Get personAnniversary](../api/personanniversary-get.md)|[personAnniversary](../resources/personanniversary.md)|Read the properties and relationships of a [personAnniversary](../resources/personanniversary.md) object.|
|[Update personAnniversary](../api/personanniversary-update.md)|[personAnniversary](../resources/personanniversary.md)|Update the properties of a [personAnniversary](../resources/personanniversary.md) object.|
|[Delete personAnniversary](../api/personanniversary-delete.md)|None|Deletes a [personAnniversary](../resources/personanniversary.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|allowedAudiences|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md). Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|date|Date|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|inference|[inferenceData](../resources/inferencedata.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|source|[personDataSource](../resources/persondatasource.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|type|anniversaryType|**TODO: Add Description**. Possible values are: `birthday`, `wedding`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.personAnniversary",
  "baseType": "microsoft.graph.itemFacet",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.personAnniversary",
  "id": "String (identifier)",
  "allowedAudiences": "String",
  "inference": {
    "@odata.type": "microsoft.graph.inferenceData"
  },
  "createdDateTime": "String (timestamp)",
  "createdBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "lastModifiedDateTime": "String (timestamp)",
  "lastModifiedBy": {
    "@odata.type": "microsoft.graph.identitySet"
  },
  "source": {
    "@odata.type": "microsoft.graph.personDataSource"
  },
  "type": "String",
  "date": "Date"
}
```
