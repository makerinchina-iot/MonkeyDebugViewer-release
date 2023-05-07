# MonkeyDebugViewer

#### A debug tool for embedded development.

- document: [https://makerinchina.cn/wiki/](https://makerinchina.cn/wiki/)

- screenshot of rtt log viewer:(use cmsis-dap V2 and SEGGER RTT print color log library)
   ![](screenshot-rtt.png)
   
- screenshot of serial log viewer:(CH340 usb)
   ![](screenshot-serial.png)

- screenshot of dap plot viewer:(v0.02 update)

  ![image-20230114225442650](screenshot-rtt-plot.png)

- screenshot of serial plot viewer:(v0.02 update)

  ![serial-plot](screenshot-serial-plot.png)

- screenshot of serial shell viewer:(v0.04 update)

  ![](screenshot-uart-shell.png)

- screenshot of daplink shell viewer:(v0.04 update)

  ![](screenshot-daplink-shell.png)
  
  

- **More Info on my website:** [https://makerinchina.cn](https://makerinchina.cn)



> This is the beta version.



- TODO:
  - log level filter
  - modbus view
  - ...

##### Release Notes

- V0.04 Beta

|              | Support               | Test |
| ------------ | --------------------- | ---- |
| DapLink View | add shell view(vt100) | -    |
| Serial View  | add shell view(vt100) | -    |

- V0.03 Beta

|         | Support                                                      | Test |
| ------- | ------------------------------------------------------------ | ---- |
| DapLink | Support CMSIS DAP V2 winusb Device ( HID version now removed) | -    |

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

