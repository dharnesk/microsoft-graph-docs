---
title: "WhoPlusFacet resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# WhoPlusFacet resource type

Namespace: microsoft.graph.linkedIn

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|buckets|[WhoPlusFacetBucket](../resources/linkedin-whoplusfacetbucket.md) collection|**TODO: Add Description**|
|facetField|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.linkedIn.WhoPlusFacet"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.linkedIn.WhoPlusFacet",
  "facetField": "String",
  "buckets": [
    {
      "@odata.type": "microsoft.graph.linkedIn.WhoPlusFacetBucket"
    }
  ]
}
```
