Ideation of the project "Wireless doorbell":

The project description: [Wireless doorbell](https://github.com/Snehan2k2/Tasks/blob/master/Arduino%20in%20complex%20circuits/Wireless%20Doorbell.md)

**Problem statement**:
When the button on the transmitter side is pressed , the buzzer on the reciever side is turned on wirelessly.

**Ideation phase:**

Button => HT-12E Encoder IC => RF transmitter => RF receiver => HT-12D Decoder => Arduino => buzzer

| **Part of the pathway** | **Feasibility** | **Advantages** | **Disadvantages** |
|---|---|---|--|
| Button | These are switches | Cheap | A complex microcontroller can get things get hard |
| HT-12E Encoder IC | It is used for RF communication | They are cheap and are of small size | They function at low voltage |
| RF communication | Usually hard | The programming would be very easy | Dedicated ratio equipment is needed |
| HT-12D Decoder IC | It is used for RF communication | Lower power consumption | Quite delicate in handling |
| Arduino | Usually hard, unless very skilled and experienced | Very cheap and easily programmable if one can identify what to do | Hard for beginners | 
| Buzzer | They are easily available | It can produce sounds of different frequency | It cannot produce sounds with DC signal |

*Choosing a pipeline*:

From the above pathway, we choose the RF communication part. Instead of RF communication, we can use HC-05 buletooth module and connect it to the Arduino board.

**Prototyping phase**: Here, we build the product in this phase and test and debug it.
