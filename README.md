# Balena HAL NodeJS SDK

## Usage example

```js
const BalenaHal = require("balena-hal").BalenaHal;

/*turn on /sys/class/leds/led0*/

BalenaHal.leds.write(0, 1);
```
