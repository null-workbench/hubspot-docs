# Delete Specific Labels

## Endpoint
https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/labels/archive

## Description
# Delete Specific Labels

Source: unknown source

---

Delete Specific Labels - HubSpot docsBatchDelete Specific LabelscloseDelete Specific LabelscURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/labels/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" }, "types": [ { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 } ] } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ "&#x3C;unknown>" ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchDelete Specific LabelsBatch delete specific association labels for objects. Deleting an unlabeled association will also delete all labeled associations between those two objectsPOST/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/labels/archiveDelete Specific LabelscURLcurl --request POST \ --url https://api.hubapi.com/crm/v4/associations/{fromObjectType}/{toObjectType}/batch/labels/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "&#x3C;string>" }, "to": { "id": "&#x3C;string>" }, "types": [ { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 } ] } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ "&#x3C;unknown>" ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
