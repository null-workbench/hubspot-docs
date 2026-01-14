# Create a batch of communications

## Endpoint
https://api.hubapi.com/crm/v3/objects/communications/batch/create

## Description
# Create a batch of communications

Source: unknown source

---

Create a batch of communications - HubSpot docsBatchCreate a batch of communicationscloseCreate a batch of communicationscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/communications/batch/create \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "associations": [ { "to": { "id": "&#x3C;string>" }, "types": [ { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 } ] } ], "properties": {}, "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchCreate a batch of communicationsCreate a batch of messages. The inputs array can contain a properties object to define property values for each message, along with an associations array to define associations with other CRM records.POST/crm/v3/objects/communications/batch/createCreate a batch of communicationscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/communications/batch/create \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "associations": [ { "to": { "id": "&#x3C;string>" }, "types": [ { "associationCategory": "HUBSPOT_DEFINED", "associationTypeId": 123 } ] } ], "properties": {}, "objectWriteTraceId": "&#x3C;string>" } ] } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
