# Create or update a batch of subscriptions by unique property values

## Endpoint
https://api.hubapi.com/crm/v3/objects/subscriptions/batch/upsert

## Description
# Create or update a batch of subscriptions by unique property values

Source: unknown source

---

Create or update a batch of subscriptions by unique property values - HubSpot docsBatchCreate or update a batch of subscriptions by unique property valuesclosePerform a batch upsert operation on subscription objects.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {} } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }BatchCreate or update a batch of subscriptions by unique property valuesThis endpoint allows you to perform a batch upsert operation on subscription objects, which will either update existing records or create new ones if they do not already exist. The operation returns the status, timestamps, and a list of successfully processed objects.POST/crm/v3/objects/subscriptions/batch/upsertPerform a batch upsert operation on subscription objects.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {} } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
