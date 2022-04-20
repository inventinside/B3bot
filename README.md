# B3bot
B3 BeFree (Building Balanced Bots)

# Dynamic robots
Dynamic robots should be well balanced in order to leverage the effects of gravity.

# Read more:
https://inventinside.com/item/robot-arm

4 DOF motorized platform based on 3D Printer control board Duet3D. 

Duet 2 wifi motor controller may be instructed using HTTP REST API, this enables one to send commands to the robot over local network wifi connection. 
Therefore;G code commands may be sent to the robot via a custom smart part designed on InventInside.
https://inventinside.com/editor/wuhtRXKpYCgmD436U6Th
Currently 4-axes control pad is implemented, more to come. 

https://www.duet3d.com/

How to build the robot for yourself:

The robot consists of 5 different parts. All parts should be printed using 0.8mm nozzle in vase mode using 0.4mm layer height. 
No top or bottom.

Exeptions:
Brackets - Single wall, 10% insfill, gyroid, connected walls, 0.5mm layer height. No top or bottom.

Material tested:
PTEG = GOOD, Gears on the motors skip, need something more stiff. Very good for brackets.

Body Brackets: (20-50g 1-2h ea)
(1x)A - lower bracket,  gap: motor_offset: [g min]
(1x)B - upper bracket,  gap: motor_offset: [g min]

(2x)Cup - [8g 15min]

Gears:
(2x)A - 50 tooth id:, t:   [35g 1h6min]
(2x)B - 40 tooth, id:, t: [19g 36min]
(4x)Motor Gear - 10 tooth, id:, t: [4g 5min]
(2x)Gear with shaft - 25 tooth id: od: length: [32g 58min]

Hardware:
Bearing, 3 sizes
Large - 4x
Medium - 4x
Small - 4x

Motors:
Nema-17x25mm (2x)
Nema-17x40mm (2x)

