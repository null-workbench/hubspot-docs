# Archive a batch of subscriptions by ID

## Endpoint
https://api.hubapi.com/crm/v3/objects/subscriptions/batch/archive

## Description
# Archive a batch of subscriptions by ID

Source: unknown source

---

Archive a batch of subscriptions by ID - HubSpot docsBatchArchive a batch of subscriptions by IDcloseArchive multiple subscription objects in a single request.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of subscriptions by IDArchive a batch of subscription objects by providing their IDs in the request body.POST/crm/v3/objects/subscriptions/batch/archiveArchive multiple subscription objects in a single request.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/subscriptions/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
