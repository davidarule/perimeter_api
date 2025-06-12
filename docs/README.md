# Insitec Client-Server API Documentation

This repository holds the design and documentation for the client-server API used by Insitec devices.

## API Specification

- **OpenAPI 3.0**: [`oas/openapi.yaml`](../oas/openapi.yaml)
- **Swagger 2.0**: [`oas/swagger.yaml`](../oas/swagger.yaml)

## Swagger UI

- API documentation is viewable via [Swagger UI](../swagger-ui/index.html) (or on the deployed GitHub Pages site).

## Documentation Hosting

API documentation is automatically deployed to [GitHub Pages](https://davidsrule.github.io/perimeter_api/) on every push to `main`.

## How to Add a New API Version

1. Add your new OAS or Swagger file under `oas/` (e.g. `oas/openapi-v2.yaml`).
2. Update `swagger-ui/index.html` if you want the Swagger UI to point to a different version.
3. Commit and push your changes.

## Authentication

- This API uses HTTP Basic Authentication.
- Example username: `insitec@hexlitix.com`
- Example password: `demo`