# timezones-list-custom
This package is a custom version of the [timezones-list](https://www.npmjs.com/package/timezones-list) package.

It does not follow any complete data set, but it contains almost all basic timezones. And all names are according to the tz format: [https://en.wikipedia.org/wiki/List_of_tz_database_time_zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)

The fields in the array are as follows:
* `label` a string label which contains the UTC with the `tz` code of a timezone
* `tzCode` contains the `tz` codes
* `name` contains the descriptive name of the timezone with UTC offset
* `utc` contains only the UTC of a timezone

## Install
```bash
npm install timezones-list-custom --save

# or

yarn add timezones-list-custom
```

## Example
```javascript
import timezones from 'timezones-list-custom';

// or

var timezones = require('timezones-list-custom');
```
