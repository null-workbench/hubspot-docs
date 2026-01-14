# Retrieve account details

## Endpoint
https://api.hubapi.com/account-info/v3/details

## Description
# Retrieve account details

Source: unknown source

---

Retrieve account details - HubSpot docsDetailsRetrieve account detailscloseRetrieve account detailscURLcurl --request GET \ --url https://api.hubapi.com/account-info/v3/details \ --header 'Authorization: Bearer &#x3C;token>'200default{ "additionalCurrencies": [ "NZD", "AUD", "EUR" ], "companyCurrency": "USD", "dataHostingLocation": "eu1", "portalId": 12345678, "timeZone": "US/Eastern", "uiDomain": "app-eu1.hubspot.com", "utcOffset": "-04:00", "utcOffsetMilliseconds": -14400000 }DetailsRetrieve account detailsRetrieve account details such as the account type, time zone, currencies, and data hosting location.GET/account-info/v3/detailsRetrieve account detailscURLcurl --request GET \ --url https://api.hubapi.com/account-info/v3/details \ --header 'Authorization: Bearer &#x3C;token>'200default{ "additionalCurrencies": [ "NZD", "AUD", "EUR" ], "companyCurrency": "USD", "dataHostingLocation": "eu1", "portalId": 12345678, "timeZone": "US/Eastern", "uiDomain": "app-eu1.hubspot.com", "utcOffset": "-04:00", "utcOffsetMilliseconds": -14400000 }

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
