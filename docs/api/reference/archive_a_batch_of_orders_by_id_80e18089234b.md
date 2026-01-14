# Archive a batch of orders by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/orders/batch/archive

## Description
# Archive a batch of orders by ID

Source: unknown source

---

Archive a batch of orders by ID - HubSpot docsBatchArchive a batch of orders by IDcloseArchive a batch of orders by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/orders/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of orders by IDArchive a batch of orders identified by their IDs.POST/crm/v3/objects/orders/batch/archiveArchive a batch of orders by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/orders/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
