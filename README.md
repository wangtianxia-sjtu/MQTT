# MQTT
ONENET MQTT SDK (Command Line Simulator under Linux)

## Usage

``` bash
gcc *.c -lm -O2 -Wall -o sample
(Some warnings...)
./sample -i 183.230.40.39 -p 6002 -j <Product ID 产品ID> -d <Device ID 设备ID> -a <APIKey 该产品的APIkey>
(Follow the instructions to connect...)
```

183.230.40.39:6002 is the MQTT endpoint of OneNET platform.

Enjoy!
