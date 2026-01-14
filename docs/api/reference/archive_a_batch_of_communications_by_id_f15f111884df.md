# Archive a batch of communications by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/communications/batch/archive

## Description
# Archive a batch of communications by ID

Source: unknown source

---

Archive a batch of communications by ID - HubSpot docsBatchArchive a batch of communications by IDcloseArchive a batch of communications by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/communications/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of communications by IDDelete a batch of messages by ID. A deleted message can be restored within 90 days of being deleted. Learn more about restoring activity records.POST/crm/v3/objects/communications/batch/archiveArchive a batch of communications by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/communications/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
