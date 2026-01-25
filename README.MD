# Smart Six-way High Side Switch Node
Compact power management board intended to control six high-side DC loads. The node provides current monitoring of each load, and the board total. Temperature and supply voltage are also monitored. This node works with other CAN-CTL modules using the robust CAN bus interface.

* STM32G071 microcontroller with 64 pins and 256k flash
* Six Infineon BTS7002 Profet Smart Switches for high side loads; firmware limited to 15 amps each
* Allegro ACS712 on board to monitor total board current; firmware limited to 30 amps
* Microchip MCP2562 isolated CAN bus transceiver
* Microchip MCP9701 board mount temperature sensor
* Voltage divider to monitor supply voltage
* Each switch provides current monitoring and diagnostics
* Screw terminal block for CAN bus connection
* Screw terminal block for power-out, up to 12 AWG
* Heavy duty screw terminals for power in, up to 6 AWG cable
* Headers for SWD programming and USART2 serial port

<IMG src="https://github.com/gordonthree/SW-SMART-SIX-HIGH/blob/main/SW-SMART-SIX-HIGH.png?raw=true" width=480>