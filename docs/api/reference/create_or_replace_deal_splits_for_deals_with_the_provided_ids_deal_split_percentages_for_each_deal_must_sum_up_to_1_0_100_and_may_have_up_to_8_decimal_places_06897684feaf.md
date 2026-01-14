# Create or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal places

## Endpoint
https://api.hubapi.com/crm/v3/objects/deals/splits/batch/upsert

## Description
# Create or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal places

Source: unknown source

---

Create or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal places - HubSpot docsBatchCreate or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal placescloseCreate or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal placescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/deals/splits/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": 123, "splits": [ { "ownerId": 123, "percentage": 123 } ] } ] } '200207default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "id": "&#x3C;string>", "splits": [ { "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archived": true, "archivedAt": "2023-11-07T05:31:56Z", "propertiesWithHistory": {} } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "links": {}, "requestedAt": "2023-11-07T05:31:56Z" }BatchCreate or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal placesCreate or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal placesPOST/crm/v3/objects/deals/splits/batch/upsertCreate or replace deal splits for deals with the provided IDs. Deal split percentages for each deal must sum up to 1.0 (100%) and may have up to 8 decimal placescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/deals/splits/batch/upsert \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": 123, "splits": [ { "ownerId": 123, "percentage": 123 } ] } ] } '200207default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "id": "&#x3C;string>", "splits": [ { "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archived": true, "archivedAt": "2023-11-07T05:31:56Z", "propertiesWithHistory": {} } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "links": {}, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
