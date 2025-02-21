# PlatformIO Example

The example is used to guide how to use this library in PlatformIO. It also demonstrates how to port LVGL(v8). And for RGB LCD, it can enable the avoid tearing fucntion.

It is by default suitable for **Waveshare ESP32-S3 4.2inch lcd** and **Waveshare ESP32-S3 7inch lcd** boards. 

## How to Use

Follow the steps below to configure:

1. For **ESP32_Display_Panel**:

    - Follow the [steps](../../README.md#configuring-drivers) to configure drivers if needed.
    - If using a supported development board, follow the [steps](../../README.md#using-supported-development-boards) to configure it.
    - If using a custom board, follow the [steps](../../README.md#using-custom-development-boards) to configure it.

2. For **lvgl**:

    - Follow the [steps](../../README.md#configuring-lvgl) to add *lv_conf.h* file and change the configurations.
    - Modify the macros in the [lvgl_port_v8.h](./lvgl_port_v8.h) file to configure the LVGL porting parameters.

3. Navigate to the `Tools` menu in the Arduino IDE to choose a ESP board and configure its parameters. For supported boards, please refter to [Configuring Supported Development Boards](../../README.md#configuring-supported-development-boards)
4. Verify and upload the example to your ESP board.

## Serial Output

```bash
...
LVGL porting example start
Initialize panel device
Initialize LVGL
Create UI
LVGL porting example end
IDLE loop
IDLE loop
...
```
