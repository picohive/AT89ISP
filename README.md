# AT89ISP
Arduino based AT89S51 programmer

## Compile

Use Arduino IDE to compile the arduino sketch under `AT89Interface` folder

The application relies on Qt and qhexedit2

```
cmake [This repository] -DCMAKE_PREFIX_PATH=[Path to Qt];[Path to qhexedit2]
make
```

## Wiring

RST pin on the AT89S51 to pin 10 on the Arduino

Pin 8 (P1.7) on the AT89S51 to pin 13 on the Arduino (SCK)

Pin 7 (P1.6) on the AT89S51 to pin 12 on the Arduino (MISO)

Pin 6 (P1.5) on the AT89S51 to pin 11 on the Arduino (MOSI)
