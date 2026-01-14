# Read

## Endpoint
https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/read

## Description
# Read

Source: unknown source

---

Read - HubSpot docsBatchReadcloseReadcURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "after": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "from": { "id": "&#x3C;string>" }, "to": [ { "associationTypes": [ { "category": "HUBSPOT_DEFINED", "typeId": 123, "label": "&#x3C;string>" } ], "toObjectId": "&#x3C;string>" } ], "paging": { "next": { "after": "&#x3C;string>", "link": "&#x3C;string>" }, "prev": { "before": "&#x3C;string>", "link": "&#x3C;string>" } } } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchReadBatch read associations for objects to specific object type. The ‘after’ field in a returned paging object can be added alongside the ‘id’ to retrieve the next page of associations from that objectId. The ‘link’ field is deprecated and should be ignored. Note: The ‘paging’ field will only be present if there are more pages and absent otherwise.POST/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/readReadcURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>", "after": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "from": { "id": "&#x3C;string>" }, "to": [ { "associationTypes": [ { "category": "HUBSPOT_DEFINED", "typeId": 123, "label": "&#x3C;string>" } ], "toObjectId": "&#x3C;string>" } ], "paging": { "next": { "after": "&#x3C;string>", "link": "&#x3C;string>" }, "prev": { "before": "&#x3C;string>", "link": "&#x3C;string>" } } } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
