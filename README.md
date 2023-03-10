# Project Based Learning

Project implemented as part of the Project based learning carried out by the Silesian University of Technology, in which I participated. My main task was to create a power supply board for an AGV robot.
For this project, I created several models in Autodesk Fusion 360 and printed them on a 3D printer.
In addition, I implemented a script on a Raspberry Pi using a Lepton thermal imaging camera to test overheating devices.

## Power supply board 
Two types of ToF sensors and lidar, two motors and an Nvidia Xavier were to be powered. The power supply was to come from LiPo batteries. In each line I installed shunt to research the current spikes. This is to directly test the voltage drop across the shunt, and by knowing the resistance, you can calculate the current spike caused by some fault.

### Elements
* Pololu 2857- 3.3V DC Step-down
* Pololu 2851- 5V DC Step-down
* 12V DC Step-down 300W/8A
* Shunt 100mV/10A x6
* Wires, soldering iron, tin, flux
* Goldpins, ark connectors
* Switch
* PCB board

### Scheme
![schem](https://user-images.githubusercontent.com/92868145/213928097-91c905ce-4ca8-41cf-9b94-4e7e0dabc57b.png)

### Effects
![boards](https://user-images.githubusercontent.com/92868145/213928304-06570189-60f6-467a-94f7-65a7f424adeb.png)


## 3D Printing
To model I used Autodesk Fusion 360, I did the printing on a Creality CR-2020 printer, and used an Ultimaker Cura for the G-code generation. The filament I used was PLA.
### Models
![3D](https://user-images.githubusercontent.com/92868145/213929036-aa8df670-30c9-4117-ba34-a1d12866dd8a.png)


