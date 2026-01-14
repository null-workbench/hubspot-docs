# Archive a batch of discounts by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/discounts/batch/archive

## Description
# Archive a batch of discounts by ID

Source: unknown source

---

Archive a batch of discounts by ID - HubSpot docsBatchArchive a batch of discounts by IDcloseArchive a batch of discounts by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/discounts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of discounts by IDArchive multiple discounts by their IDs in a single request. This operation moves the specified discounts to the recycling bin, effectively removing them from active use.POST/crm/v3/objects/discounts/batch/archiveArchive a batch of discounts by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/discounts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
