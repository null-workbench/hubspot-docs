# Archive a batch of companies

## Endpoint
https://api.hubapi.com/crm/v3/objects/companies/batch/archive

## Description
# Archive a batch of companies

Source: unknown source

---

Archive a batch of companies - HubSpot docsBatchArchive a batch of companiescloseArchive a batch of companiescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/companies/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.BatchArchive a batch of companiesDelete a batch of companies by ID. Deleted companies can be restored within 90 days of deletion. Learn more about restoring records.POST/crm/v3/objects/companies/batch/archiveArchive a batch of companiescURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/objects/companies/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "id": "430001" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
