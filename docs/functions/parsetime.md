# @parseTime

Parses milliseconds into a readable format.

### Usage

```text
@parseTime[milliseconds, format]
```

#### Breakdown

* `milliseconds` - The milliseconds to parse. \| integer
* `format` - How the date/time should be formatted, uses [momentJS](https://momentjs.com/). \| ?string

### Formatting

```javascript
MMMM Do YYYY, h:mm:ss a
// June 5th 2021, 11:35:22 am
```

```javascript
dddd
// Saturday
```

```javascript
MMM Do YY
// Jun 5th 21
```

[\(see more\)](https://momentjs.com)

### Example
```javascript
@parseTime[@user[@authorID, createdTimestamp]]
```
