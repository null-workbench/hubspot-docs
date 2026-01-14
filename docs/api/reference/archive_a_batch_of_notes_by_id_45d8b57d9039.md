# Archive a batch of notes by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/notes/batch/archive

## Description
# Archive a batch of notes by ID

Source: unknown source

---

Archive a batch of notes by ID - HubSpot docsBatchArchive a batch of notes by IDcloseArchive a batch of notes by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/notes/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of notes by IDArchive multiple notes by their IDs in a single request. This operation moves the specified notes to the recycling bin, making them inaccessible from regular queries.POST/crm/v3/objects/notes/batch/archiveArchive a batch of notes by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/notes/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
