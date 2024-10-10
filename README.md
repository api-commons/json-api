# JSON:API
This is an API Commons working repository for developing reusable JSON:API components that can be used as part of API development.

Currently, there are three key artifacts in this repository:

- [**JSON Schema (JSON)**](json-schema.json) - A complete JSON Schema found via a Columbia University repository](https://github.com/columbia-it/django-jsonapi-training/blob/master/docs/schemas/original-jsonapi.json), covering the success, errors, and info aspects of JSON:API.
- [**JSON Schema (YAML)**](json-schema.yml) - A YAML derivative of the master JSON Schema that covers only the success portion of JSON:API, and applying meta, data, and pagination to APIs.
- [**OpenAPI (YAML)**](openapi.yml) - A seed of an OpenAPI that takes the JSON Schema (YAML) and begins using it to validate different API responses covering basic meta, data, and pagination examples.

I will be doing more work on this suite of JSON:API components. My goal was to standardize the API responses for [APIs.io](https://apis.io) and [API Evangelist](https://apievangelist.com) API, but then also contribute something to the API Commons that others can use. There is a lot of work still to be done, but the work here should be useful enough to jump start a variety of use cases.

If you have any questions or needs feel free to submit an issue or email kin@apievangelist.com.