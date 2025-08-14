Phel example for interfacing with Google Sheets API

# Usage

1) Install Composer dependencies with `composer install`
2) In Google API Console enable GSheets API, add services account with Google Sheets access and add key for it that generates `.json` file (e.g. `service_account_key.example.json`). Save it as `service_account_key.json` in this folder. Follow [nidup tutorial](https://www.nidup.io/blog/manipulate-google-sheets-in-php-with-api/) for more (mostly up to date) info on key creation if required.

Run main namespace with `phel run main.phel` or evaluate code with `phel repl`. If you don't have standalone `phel` Phar distribution in PATH, use `vendor/bin/phel` instead (Phar build feature https://github.com/phel-lang/phel-lang/pull/835).

## About project structure
While there's [cli-skeleton](https://github.com/phel-lang/cli-skeleton/) and [web-skeleton](https://github.com/phel-lang/web-skeleton) projects, this project uses more minimal project structure.

# Credits / PHP Docs

- "Reading and Writing Google Sheets in PHP" tutorial by nidup
  - https://www.nidup.io/blog/manipulate-google-sheets-in-php-with-api/
  - https://github.com/nidup/manipulate-google-sheets-api-in-php

- https://github.com/googleapis/google-api-php-client-services
- https://github.com/googleapis/google-api-php-client
