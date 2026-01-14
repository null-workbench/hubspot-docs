# Read a batch of deal split objects by their associated deal object internal ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/deals/splits/batch/read

## Description
# Read a batch of deal split objects by their associated deal object internal ID

Source: unknown source

---

Read a batch of deal split objects by their associated deal object internal ID - HubSpot docsBatchRead a batch of deal split objects by their associated deal object internal IDcloseRead a batch of deal split objects by their associated deal object internal IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/deals/splits/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>" } ] } '200207default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "id": "&#x3C;string>", "splits": [ { "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archived": true, "archivedAt": "2023-11-07T05:31:56Z", "propertiesWithHistory": {} } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "links": {}, "requestedAt": "2023-11-07T05:31:56Z" }BatchRead a batch of deal split objects by their associated deal object internal IDRead a batch of deal split objects by their associated deal object internal IDPOST/crm/v3/objects/deals/splits/batch/readRead a batch of deal split objects by their associated deal object internal IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/deals/splits/batch/read \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "&#x3C;string>" } ] } '200207default{ "completedAt": "2023-11-07T05:31:56Z", "results": [ { "id": "&#x3C;string>", "splits": [ { "createdAt": "2023-11-07T05:31:56Z", "id": "&#x3C;string>", "properties": {}, "updatedAt": "2023-11-07T05:31:56Z", "archived": true, "archivedAt": "2023-11-07T05:31:56Z", "propertiesWithHistory": {} } ] } ], "startedAt": "2023-11-07T05:31:56Z", "status": "CANCELED", "links": {}, "requestedAt": "2023-11-07T05:31:56Z" }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
