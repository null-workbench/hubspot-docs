# Retrieve account details

## Endpoint
https://api.hubapi.com/account-info/2025-09/details

## Description
# Retrieve account details

Source: unknown source

---

Retrieve account details - HubSpot docsDetailsRetrieve account detailscloseRetrieve account detailscURLcurl --request GET \ --url https://api.hubapi.com/account-info/2025-09/details \ --header 'Authorization: Bearer &#x3C;token>'200default{ "accountType": "APP_DEVELOPER", "additionalCurrencies": [ "&#x3C;string>" ], "companyCurrency": "&#x3C;string>", "dataHostingLocation": "&#x3C;string>", "portalId": 123, "timeZone": "&#x3C;string>", "uiDomain": "&#x3C;string>", "utcOffset": "&#x3C;string>", "utcOffsetMilliseconds": 123 }DetailsRetrieve account detailsRetrieve account details such as the account type, time zone, currencies, and data hosting location.GET/account-info/2025-09/detailsRetrieve account detailscURLcurl --request GET \ --url https://api.hubapi.com/account-info/2025-09/details \ --header 'Authorization: Bearer &#x3C;token>'200default{ "accountType": "APP_DEVELOPER", "additionalCurrencies": [ "&#x3C;string>" ], "companyCurrency": "&#x3C;string>", "dataHostingLocation": "&#x3C;string>", "portalId": 123, "timeZone": "&#x3C;string>", "uiDomain": "&#x3C;string>", "utcOffset": "&#x3C;string>", "utcOffsetMilliseconds": 123 }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
