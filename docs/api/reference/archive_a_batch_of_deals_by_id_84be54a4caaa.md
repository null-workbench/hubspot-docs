# Archive a batch of deals by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/0-3/batch/archive

## Description
# Archive a batch of deals by ID

Source: unknown source

---

Archive a batch of deals by ID - HubSpot docsBatchArchive a batch of deals by IDcloseArchive a batch of deals by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/0-3/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of deals by IDArchive multiple deals using their IDs.POST/crm/v3/objects/0-3/batch/archiveArchive a batch of deals by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/0-3/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
