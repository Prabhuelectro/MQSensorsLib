# MQSensorsLib

This is a unified library to use sensors MQ: 2, 3, 4, 5, 6, 7, 8, 9, 131, 135, 303A and 309A.

## Getting Started

```
MQUnifiedsensor MQ4(pin, 4); //Example if sensor is MQ4, type = 4
float ppmCH4 = MQ4.readSensor();
```

### Prerequisites

You'll need Arduino desktop app 1.8.9 or later.

### Sensor manufacture:
| Sensor | Manufacture | URL Datasheet |
|----------|----------|----------|
| MQ-2 | Pololulu| [datasheet](https://www.pololu.com/file/0J309/MQ2.pdf) |
| MQ-3 | Sparkfun | [datasheet](https://www.sparkfun.com/datasheets/Sensors/MQ-3.pdf) |
| MQ-4 | Sparkfun | [datasheet](https://www.sparkfun.com/datasheets/Sensors/Biometric/MQ-4.pdf) |
| MQ-5 | parallax | [datasheet](https://www.parallax.com/sites/default/files/downloads/605-00009-MQ-5-Datasheet.pdf) |
| MQ-6 | Sparkfun | [datasheet](https://www.sparkfun.com/datasheets/Sensors/Biometric/MQ-6.pdf) |
| MQ-7 | Sparkfun | [datasheet](https://www.sparkfun.com/datasheets/Sensors/Biometric/MQ-7.pdf) |
| MQ-8 | Sparkfun | [datasheet](https://dlnmh9ip6v2uc.cloudfront.net/datasheets/Sensors/Biometric/MQ-8.pdf) |
| MQ-9 | Haoyuelectronics | [datasheet](http://www.haoyuelectronics.com/Attachment/MQ-9/MQ9.pdf) |
| MQ-131 | Sensorsportal | [datasheet](http://www.sensorsportal.com/DOWNLOADS/MQ131.pdf) |
| MQ-135 | HANWEI Electronics | [datasheet](https://www.electronicoscaldas.com/datasheet/MQ-135_Hanwei.pdf) |
| MQ-303A | HANWEI Electronics | [datasheet](http://www.kosmodrom.com.ua/pdf/MQ303A.pdf) |
| MQ-309A | HANWEI Electronics | [datasheet](http://www.sensorica.ru/pdf/MQ-309A.pdf) |

### Installing

Clone this repository into your desktop machine

```
git clone https://github.com/Prabhuelectro/MQSensorsLib
```

## Running the tests

Use calibration systems if you have several sensors that read the same gas.

### Break down into end to end tests

These tests can re-adjust values defined previously and you can contribute to improve conditions or features obtained from particular scenes.

```
Examples/MQ-3
```

### And coding style tests

These tests may generate statistics validation using descriptive tools for quantitative variables.

```
Examples/MQ-board.ino
```

<p align="center">
<img src="https://raw.githubusercontent.com/Prabhuelectro/MQSensorsLib1/master/image/bg.jpg">
</p>                                                                                                                    
