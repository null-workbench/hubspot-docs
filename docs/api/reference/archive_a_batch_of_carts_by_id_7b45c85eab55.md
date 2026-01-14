# Archive a batch of carts by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/carts/batch/archive

## Description
# Archive a batch of carts by ID

Source: unknown source

---

Archive a batch of carts by ID - HubSpot docsBatchArchive a batch of carts by IDcloseArchive a batch of carts by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/carts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of carts by IDArchive a batch of carts identified by their IDs.POST/crm/v3/objects/carts/batch/archiveArchive a batch of carts by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/carts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
