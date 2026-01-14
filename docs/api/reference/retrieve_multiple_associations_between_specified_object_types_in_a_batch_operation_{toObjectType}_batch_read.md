# Retrieve multiple associations between specified object types in a batch operation.

## Endpoint
https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/read

## Description
# Retrieve multiple associations between specified object types in a batch operation.

Source: unknown source

---

Retrieve multiple associations between specified object types in a batch operation. - HubSpot docsBatchRetrieve multiple associations between specified object types in a batch operation.closeRetrieve multiple associations between specified object types in a batch operation.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "37295" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "from": { "id": "53628" }, "to": [ { "id": "12726", "type": "contact_to_company" }, { "id": "61352", "type": "contact_to_company" } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchRetrieve multiple associations between specified object types in a batch operation.This endpoint allows you to retrieve multiple associations between specified ‘from’ and ‘to’ object types in a single batch request.POST/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/readRetrieve multiple associations between specified object types in a batch operation.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "37295" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "from": { "id": "53628" }, "to": [ { "id": "12726", "type": "contact_to_company" }, { "id": "61352", "type": "contact_to_company" } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
