---
title: "ESP32 as IED"
permalink: "/IED"
layout: default
---

# ESP32 as a IED for Protection, Automation and Control  

## Functionalities builtin:
* 32 bit CPU with 2 cores (Clock: 240 MHz)
* 16 I/O Ports (at least)
* Wi-fi and USB
* RAM: 520 Kbytes
* Flash: 4 Mbytes

## Functionalities to Implement:
1. Internal Timer: [Here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/system/system_time.html#system-time)
2. SNTP Time Synchronization: [Here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/system/system_time.html#sntp-time-synchronization)
3. Modbus Interface: [Here](https://docs.espressif.com/projects/esp-idf/en/v4.3.1/esp32/api-reference/protocols/modbus.html#esp-modbus)
4. RS485 Serial protocol:[Here]()
5. RS232 Serial protocol: [Here](https://esp32.com/viewtopic.php?t=9714)
6. Webserver: [Here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/protocols/esp_http_server.html#http-server) and [Here](https://github.com/espressif/esp-idf/tree/20f5e180eecccfaff815d707e1fcbba2f4d6a391/examples/protocols/https_server/simple)
7. HMI with keys: Using some digital inputs
8. DNP3: [Here](https://en.wikipedia.org/wiki/DNP3) and [here](https://www.cdoancal.com/) and [here](https://books.google.pt/books?id=ENqyW8fExswC&lpg=PA9-IA1&ots=k8emukH8R_&dq=DNP3&lr&pg=PA7#v=onepage&q=DNP3&f=false)  
9. I/O Modules: [Here](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/peripherals/i2c.html#inter-integrated-circuit-i2c)
10. Save Settings Permanently: [Here](https://randomnerdtutorials.com/esp32-save-data-permanently-preferences/)
