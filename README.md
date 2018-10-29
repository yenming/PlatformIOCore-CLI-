# PlatformIOCore-CLI
PlatformIO CLI使用說明筆記

### Blink Project
##### Used in demo

1. Source code of Wiring Blink Example
2. platformio run command
3. platformio run -t upload command.

##### How to build PlatformIO based project

1. Install PlatformIO Core</li>
2. Download <a href="https://github.com/platformio/platformio-examples/archive/develop.zip" title="MSN Search">examples source code</a>.
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
