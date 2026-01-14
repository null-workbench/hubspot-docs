# Delete

## Endpoint
https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/archive

## Description
# Delete

Source: unknown source

---

Delete - HubSpot docsBatchDeletecloseDeletecURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": [ { "id": "&#x3C;string>" } ] } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ "&#x3C;unknown>" ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchDeleteBatch delete associations for objectsPOST/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/archiveDeletecURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": [ { "id": "&#x3C;string>" } ] } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ "&#x3C;unknown>" ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
