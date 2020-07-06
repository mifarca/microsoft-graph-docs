---
title: "personInterest resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# personInterest resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [itemFacet](../resources/itemfacet.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List interests](../api/profile-list-interests.md)|[personInterest](../resources/personinterest.md) collection|Get the personInterests from the interests navigation property.|
|[Create interests](../api/profile-post-interests.md)|[personInterest](../resources/personinterest.md)|Create a new interests object.|
|[Update interests](../api/profile-update-interests.md)|[personInterest](../resources/personinterest.md)|Update the properties of an interests object.|
|[Get interests](../api/profile-get-personinterest.md)|[personInterest](../resources/personinterest.md)|Read the properties and relationships of a [personInterest](../resources/personinterest.md) object.|
|[Delete interests](../api/profile-delete-interests.md)|None|Delete a [personInterest](../resources/personinterest.md) object.|
|[List personInterests](../api/personinterest-list.md)|[personInterest](../resources/personinterest.md) collection|Get a list of the [personInterest](../resources/personinterest.md) objects and their properties.|
|[Create personInterest](../api/personinterest-create.md)|[personInterest](../resources/personinterest.md)|Create a new [personInterest](../resources/personinterest.md) object.|
|[Get personInterest](../api/personinterest-get.md)|[personInterest](../resources/personinterest.md)|Read the properties and relationships of a [personInterest](../resources/personinterest.md) object.|
|[Update personInterest](../api/personinterest-update.md)|[personInterest](../resources/personinterest.md)|Update the properties of a [personInterest](../resources/personinterest.md) object.|
|[Delete personInterest](../api/personinterest-delete.md)|None|Deletes a [personInterest](../resources/personinterest.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|allowedAudiences|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md). Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|categories|String collection|**TODO: Add Description**|
|collaborationTags|String collection|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|inference|[inferenceData](../resources/inferencedata.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|source|[personDataSource](../resources/persondatasource.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|webUrl|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.personInterest",
  "baseType": "microsoft.graph.itemFacet",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.personInterest",
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
  "categories": [
    "String"
  ],
  "description": "String",
  "displayName": "String",
  "webUrl": "String",
  "collaborationTags": [
    "String"
  ]
}
```
