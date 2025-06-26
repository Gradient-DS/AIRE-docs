# AIRE-docs
_public_
_docs_

This repository contains the OpenAPI 3.1 specification for the AIRE chat service running at <to be disclosed>
All endpoints are secured with OAuth 2 / OpenID Connect tokens issued by <to be disclosed>; clients must obtain a JWT (scope aire) via the authorization-code + PKCE flow before calling the API.
Core routes let you send chat messages, fetch or delete a user’s chat history, and silently refresh access tokens when using HttpOnly cookies.
Start by loading openapi.yaml into your favourite tool (e.g. Postman, Swagger UI) to explore and test the endpoints.
