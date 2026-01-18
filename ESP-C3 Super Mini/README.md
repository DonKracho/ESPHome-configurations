## ESP32-C3 Super Mini basic configuration

The ESP-C3 Super Mini is a more worthy ES8266 replacement. It has no dedicated serial hardware. It uses the internal USB port of the ESP-C3 chip for uploading firmware.
To make logging available it is required to specify the communication port "hardware_uart: UART0"!

As for all new ESP32 chip generations it is strongly recomended to use the esp-idf framework.