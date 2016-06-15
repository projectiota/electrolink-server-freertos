## Electrolink Server for RIOT RTOS

`Electrolink RIOT Server` is a [RIOT RTOS](https://www.riot-os.org/) application that is implementing [Electrolink protocol specification](https://github.com/projectiota/electrolink/blob/master/electrolink-protocol.md) file

## Usage
Clone [RIOT RTOS](https://github.com/RIOT-OS/RIOT):
```
git clone https://github.com/RIOT-OS/RIOT
```

Clone Electrolink RIOT server app next to RIOT RTOS dir:
```
git clone https://github.com/projectiota/electrolink-server-riot
```

Build:
```
cd electrolink-server-riot
make
```

Execute:
```
./bin/native/electrolink-server-riot.elf 
```

## License
[Apache-2.0](http://www.apache.org/licenses/LICENSE-2.0)
