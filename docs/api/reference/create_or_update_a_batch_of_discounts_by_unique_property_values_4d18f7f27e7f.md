# Create or update a batch of discounts by unique property values

## Endpoint
https://api.hubapi.com/crm/v3/objects/discounts/batch/upsert

## Description
# Create or update a batch of discounts by unique property values

Source: unknown source

---

Create or update a batch of discounts by unique property values - HubSpot docsBatchCreate or update a batch of discounts by unique property valuescloseCreate or update a batch of discounts by unique property valuescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/discounts/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {}, "url": "&#x3C;string>" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }BatchCreate or update a batch of discounts by unique property valuesCreate or update records identified by a unique property value as specified by the idProperty query param. idProperty query param refers to a property whose values are unique for the object.POST/crm/v3/objects/discounts/batch/upsertCreate or update a batch of discounts by unique property valuescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/discounts/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {}, "url": "&#x3C;string>" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
