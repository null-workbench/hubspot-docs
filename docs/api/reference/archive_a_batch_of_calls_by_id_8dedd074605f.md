# Archive a batch of calls by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/calls/batch/archive

## Description
# Archive a batch of calls by ID

Source: unknown source

---

Archive a batch of calls by ID - HubSpot docsBatchArchive a batch of calls by IDcloseArchive a batch of calls by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/calls/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of calls by IDArchive a batch of calls by ID. Deleted calls can be restored within 90 days of being deleted, but call recordings recording will be permanently deleted. Learn more about restoring activity records.POST/crm/v3/objects/calls/batch/archiveArchive a batch of calls by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/calls/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
