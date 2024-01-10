
# [![Passmeister.com](https://www.passmeister.com/logo.png)](https://www.passmeister.com)

# elm client for Apple Wallet and Google Wallet API

Demo API client (elm) for [passmeister.com](https://www.passmeister.com), the easiest developer API to create the most beautiful iOS and Android Wallet passes.

- The most beautiful passes: Simply upload a logo and an image -  **Passmeister automatically designs**  the most beautiful layouts.
- The easiest API: **By developers, for developers**  - including full OpenAPI Specification and Swagger UI to interact with the API.

This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project. By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

## API Endpoints
| Method | HTTP request | Description |
------------ | ------------- | ------------- |
| **POST** | /pass | This method creates or (if the pass id already exists) updates a pass, so you don&#39;t have to track ids and creation status of your passes.|
| **DELETE** | /pass | Delete pass by pass id.|
| **GET** | /pass | Get pass information by pass id.|
| **GET**| /pass/list | Retrieve the list of active pass ids for a given pass type.|
| **POST** | /pass/sync | Send updates to all active passes for a given pass type. |

## Passmeister
Digitize your  **customer cards, membership cards, tickets, season passes**  and more - with Passmeister.
[https://www.passmeister.com](https://www.passmeister.com)
