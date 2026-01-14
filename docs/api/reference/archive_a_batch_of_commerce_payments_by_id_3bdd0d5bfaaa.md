# Archive a batch of commerce payments by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/commerce_payments/batch/archive

## Description
# Archive a batch of commerce payments by ID

Source: unknown source

---

Archive a batch of commerce payments by ID - HubSpot docsBatchArchive a batch of commerce payments by IDcloseArchive a batch of commerce payments by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/commerce_payments/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of commerce payments by IDArchive a batch of commerce payments by their IDs. This operation moves the specified payments to the archive, making them inactive in the system.POST/crm/v3/objects/commerce_payments/batch/archiveArchive a batch of commerce payments by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/commerce_payments/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
