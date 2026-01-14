# Create or update a batch of contacts

## Endpoint
https://api.hubapi.com/crm/v3/objects/contacts/batch/upsert

## Description
# Create or update a batch of contacts

Source: unknown source

---

Create or update a batch of contacts - HubSpot docsBatchCreate or update a batch of contactscloseCreate or update a batch of contactscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/contacts/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {}, "url": "&#x3C;string>" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }BatchCreate or update a batch of contactsUpsert a batch of contacts. The inputs array can contain a properties object to define property values for each record.POST/crm/v3/objects/contacts/batch/upsertCreate or update a batch of contactscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/contacts/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "properties": {}, "idProperty": "&#x3C;string>", "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": true, "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "new": true, "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archivedAt": "2023-11-07T05:31:56Z", "objectWriteTraceId": "&#x3C;string>", "propertiesWithHistory": {}, "url": "&#x3C;string>" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 10, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
