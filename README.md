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
$ platformio platform --help
$ platformio platform [COMMAND] --help
```

2. platformio platform list (List installed Development Platforms)

```
$ platformio platform list [OPTIONS]
```

3. platformio platform search (Search for development Development Platforms)

```
$ platformio platform search QUERY [OPTIONS]
$ pio platform search QUERY [OPTIONS]
```

4. platformio platform show teensy (Show details about Development Platforms)

```
$ platformio platform show [PLATFORM]
$ pio platform show [PLATFORM]
```

5. platformio platform update(Check or update installed Development Platforms)

```
$ platformio platform update [OPTIONS] [PLATFORM...]
$ pio platform update [OPTIONS] [PLATFORM...]

# update specific platform version using Semantic Versioning
$ platformio platform update PLATFORM@X.Y.Z
```
6. platformio platform uninstall (Uninstall specified Development Platforms)
```
$ platformio platform uninstall [PLATFORM...]
$ pio platform uninstall [PLATFORM...]

# uninstall specific platform version using Semantic Versioning
$ platformio platform uninstall PLATFORM@X.Y.Z
```
7. platformio remote
```
$ pio remote --help
$ platformio remote --help
$ platformio remote [COMMAND] --help

# run command on the specified PIO Remote Agents
 platformio remote --agent NAME_1 --agent NAME_N COMMAND
```
### Library Manager
##### Used in demo
```
Library Manager
platformio lib search 1-wire 
platformio lib install 54 
platformio lib search -f mbed 
platformio lib search -k rf 
platformio lib search radiohead 
platformio lib install 124 –version “1.40” 
platformio lib show 124 
platformio lib update 
```
### Over-the-Air update for ESP8266
##### Used in demo
```
1. platformio run 
2. platformio run -t upload

```
