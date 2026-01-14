# Archive a batch of goal targets by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/goal_targets/batch/archive

## Description
# Archive a batch of goal targets by ID

Source: unknown source

---

Archive a batch of goal targets by ID - HubSpot docsBatchArchive a batch of goal targets by IDcloseArchive a batch of goal targets by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/goal_targets/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of goal targets by IDArchive multiple goal targets in a single batch operation using their IDs.POST/crm/v3/objects/goal_targets/batch/archiveArchive a batch of goal targets by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/goal_targets/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
