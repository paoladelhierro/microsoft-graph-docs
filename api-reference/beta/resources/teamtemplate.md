---
title: "teamTemplate resource type"
description: "Represents details about a team template."
author: "Charlieforce"
ms.localizationpriority: medium
ms.prod: "Teamwork"
doc_type: resourcePageType
---

# teamTemplate resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents details about a team template. A **teamTemplate** is a logical container for all the definitions and versions of the same team template.

Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List teamTemplates](../api/teamwork-templates-list.md)|[teamTemplate](../resources/teamtemplate.md) collection|Get a list of the [teamTemplate](../resources/teamtemplate.md) objects and their properties.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|The unique identifier for the team template. Inherited from [entity](../resources/entity.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|definitions|[teamTemplateDefinition](../resources/teamtemplatedefinition.md) collection|The collection of team template definitions.|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.teamTemplate",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.teamTemplate",
  "id": "String (identifier)"
}
```
