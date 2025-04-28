# HttpStatus

A simple, lightweight PHP library that provides HTTP status code constants, inspired by the PHP-FIG's `StatusCodeInterface`.

## Installation

You can install this package via Composer:

```bash
composer require jaimecx/http-status
```

## Usage
Use the provided HTTP status code constants to improve the readability and consistency of your PHP applications.

## Example
```php
<?php

use Jaimecx\Http\HttpStatus;

echo HttpStatus::OK; // Outputs: 200
echo HttpStatus::NOT_FOUND; // Outputs: 404
```
## Available Status Codes:
### Informational (1xx)
- `HttpStatus::CONTINUE` (100)
- `HttpStatus::SWITCHING_PROTOCOLS` (101)
- `HttpStatus::PROCESSING` (102)
- `HttpStatus::EARLY_HINTS` (103)
### Success (2xx)
- `HttpStatus::OK` (200)
- `HttpStatus::CREATED` (201)
- `HttpStatus::ACCEPTED` (202)
- `HttpStatus::NON_AUTHORITATIVE_INFORMATION` (203)
- `HttpStatus::NO_CONTENT` (204)
- `HttpStatus::RESET_CONTENT` (205)
- `HttpStatus::PARTIAL_CONTENT` (206)
- `HttpStatus::MULTI_STATUS` (207)
- `HttpStatus::ALREADY_REPORTED` (208)
- `HttpStatus::IM_USED` (226)
### Redirection (3xx)
- `HttpStatus::MULTIPLE_CHOICES` (300)
- `HttpStatus::MOVED_PERMANENTLY` (301)
- `HttpStatus::FOUND` (302)
- `HttpStatus::SEE_OTHER` (303)
- `HttpStatus::NOT_MODIFIED` (304)
- `HttpStatus::USE_PROXY` (305)
- `HttpStatus::TEMPORARY_REDIRECT` (307)
- `HttpStatus::PERMANENT_REDIRECT` (308)
### Client Error (4xx)
- `HttpStatus::BAD_REQUEST` (400)
- `HttpStatus::UNAUTHORIZED` (401)
- `HttpStatus::PAYMENT_REQUIRED` (402)
- `HttpStatus::FORBIDDEN` (403)
- `HttpStatus::NOT_FOUND` (404)
- `HttpStatus::METHOD_NOT_ALLOWED` (405)
- `HttpStatus::NOT_ACCEPTABLE` (406)
- `HttpStatus::PROXY_AUTHENTICATION_REQUIRED` (407)
- `HttpStatus::REQUEST_TIMEOUT` (408)
- `HttpStatus::CONFLICT` (409)
- `HttpStatus::GONE` (410)
- `HttpStatus::LENGTH_REQUIRED` (411)
- `HttpStatus::PRECONDITION_FAILED` (412)
- `HttpStatus::PAYLOAD_TOO_LARGE` (413)
- `HttpStatus::URI_TOO_LONG` (414)
- `HttpStatus::UNSUPPORTED_MEDIA_TYPE` (415)
- `HttpStatus::RANGE_NOT_SATISFIABLE` (416)
- `HttpStatus::EXPECTATION_FAILED` (417)
- `HttpStatus::IM_A_TEAPOT` (418)
- `HttpStatus::MISDIRECTED_REQUEST` (421)
- `HttpStatus::UNPROCESSABLE_ENTITY` (422)
- `HttpStatus::LOCKED` (423)
- `HttpStatus::FAILED_DEPENDENCY` (424)
- `HttpStatus::TOO_EARLY` (425)
- `HttpStatus::UPGRADE_REQUIRED` (426)
- `HttpStatus::PRECONDITION_REQUIRED` (428)
- `HttpStatus::TOO_MANY_REQUESTS` (429)
- `HttpStatus::REQUEST_HEADER_FIELDS_TOO_LARGE` (431)
- `HttpStatus::UNAVAILABLE_FOR_LEGAL_REASONS` (451)
### Server Error (5xx)
- `HttpStatus::INTERNAL_SERVER_ERROR` (500)
- `HttpStatus::NOT_IMPLEMENTED` (501)
- `HttpStatus::BAD_GATEWAY` (502)
- `HttpStatus::SERVICE_UNAVAILABLE` (503)
- `HttpStatus::GATEWAY_TIMEOUT` (504)
- `HttpStatus::HTTP_VERSION_NOT_SUPPORTED` (505)
- `HttpStatus::VARIANT_ALSO_NEGOTIATES` (506)
- `HttpStatus::INSUFFICIENT_STORAGE` (507)
- `HttpStatus::LOOP_DETECTED` (508)
- `HttpStatus::NOT_EXTENDED` (510)
- `HttpStatus::NETWORK_AUTHENTICATION_REQUIRED` (511)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome!
Feel free to open an issue or submit a pull request to help improve this library.

© 2025 [Jaime Cruz](https://jaimecx.com)