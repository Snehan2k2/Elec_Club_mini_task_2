Ideation of the project "Water level controller":

The project description: [Water level controller](https://github.com/Snehan2k2/Tasks/blob/master/Arduino%20in%20complex%20circuits/Water%20level%20controller.md)

**Problem statement**:
The aim is to switch the motor ON when the level of the water drops below certain point, and to switch off the motor when the tank becomes full. If the level in side the sump tank is low, the motor will not be switched ON and a beep sound is generated when the level in the sump tank is low.
Also, the data regarding the quantity of water is displayed on the internet.

**Ideation phase**:

Aluminium wire => Analog pins on Arduino => Buzzer, LCD display, Motor

| **Part of the pathway** | **Feasibility** | **Advantages** | **Disadvantages** |
|---|---|---|--|
| Aluminium wires | Aluminium is a good conductor of electricity | They are light in weight and have the same conductivity as copper | It is prone to fire hazards |
| Arduino | Usually hard, unless very skilled and experienced | Very cheap and easily programmable if one can identify what to do | Hard for beginners | 
| Buzzer | They are easily available | It can produce sounds of different frequency | It cannot produce sounds with DC signal |
| Motor | Easy to control | Because of low level control, we can customize it further | It costs more compared to the other ones |
| LCD display | Easy to display | It is very compact, thin, and light | It consumes a lot of electricity which produces a lot of heat |

*Choosing a pipeline*:

From the above pathway, we choose Arduino part of the pathway. We replace Arduino with ESP-32. The advantages being ESP-32 being cheaper than the Arduino. With the help of IoT, ESP-32 helps us to display information regarding the quantity of water in the internet.

**Prototyping phase:**
Here, we build the product in this phase and test and debug it.


