# Create Default Associations

## Endpoint
https://api.hubapi.com/crm/associations/2025-09/{fromObjectType}/{toObjectType}/batch/associate/default

## Description
# Create Default Associations

Source: unknown source

---

Create Default Associations - HubSpot docsBatch Create Default Associationsclose Create Default AssociationscURLcurl --request POST \ --url https://api.hubapi.com/crm/associations/2025-09/{fromObjectType}/{toObjectType}/batch/associate/default \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" } } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "associationSpec": { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 }, "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" } } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }Batch Create Default AssociationsCreate the default (most generic) association type between two object typesPOST/crm/associations/2025-09/{fromObjectType}/{toObjectType}/batch/associate/default Create Default AssociationscURLcurl --request POST \ --url https://api.hubapi.com/crm/associations/2025-09/{fromObjectType}/{toObjectType}/batch/associate/default \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" } } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "associationSpec": { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 }, "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" } } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
