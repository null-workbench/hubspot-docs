# Read a batch of subscriptions by internal ID, or unique property values

## Endpoint
https://api.hubapi.com/crm/v3/objects/subscriptions/batch/read

## Description
# Read a batch of subscriptions by internal ID, or unique property values

Source: unknown source

---

Read a batch of subscriptions by internal ID, or unique property values - HubSpot docsBatchRead a batch of subscriptions by internal ID, or unique property valuescloseRetrieve a batch of subscription objects by IDs.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ], "properties": [ "&#x3C;string>" ], "propertiesWithHistory": [ "&#x3C;string>" ], "idProperty": "&#x3C;string>" } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }BatchRead a batch of subscriptions by internal ID, or unique property valuesRetrieve a batch of CRM subscription objects by their IDs, including specified properties and their histories.POST/crm/v3/objects/subscriptions/batch/readRetrieve a batch of subscription objects by IDs.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ], "properties": [ "&#x3C;string>" ], "propertiesWithHistory": [ "&#x3C;string>" ], "idProperty": "&#x3C;string>" } '200default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "errors": [ { "category": "&#x3C;string>", "context": {}, "errors": [ { "message": "&#x3C;string>", "code": "&#x3C;string>", "context": "{missingScopes=[scope1, scope2]}", "in": "&#x3C;string>", "subCategory": "&#x3C;string>" } ], "links": {}, "message": "&#x3C;string>", "status": "&#x3C;string>", "id": "&#x3C;string>", "subCategory": {} } ], "links": {}, "numErrors": 123, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
