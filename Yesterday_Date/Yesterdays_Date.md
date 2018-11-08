# Yesterdays Date

Quick and dirty way to display yesterdays ( or any day in the past or future ) date.

## Description

* Gets the current date and subtracts to 24 hours in the past. 
* Formats date to "Long Date" ex. January 1 2018.

### Changing Date Range

* Adjust the date range by changing var yesterday
```
var yesterday = new Date(new Date().getTime() - 24 * 60 * 60 * 1000);
```
