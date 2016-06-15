## Electrolink Server for Freertos

`Electrolink RIOT Server` is a [Freertos](http://www.freertos.org/) application that is implementing [Electrolink protocol specification](https://github.com/projectiota/electrolink/blob/master/electrolink-protocol.md) file

It targets [Espressif ESP8266](https://espressif.com/en/products/hardware/esp8266ex/overview) architecture.

## Usage
Clone [esp-open-rtos](https://github.com/SuperHouse/esp-open-rtos):
```
git clone https://github.com/SuperHouse/esp-open-rtos
```

Clone Electrolink Freertos server app next to `esp-open-rtos` dir:
```
git clone https://github.com/projectiota/electrolink-server-freertos
```

Build:
```
cd electrolink-server-freertos
make
```

Execute:
```
make flash
```

## License
[Apache-2.0](http://www.apache.org/licenses/LICENSE-2.0)
