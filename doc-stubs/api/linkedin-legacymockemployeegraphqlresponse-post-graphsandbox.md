---
title: "Create LegacyMockEmployeeGraphQLResponse"
description: "Create a new LegacyMockEmployeeGraphQLResponse object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create LegacyMockEmployeeGraphQLResponse
Namespace: microsoft.graph.linkedIn

Create a new [LegacyMockEmployeeGraphQLResponse](../resources/linkedin-legacymockemployeegraphqlresponse.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /graphSandbox
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [LegacyMockEmployeeGraphQLResponse](../resources/linkedin-legacymockemployeegraphqlresponse.md) object.

The following table shows the properties that are required when you create the [LegacyMockEmployeeGraphQLResponse](../resources/linkedin-legacymockemployeegraphqlresponse.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/linkedin-entity.md)|
|data|[EmployeeResponseData](../resources/linkedin-employeeresponsedata.md)|**TODO: Add Description** Inherited from [EmployeeGraphQLResponse](../resources/linkedin-employeegraphqlresponse.md)|
|errors|[ResponseError](../resources/linkedin-responseerror.md) collection|**TODO: Add Description** Inherited from [EmployeeGraphQLResponse](../resources/linkedin-employeegraphqlresponse.md)|
|extensions|[ResponseExtensions](../resources/linkedin-responseextensions.md)|**TODO: Add Description** Inherited from [EmployeeGraphQLResponse](../resources/linkedin-employeegraphqlresponse.md)|



## Response

If successful, this method returns a `201 Created` response code and a [LegacyMockEmployeeGraphQLResponse](../resources/linkedin-legacymockemployeegraphqlresponse.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_legacymockemployeegraphqlresponse_from_graphsandbox"
}
-->
``` http
POST https://graph.microsoft.com/beta/graphSandbox
Content-Type: application/json
Content-length: 360

{
  "@odata.type": "#microsoft.graph.linkedIn.LegacyMockEmployeeGraphQLResponse",
  "data": {
    "@odata.type": "microsoft.graph.linkedIn.EmployeeResponseData"
  },
  "errors": [
    {
      "@odata.type": "microsoft.graph.linkedIn.ResponseError"
    }
  ],
  "extensions": {
    "@odata.type": "microsoft.graph.linkedIn.ResponseExtensions"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.linkedIn.LegacyMockEmployeeGraphQLResponse"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.linkedIn.LegacyMockEmployeeGraphQLResponse",
  "id": "272319bf-19bf-2723-bf19-2327bf192327",
  "data": {
    "@odata.type": "microsoft.graph.linkedIn.EmployeeResponseData"
  },
  "errors": [
    {
      "@odata.type": "microsoft.graph.linkedIn.ResponseError"
    }
  ],
  "extensions": {
    "@odata.type": "microsoft.graph.linkedIn.ResponseExtensions"
  }
}
```
