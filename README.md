# Console reporter for Sweter

This project refers to ``sweter``. If you are not familiar with ``sweter`` then take a look at [Sweter](https://github.com/msn0/sweter) first.

By default `sweter` uses `sweter-console-reporter`. It reports `domInteractive` timings.

## Installation

Just install `sweter`

```sh
$ npm install sweter -g
```

## Usage

`sweter-console-reporter` is used by default. Just run

```
$ sweter google.com
```

## Output

```
Tue, 28 Jul 2015 16:20:44 GMT
  timeToFirstByte: 239
  domInteractive: 553
  domComplete: 1548
```

All timings in milliseconds.