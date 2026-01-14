# Archive a batch of fees by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/fees/batch/archive

## Description
# Archive a batch of fees by ID

Source: unknown source

---

Archive a batch of fees by ID - HubSpot docsBatchArchive a batch of fees by IDcloseArchive a batch of fees by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/fees/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of fees by IDArchive multiple fees by their IDs, effectively moving them to the recycling bin.POST/crm/v3/objects/fees/batch/archiveArchive a batch of fees by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/fees/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
