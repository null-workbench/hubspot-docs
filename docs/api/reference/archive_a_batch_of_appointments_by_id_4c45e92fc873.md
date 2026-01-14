# Archive a batch of appointments by ID

## Endpoint
https://api.hubapi.com/crm/objects/v3/{objectType}/batch/archive

## Description
# Archive a batch of appointments by ID

Source: unknown source

---

Archive a batch of appointments by ID - HubSpot docsBatchArchive a batch of appointments by IDcloseArchive a batch of appointments by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/objects/v3/{objectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of appointments by IDArchive multiple appointments using their IDs.POST/crm/objects/v3/{objectType}/batch/archiveArchive a batch of appointments by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/objects/v3/{objectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
