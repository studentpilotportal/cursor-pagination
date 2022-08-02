> This branch contains a bug fix that allows the use of hashed ids with cursor pagination. Previously, the ids would not be properly encoded. This repo only exists to prevent unexpected changes in production from the original author since these changes have not yet been merge. Those changes are on the "dev-feature/id-decoding" branch. The original author's package should be used as soon as possible once the changes are merged and is stable.

# laravel-json-api/cursor-pagination

Cursor pagination for [Laravel JSON:API](https://laraveljsonapi.io) packages.

This cursor implementation pre-dates Laravel's cursor pagination implementation. It matches the cursor pagination implementation
in the legacy package [cloudcreativity/laravel-json-api](https://github.com/cloudcreativity/laravel-json-api).

## Installation

Install using [Composer](https://getcomposer.org)

```bash
composer require laravel-json-api/cursor-pagination
```

## License

Laravel JSON:API is open-sourced software licensed under the [Apache 2.0 License](./LICENSE).
