# Google AppSheet API

The Google AppSheet API enables programmatic access to AppSheet applications, allowing developers to add, update, delete, and find records in AppSheet tables, as well as invoke predefined AppSheet actions via a REST interface.

## APIs

- **Google AppSheet API** - CRUD operations on AppSheet table data and custom action invocation.

## Base URL

```
https://api.appsheet.com/api/v2
```

## Key Endpoints

- **Invoke Action** - `POST /apps/{appId}/tables/{tableName}/Action` - Add, Delete, Edit, Find records or invoke custom actions

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index
- [OpenAPI](openapi/openapi.yml) - OpenAPI 3.1.0 specification
- [JSON Schema](json-schema/ActionRequest.json) - JSON Schema (draft 2020-12) for ActionRequest
- [JSON-LD Context](json-ld/context.jsonld) - JSON-LD context mapping

## Resources

- [Getting Started](https://support.google.com/appsheet/answer/10105398)
- [Pricing](https://workspace.google.com/products/appsheet/pricing/)
- [API Integration Points](https://support.google.com/appsheet/answer/11628886)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
