# List DirectoryRole

Retrieve a list of directoryrole objects.
### Prerequisites
The following **scopes** are required to execute this API: ### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /directoryRoles
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$orderby|string|Comma-separated list of properties that are used to sort the order of items in the response collection.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [DirectoryRole](../resources/directoryrole.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "directoryroles"
} -->
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 337
{
  "values": [
    {
      "description": "description-value",
      "displayName": "displayName-value",
      "isSystem": true,
      "roleDisabled": true,
      "roleTemplateId": "roleTemplateId-value",
      "objectType": "objectType-value",
      "objectId": "objectId-value",
      "deletionTimestamp": "datetime-value"
    }
  ]
}
```

<!-- uuid: 5236eb9c-fc63-43e2-ad09-056426c38c5d
2015-10-15 03:41:18 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "List DirectoryRole",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->If successful, this method returns a `200 OK` response code and collection of [DirectoryRole](../resources/directoryrole.md) objects in the response body.