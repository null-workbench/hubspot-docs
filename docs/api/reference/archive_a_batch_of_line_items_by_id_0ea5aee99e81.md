# Archive a batch of line items by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/line_items/batch/archive

## Description
# Archive a batch of line items by ID

Source: unknown source

---

Archive a batch of line items by ID - HubSpot docsBatchArchive a batch of line items by IDcloseArchive a batch of line items by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/line_items/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of line items by IDArchive multiple line items simultaneously by specifying their IDs in the request body.POST/crm/v3/objects/line_items/batch/archiveArchive a batch of line items by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/line_items/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
