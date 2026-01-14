# Archive a batch of contacts

## Endpoint
https://api.hubapi.com/crm/v3/objects/contacts/batch/archive

## Description
# Archive a batch of contacts

Source: unknown source

---

Archive a batch of contacts - HubSpot docsBatchArchive a batch of contactscloseArchive a batch of contactscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/contacts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of contactsArchive a batch of contacts by ID. Archived contacts can be restored within 90 days of deletion. Learn more about the data impacted by contact deletions and how to restore archived records.POST/crm/v3/objects/contacts/batch/archiveArchive a batch of contactscURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/contacts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
