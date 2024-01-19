# ABB-LINAK-Modbus
Program for ABB robots to control LINAK ELEVATE lifting column using Modbus TCP/IP


## Requirements

- **ABB Robot** with IRC5 or OmniCore controller
- **Multitasking** option
- **LINAK ELEVATE Modbus TCP/IP actuator**

## How to use

- Configure the IP of the robot to match the subnetwork "192.168.1.X".

- Load program modules from **LINAK_BG** to a background task
- Load program modules from **LINAK_TROB1** to the TROB1 -task

## Examples
- **TestRoutine** in the **Actuator** -module contains examples on how to control the actuator


## License

ABB-LINAK-Modbus is released under the Apache V2.0 License. See the [LICENSE](./LICENSE) file file for details.
