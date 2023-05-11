# Catalog Integration v2

This repo is intended to be an advancement of the first [catalog-integraton](https://github.com/postman-solutions-eng/catalog-integration) example.

This is intended to be as lightweight example as possible that isn't opinionated on any specific type of implementation.

# Main goals of this integration

To create a Postman Workspace, API, Collection, Mock Server and list within Postman's Private Network.

# Understanding how it works

3 endpoints from the Postman API are used to enable this experience:

- [Get all workspaces](https://www.postman.com/postman/workspace/postman-public-workspace/request/12959542-f027a0fa-9012-4654-a65d-2b751a3154a9)

- [Create a mock server](https://www.postman.com/postman/workspace/postman-public-workspace/request/12959542-296628ed-d49b-4206-b4a7-d622e693945c)

This can be seen in more detail in [api.js](https://github.com/postman-solutions-eng/catalog-integration-v2/blob/main/api.js)

# Example

You can see this repo in practice via the GitHub pages link below:

https://postman-solutions-eng.github.io/catalog-integration-v2/
