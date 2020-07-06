---
title: "educationalActivity resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# educationalActivity resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [itemFacet](../resources/itemfacet.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List educationalActivities](../api/profile-list-educationalactivities.md)|[educationalActivity](../resources/educationalactivity.md) collection|Get the educationalActivities from the educationalActivities navigation property.|
|[Create educationalActivities](../api/profile-post-educationalactivities.md)|[educationalActivity](../resources/educationalactivity.md)|Create a new educationalActivities object.|
|[Update educationalActivities](../api/profile-update-educationalactivities.md)|[educationalActivity](../resources/educationalactivity.md)|Update the properties of an educationalActivities object.|
|[Get educationalActivities](../api/profile-get-educationalactivity.md)|[educationalActivity](../resources/educationalactivity.md)|Read the properties and relationships of an [educationalActivity](../resources/educationalactivity.md) object.|
|[Delete educationalActivities](../api/profile-delete-educationalactivities.md)|None|Delete an [educationalActivity](../resources/educationalactivity.md) object.|
|[List educationalActivities](../api/educationalactivity-list.md)|[educationalActivity](../resources/educationalactivity.md) collection|Get a list of the [educationalActivity](../resources/educationalactivity.md) objects and their properties.|
|[Create educationalActivity](../api/educationalactivity-create.md)|[educationalActivity](../resources/educationalactivity.md)|Create a new [educationalActivity](../resources/educationalactivity.md) object.|
|[Get educationalActivity](../api/educationalactivity-get.md)|[educationalActivity](../resources/educationalactivity.md)|Read the properties and relationships of an [educationalActivity](../resources/educationalactivity.md) object.|
|[Update educationalActivity](../api/educationalactivity-update.md)|[educationalActivity](../resources/educationalactivity.md)|Update the properties of an [educationalActivity](../resources/educationalactivity.md) object.|
|[Delete educationalActivity](../api/educationalactivity-delete.md)|None|Deletes an [educationalActivity](../resources/educationalactivity.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowedAudiences|allowedAudiences|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md). Possible values are: `me`, `family`, `contacts`, `groupMembers`, `organization`, `federatedOrganizations`, `everyone`, `unknownFutureValue`.|
|completionMonthYear|Date|**TODO: Add Description**|
|createdBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|createdDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|endMonthYear|Date|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|inference|[inferenceData](../resources/inferencedata.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|institution|[institutionData](../resources/institutiondata.md)|**TODO: Add Description**|
|lastModifiedBy|[identitySet](../resources/identityset.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|program|[educationalActivityDetail](../resources/educationalactivitydetail.md)|**TODO: Add Description**|
|source|[personDataSource](../resources/persondatasource.md)|**TODO: Add Description** Inherited from [itemFacet](../resources/itemfacet.md)|
|startMonthYear|Date|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.educationalActivity",
  "baseType": "microsoft.graph.itemFacet",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.educationalActivity",
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
  "completionMonthYear": "Date",
  "endMonthYear": "Date",
  "institution": {
    "@odata.type": "microsoft.graph.institutionData"
  },
  "program": {
    "@odata.type": "microsoft.graph.educationalActivityDetail"
  },
  "startMonthYear": "Date"
}
```
