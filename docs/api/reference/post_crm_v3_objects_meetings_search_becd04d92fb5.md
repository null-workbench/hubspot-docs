# POST /crm/v3/objects/meetings/search

## Endpoint
https://api.hubapi.com/crm/v3/objects/meetings/search

## Description
# POST /crm/v3/objects/meetings/search

Source: unknown source

---

POST /crm/v3/objects/meetings/search - HubSpot docsSearchPOST /crm/v3/objects/meetings/searchclosecURLcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/meetings/search \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "after": "&#x3C;string>", "filterGroups": [ { "filters": [ { "operator": "BETWEEN", "propertyName": "&#x3C;string>", "highValue": "&#x3C;string>", "value": "&#x3C;string>", "values": [ "&#x3C;string>" ] } ] } ], "limit": 123, "properties": [ "&#x3C;string>" ], "sorts": [ "&#x3C;string>" ], "query": "&#x3C;string>" } '200default{ "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "total": 123, "paging": { "next": { "after": "NTI1Cg%3D%3D", "link": "?after=NTI1Cg%3D%3D" }, "prev": { "before": "&#x3C;string>", "link": "&#x3C;string>" } } }SearchPOST /crm/v3/objects/meetings/searchPOST/crm/v3/objects/meetings/searchcURLcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/meetings/search \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "after": "&#x3C;string>", "filterGroups": [ { "filters": [ { "operator": "BETWEEN", "propertyName": "&#x3C;string>", "highValue": "&#x3C;string>", "value": "&#x3C;string>", "values": [ "&#x3C;string>" ] } ] } ], "limit": 123, "properties": [ "&#x3C;string>" ], "sorts": [ "&#x3C;string>" ], "query": "&#x3C;string>" } '200default{ "results": [ { "archived": false, "createdAt": "2019-10-30T03:30:17.883Z", "id": "512", "properties": { "property_checkbox": "false", "property_date": "1572480000000", "property_dropdown": "choice_b", "property_multiple_checkboxes": "chocolate;strawberry", "property_number": "17", "property_radio": "option_1", "property_string": "value" }, "updatedAt": "2019-12-07T16:50:06.678Z" } ], "total": 123, "paging": { "next": { "after": "NTI1Cg%3D%3D", "link": "?after=NTI1Cg%3D%3D" }, "prev": { "before": "&#x3C;string>", "link": "&#x3C;string>" } } }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
