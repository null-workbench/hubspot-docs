# Archive a batch of leads by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/leads/batch/archive

## Description
# Archive a batch of leads by ID

Source: unknown source

---

Archive a batch of leads by ID - HubSpot docsBatchArchive a batch of leads by IDcloseArchive a batch of leads by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/leads/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of leads by IDArchive multiple leads by their IDs in a single request, moving them to the recycling bin.POST/crm/v3/objects/leads/batch/archiveArchive a batch of leads by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/leads/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
