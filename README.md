The article is being published in collaboration with JLCPCB. They supply high quality PCBs at a very reasonable price. They also can provide SMT circuit assembly.


We thanks to our sponsor JLCPCB https://jlcpcb.com/RTA for sponsoring us PCBs for this project circuit.

Thanks To JLCPCB.

$2 for 1-4 Layer PCBs.

Get SMT Coupons: https://jlcpcb.com/RTA


In this project, we’ll teach you making a LED dimmer light circuit. An LED, also known as a light emitting diode, can be made to blink. Not only can the LED be made to blink manually, but it can also be made to blink by itself. Regardless of the method you choose to make your LED blink, you will need other electronic components to make the LED blink. For simple designs, all you will need is a manual switch.

There are several ways of making a blinking LED circuit. You can make one using relays. This primary flasher circuit generally relies on a few components to achieve blinking.


Applications and Uses - 

•	Decorative Pieces
•	Toys
•	Advertisement Hoardings
•	Visual Sign Indications



To make this wireless power transfer circuit, we might need some electronics component.

All components list have been given below –

Component List – 

•	Timer IC – NE 555

•	Resistor – 1  KΩ
             10 KΩ
 		         20 KΩ
•	LED – 9 Pieces

•	Diode – 1N 4007 (4 Pieces)

•	Linear voltage regulating IC - 7803

•	Multilayer Ceramic Disc Capacitor (103)

•	Capacitor - 1000µf/ 25v

2.2 µf/ 50v

•	Power Source – DC 3.7 volt


NE555 Pin Out - 


Pin 1

It is the ground pin directly connected to the negative rail. It should not be connected using a resistor, because all the semiconductors inside the IC will heat up due to stray voltage accumulating in it.


Pin 2

It is the Trigger pin to activate the IC’s timing cycle. It is generally low signal pin and the timer is triggered when voltage on this pin is below one third of the supply voltage. The trigger pin is connected to the Inverting input of the comparator inside the IC and accepts negative signals. The current required for triggering is 0.5 uA for a period of 0.1uS.The triggering voltage maybe 1.67 V if the supply voltage is 5V and 5 V if the supply voltage is 15V. The triggering circuit inside the IC is too sensitive so that the IC will show false triggering due to noise in the surroundings. It requires a pull up connection to avoid false triggering.


Pin 3

It is the output pin. When the IC triggers via pin 2, the output pin goes high depending on the duration of the timing cycle. It can either sink or source current which is at maximum 200mA. For logic zero output, it is sinking current with voltage slightly greater than zero. For logic high output, it is sourcing current with the output voltage slightly lesser than Vcc.


Pin 4

It is the reset pin. It should be connected to the positive rail to work the IC properly. When this pin is grounded, the IC will stop working. The reset voltage required for this pin should be 0.7 volts at a current of 0.1mA.


Pin 5

Control pin – The 2/3 supply voltage point on the terminal voltage divider is brought to the control pin. It requires to be connected to an external DC signal to modify the timing cycle. When not in use, it should be connected to the ground through a 0.01uF capacitor; otherwise the IC will show erratic responses


Pin 6

It is the Threshold pin. The timing cycle is completed when voltage on this pin is equal to or greater than two-third of Vcc. It is connected to the non inverting input of the upper comparator so that it accepts the positive going pulse to complete the timing cycle. Typical threshold current is 0.1 mA as in the case of Reset pin. The time width of this pulse should be equal or greater than 0.1uS.


Pin 7

Discharge pin. It provides a discharge path for the timing capacitor through the collector of the NPN transistor, to which it is connected. The maximum allowable discharging current should be less than 50 mA otherwise the transistor may damage. It can be also used as an open collector output.


Pin 8

It is positive rail connected pin which is connected to positive terminal of the power supply. It is also known as Vcc.  IC555 works in a wide range of voltage from 5V to 18 V DC where as the CMOS version 7555 works with 3 Volts.


Feature of NE555 timer - 

•	Timers
•	To provide time delays
•	Pulse generation
•	To toggle between high and low states
•	Oscillator applications.
•	Wide range of power supply (5-18)V
•	Sinking High current output (200mA of load current)
•	Variable duty cycle
•	Logic compatible trigger and reset inputs
•	High-temperature stability
•	The operating power supply range is from 5 Volts to 18 Volts.
•	It can drive TTL as its output current is high.
•	It has a capability of sourcing or sinking up to 200mA current
•	Trigger and reset inputs are logic compatible.
•	It has an adjustable duty cycle
•	It has two outputs which are normally on and normally off.
•	Turn off time is less than 2µ


