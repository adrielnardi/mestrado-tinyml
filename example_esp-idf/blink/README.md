# Blink Example

Starts a FreeRTOS task to blink an LED

See the README.md file in the upper level 'examples' directory for more information about examples.

### Prerequisites

-   [Install ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html)
-   Set the `IDF_PATH` environment variable. [Some Help](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html#step-4-set-up-the-environment-variables)
-   `idf.py` and Xtensa-esp32 tools (e.g., `xtensa-esp32-elf-gcc`) must be in `$PATH`

### Installation

To build, simply run:

```
idf.py build
```

To flash (use the corresponding USB port):

```
idf.py --port /dev/ttyUSB0 flash
```

Open the serial monitor:

```
idf.py --port /dev/ttyUSB0 monitor
```

