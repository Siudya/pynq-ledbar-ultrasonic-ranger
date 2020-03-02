## pynq-ledbar-ultrasonic-ranger
This repository contains an example of using ledbar and ultrasonic distance sensor on pynq-z2 board with Xilinx PYNQ Framework(image ver.2.4).

The design illustrates how to program embedded MircroBlaze cores to control a ultrasonic ranger and a ledbar on the FPGA with PYNQ base overlay. The pdf illustrate the operation(in Chinese).

## Quick start
```
sudo git clone https://github.com/Siudya/pynq-ledbar-ultrasonic-ranger.git /home/xilinx/jupyter_notebooks/pynq-ledbar-ultrasonic-ranger
```
Go to your jupyter home folder(`/home/xilinx/jupyter_notebooks`), and you will find this project fold `pynq-ledbar-ultrasonic-ranger`. Go in the fold you and run pynq-ledbar-ultrasonic-ranger.ipynb

##Devices and connection
Grove Ultrasonic Distance Sensor: https://www.seeedstudio.com/Grove-Ultrasonic-Distance-Sensor.html

Grove LED Bar: https://www.seeedstudio.com/Grove-LED-Bar-v2-0.html

Pmod-Grove adapter and PYNQ shield adapter: https://store.digilentinc.com/pynq-grove-system-add-on-board/

Grove Base Shield for Arduino: https://www.seeedstudio.com/Base-Shield-V2.html

There are 8 green, 1 orange and 1 red LED on the Grove LED Bar. Each LED brightness can be controlled independently.
In this design, if you use digilent PYNQ shield, LED Bar should be connected to G4 port.If you use Seeed base shield, LED Bar should be connected to D6 port.
The ultrasonic distance sensor should be connected to G1 port of the Pmod-Grove adapter and the latter should be connected to PMODA on the pynq-z2 board.

