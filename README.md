# Country DB

## Purpose
Database of countries in json format

**Notes:**

*This repo while registered as an npm module should remain agnostic so that it
may be used with several languages and platforms.*

## Installation
Via [npm](https://www.npmjs.com/)

```bash
npm install @scuba-squad/country-db
```

## Usage
```javascript
const countries = require('@scuba-squad/country-db');
```

## Object Structure
**v1.0.0**

```json
{
  "name": "string",
  "iso2Code": "string",
  "iso3Code": "string",
  "isoNumericCode": "string",
  "postalCodeRegEx": "string | null",
  "callingCode": "string | string[]"
}
```

## License
[MIT](LICENSE)