# MonkeyDebugViewer

#### A debug tool for embedded development.

- document: todo

- screenshot of rtt log viewer:(use cmsis-dap and SEGGER RTT print color log library)
  ![](screenshot-rtt.png)

- screenshot of serial log viewer:(test on ESP32 log)
  ![](screenshot-serial.png)

- screenshot of serial and dap plot viewer:(v0.02 update)

  ![image-20230114225442650](screenshot-rtt-plot.png)

- mywebsite: [https://makerinchina.cn](https://makerinchina.cn)



> This is the beta version.



- TODO:
  - log level filter
  - modbus
  - ...

##### Release Notes

- V0.02 Beta

|              | Support        | Test |
| ------------ | -------------- | ---- |
| DapLink View | Plot view      | -    |
| Serial View  | Plot view      | -    |
| App          | Window Display | -    |

- V0.01 Beta

|              | Support                     | Test              |
| ------------ | --------------------------- | ----------------- |
| DapLink View | USB HID Device/CMSIS DAP V1 | CMSIS DAP Device  |
| Serial View  | ANSI Color print            | CH340 USB to UART |

