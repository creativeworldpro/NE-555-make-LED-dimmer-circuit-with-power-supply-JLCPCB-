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


Circuit Connection  - Step 1

To make this LED blinker light, we need to connect 2no and 6no leg of timer IC and connect 4no and 8no leg of timer IC.
Now we connect 2.2µf/50v capacitor with the timer IC. We connect it’s negative leg with 1no leg of timer IC and then connect it’s positive leg with 2no leg of timer IC.

We utilize JLCPCB https://jlcpcb.com/RTA to printout our PCB.


Circuit Connection – Step 2

Now we connect resistor with the timer IC. To make this circuit, we are using 10k and 20k resistor. Connect 10k resistor with 8no leg of timer IC and connect 20k resistor with 6no leg of timer IC.  

Then connect empty terminal of 10k &20k resistor with each other. We are using 8 led light to make this circuit. We make parallel connection in these 8 led lights.


Circuit Connection – Step 3

Now we need to connect multilayer ceramic disc capacitor (103) with the timer IC. We connect its one terminal with 5no leg of timer IC and its other terminal with negative leg of LED light.

To make this led blinking light we need DC-3.7v power supply. We make a bridge power supply circuit.

Thanks to JLCPCB for offering us, this SMT PCB circuit.

Circuit Connection – Step 4

We know that, there are two polarity terminal of a diode. To make this bridge connection, we connect two diode negative terminal and connect two diode positive terminal with the circuit. Then connect, two set diode positive leg with another diode negative leg and connect other terminal with the circuit. It’s a complete bridge connection.

To filter voltage, we need to use a capacitor with the circuit. We are using 1000µf/ 25v capacitor with this circuit. We connect capacitor negative leg with diode negative leg and connect capacitor positive leg with diode positive leg.


Circuit Connection – Step 5

For indicator, now we connect resistor and LED with the circuit. We are using 1k resistor to make this circuit. We connect resistor with capacitor positive leg and connect LED positive leg with resistor.

Then connect LED negative leg with positive & negative leg of diode.

For power source we are using 12v transformer. If we want to make 15v power supply, for that we need to connect 15v transformer. Now we connect transformer secondary section with the circuit. We connect secondary section cable with diode positive and negative leg.


Circuit Connection – Step 6

You know that, we use a voltage regulating IC LA7803. From this power supply, we connect output with this voltage regulating IC.
We connect voltage regulator “voltage out” leg with 8no leg of timer IC and connect timer IC “GND” leg with LED negative leg and 1no leg of timer IC.

Our circuit is now completely ready for use. Just plug-in power and enjoy the effect of led blinking light.


Steps to Order PCBs from JLCPCB - 

If you complete design of your PCBs, then it is time to order PCBs. To order best quality PCBs, just visit JLCPCB and click on the “QUOTE NOW” button.

Since 2006, JLCPCB continuously driven to become more efficient and to reduce costs. They promise to offer customers the most economic PCBs forever. JLCPCB makes cheapest but top quality PCBs possibly because of scale effect, extremely high production efficiency and less manpower cost.

You can order minimum 5 pieces PCBs for only $2 costs.

To order PCBs, make your Gerber file. Then drag and drop the Gerber file on the following box.
Click on “Gerber Viewer” button you can check the PCBs design. Make sure everything is good, then choose color, quantity and order your PCBs at very reasonable prices.

If you are a new user, then you can order 10 pieces PCBs, costing only $2. To place your order click on “Save to Cart” button. Confirm your shipping address and shipping method.


Steps to Order SMT PCBs From JLCPCB -

•	To order your SMT PCBs, visit JLCPCB.

•	 Drag and drop SMT PCBs file on site.

•	 Choose your PCBs color and quantity.

•	 To free SMT assembly for your PCB click on “SMT Assembly” button and then confirm.

•	 Add your Bom file and CPL file.

•	 Place your order click on “Save to Cart” button.

•	 Confirm your shipping address and shipping method.

•	 Pay your payment

•	 Wait for confirmation mail.

•	 For SMT Service, Click here - https://jlcpcb.com/smt-assembly


 Shipping and Billing -
 
 JLCPCB supported all shipping method can be seen below.
 
Estimated Delivery Time - 

•	DHL International Express 3-5 business days

•	UPS Worldwide Saver 3-6 business days

•	S.F Express(Standard) 5-8 business days

•	S.F Express(Economy) 8-15 business days

•	Singapore EMS 8-15 business days

•	PostLink Registered Mail 15-20 business days

•	ePacket 15-25 business days

•	Registered Air Mail 15-20 business days
		

JLCPCB supported Payment method - 

•	PayPal

•	Credit/Debit Care

•	Prepaid wire transfer


Confirm PCBs Order - 

To confirm your order, pay your payment. Then accept PayPal, Credit/Debit Card, Prepaid Wire Transfer. To manufactured your PCBs, it’ll takes about 2 days. DHL will be fastest shipping method to arrive your ordered PCBs at your location.

All PCBs were well packed and quality was really good.

Thanks to JLCPCB for best quality PCBs.




