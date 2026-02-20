# Introduction to LoRa
Introduction to LoRa, long range radio networking.

## Overview
- [LoRa and LoRaWAN concepts](#lora-and-lorawan-concepts)
- [FreakWAN LoRa mesh network](#freakwan-lora-mesh-network)
- [Meshtastic LoRa mesh network](#meshtastic-lora-mesh-network)
- [TheThingsNetwork LoRaWAN network](#thethingsnetwork-lorawan-network)

## LoRa and LoRaWAN concepts
### LoRa radio
- https://en.wikipedia.org/wiki/LoRa

### LoRaWAN networks
- https://blog.lora-alliance.org/what-is-lorawan
- https://www.thethingsnetwork.org/docs/lorawan/what-is-lorawan/

## FreakWAN LoRa mesh network
FreakWAN is a peer-to-peer/mesh network based on LoRa radio, it requires at least two nodes.

### FreakWAN overview
- https://github.com/antirez/freakwan

### FreakWAN firmware
- https://github.com/antirez/freakwan?tab=readme-ov-file#installation

### FreakWAN nodes
#### Lilygo T3 LoRa32 V1.6.1
- https://lilygo.cc/products/lora3 (USD 18)

### FreakWAN clients
- https://github.com/eriol/freakble

## Meshtastic LoRa mesh network
Meshtastic is a peer-to-peer/mesh network based on LoRa radio, it requires at least two nodes.

### Meshtastic overview
- https://meshtastic.org

### Meshtastic firmware
- https://github.com/meshtastic/firmware

### Meshtastic nodes
#### Xiao ESP32-S3 MCU w/ Wio SX1262 Module
- https://www.seeedstudio.com/Wio-SX1262-with-XIAO-ESP32S3-p-5982.html (USD 10)

### Meshtastic resources
- https://fosdem.org/2026/schedule/event/KUZUWX-off-grid_communication_cyberpunk_and_autonomy

## TheThingsNetwork LoRaWAN network
Shared backend with shared regional gateways, requires at least one node.

### TTN overview
- https://www.thethingsnetwork.org

### TTN backend
- https://eu1.cloud.thethings.network

### TTN gateways
> Note: LoRaWAN is a standard, gateways work with any provider.

#### Dragino gateway w/ 4G uplink
- https://dragino.com/products/lora-lorawan-gateway/item/225-dlos8n.html (e.g. from [Bastelgarage](https://www.bastelgarage.ch/dlos8n-4g-version-outdoor-multichannel-lorawan-gateway-1-2364?search=lora%20gateway), CHF 300)

#### Pi 3 Linux computer w/ IMST concentrator
- https://www.thingiverse.com/thing:1665467 (Enclosure)
- https://github.com/ttn-zh/ic880a-gateway/wiki (Software)
- https://shop.imst.de/wireless-modules/lora-products/8/ic880a-spi-lorawan-concentrator-868-mhz (EUR 150)
- https://shop.imst.de/wireless-modules/accessories/20/u.fl-to-sma-pigtail-cable-for-ic880a-spi (EUR 8)
- https://shop.imst.de/wireless-modules/accessories/19/sma-antenna-for-ic880a-spi-wsa01-im880b-and-lite-gateway (EUR 8)

### TTN firmware
> Note: Each module provides a library, see examples.

### TTN nodes
> Note: LoRaWAN is a standard, nodes work with any provider.

#### Arduino Uno MCU w/ RFM95W module
- http://www.tamberg.org/chopen/2017/LoRaWANIoTWorkshop.pdf (Example)
- https://github.com/dragino/Lora/tree/master/Lora%20Shield/hardware/v1.3

#### Feather M4 Express MCU w/ RFM95W module
- https://github.com/tamberg/fhnw-iot/blob/master/08/README.md (Example)
- https://github.com/tamberg/fhnw-iot/wiki/Feather-M4-Express (USD 23)
- https://github.com/tamberg/fhnw-iot/wiki/FeatherWing-RFM95W (USD 28)

#### Pi Pico W MCU w/ E5 module
- https://wiki.seeedstudio.com/Grove_LoRa_E5_New_Version/ (Example)
- https://www.seeedstudio.com/Raspberry-Pi-Pico-W-p-5429.html (USD 6)
- https://www.seeedstudio.com/Grove-LoRa-E5-STM32WLE5JC-p-4867.html (USD 16)
- https://www.seeedstudio.com/Grove-Shield-for-Pi-Pico-v1-0-p-4846.html (USD 4)

#### Pi Pico W MCU w/ E5 module (#MakeZurich badge)
- https://github.com/makezurich/makezurich-badge-2023-circuitpython (Example)
- https://github.com/makezurich/makezurich-badge-2023 (Hardware Docs, Source)
- http://www.tamberg.org/makezurich/2023/MakeZurichBadge2023.pdf

#### Pi Zero Linux Computer w/ RN2483 module
- https://github.com/tamberg/pi-lora (Example)
- https://www.raspberrypi.com/products/raspberry-pi-zero-w/ (e.g. from [Pi-shop](https://www.pi-shop.ch/raspberry-pi-zero-wh-kit), CHF 32)
- https://www.tindie.com/products/drazzy/lorawan-rn2483rn2903-breakout-board-assembled/ (USD 32)

#### Xiao ESP32-S3 MCU w/ Wio SX1262 module
- https://wiki.seeedstudio.com/wio_sx1262_with_xiao_esp32s3_kit/ (Example)
- https://www.seeedstudio.com/Wio-SX1262-with-XIAO-ESP32S3-p-5982.html (USD 10)

#### More nodes
- https://www.thethingsnetwork.org/device-repository/
