# Delete a batch of blog posts

## Endpoint
https://api.hubapi.com/cms/v3/blogs/posts/batch/archive

## Description
# Delete a batch of blog posts

Source: unknown source

---

Delete a batch of blog posts - HubSpot docsBatchDelete a batch of blog postscloseDelete a batch of blog postscURLcurl --request POST \ --url https://api.hubapi.com/cms/v3/blogs/posts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ "&#x3C;string>" ] } '204defaultThis response has no body data.BatchDelete a batch of blog postsDelete a blog post by ID. Note: This is not the same as the in-app archive function. To perform a dashboard archive send an normal update with the archivedInDashboard field set to true.POST/cms/v3/blogs/posts/batch/archiveDelete a batch of blog postscURLcurl --request POST \ --url https://api.hubapi.com/cms/v3/blogs/posts/batch/archive \ --header 'Authorization: Bearer &#x3C;token>' \ --header 'Content-Type: application/json' \ --data ' { "inputs": [ "&#x3C;string>" ] } '204defaultThis response has no body data.

## Authentication
OAuth 2.0 (Bearer token)

## Notes
This documentation was automatically extracted and normalised from HubSpot Developer Documentation.
