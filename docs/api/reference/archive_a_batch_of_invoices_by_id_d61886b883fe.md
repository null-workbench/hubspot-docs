# Archive a batch of invoices by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/invoices/batch/archive

## Description
# Archive a batch of invoices by ID

Source: unknown source

---

Archive a batch of invoices by ID - HubSpot docsBatchArchive a batch of invoices by IDcloseArchive a batch of invoices by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/invoices/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of invoices by IDArchive multiple invoices by their IDs in a single request. This operation moves the specified invoices to the archive, making them inactive but retrievable for future reference.POST/crm/v3/objects/invoices/batch/archiveArchive a batch of invoices by IDcURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/invoices/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
