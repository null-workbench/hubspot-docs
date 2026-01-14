# Archive multiple associations between specified object types in a batch operation.

## Endpoint
https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/archive

## Description
# Archive multiple associations between specified object types in a batch operation.

Source: unknown source

---

Archive multiple associations between specified object types in a batch operation. - HubSpot docsBatchArchive multiple associations between specified object types in a batch operation.closeArchive multiple associations between specified object types in a batch operation.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "53628" }, "to": { "id": "12726" }, "type": "contact_to_company" } ] } '204defaultThis response has no body data.BatchArchive multiple associations between specified object types in a batch operation.This endpoint allows you to archive multiple associations between specified ‘from’ and ‘to’ object types in a single batch request.POST/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/archiveArchive multiple associations between specified object types in a batch operation.cURLcurl --request POST \ --url https://api.hubapi.com/crm/v3/associations/{fromObjectType}/{toObjectType}/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ { "from": { "id": "53628" }, "to": { "id": "12726" }, "type": "contact_to_company" } ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
