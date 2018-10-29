# PlatformIOCore-CLI
PlatformIO CLI使用說明筆記

### Blink Project
##### Used in demo

1. Source code of <a href="https://github.com/platformio/platformio-examples/tree/develop/wiring-blink" title="MSN Search">Wiring Blink Example</a>
2. platformio run 
3. platformio run -t upload
##### How to build PlatformIO based project

1. Install PlatformIO Core(written in Python 2.7)
2. Download <a href="https://github.com/platformio/platformio-examples/archive/develop.zip" title="MSN Search">examples source code</a>
3. Extract ZIP archive
4. Run these commands


```
# Change directory to example
> $cd platformio-examples/wiring-blink

# Build project
> $platformio run

# Upload firmware
> $platformio run --target upload

# Build specific environment
> $platformio run -e uno

# Upload firmware for the specific environment
> $platformio run -e uno --target upload

# Clean build files
> $platformio run --target clean
```

### Platform Manager
##### Used in demo

1. Platform Manager

```
platformio platform --help
platformio platform [COMMAND] --help
```

2. platformio platform list
3. platformio platform search avr
4. platformio platform show teensy
5. platformio platform update.

```

```
### Library Manager
##### Used in demo
```

```
### Over-the-Air update for ESP8266
##### Used in demo
```

```
