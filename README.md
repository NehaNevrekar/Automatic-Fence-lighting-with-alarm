# Automatic-Fence-lighting-with-alarm
***

## **Problem Statement**
Automatic Fence Lighting with Alarm. The generic types of fence lighting circuits require high precision alignment. Design a sensitive automatic fence light Circuit using op-amp which can work within the line-of-sight to any light source like sunlight, electric light etc.


## **Introduction**
Light fence circuit is used to detect the presence of any human or object in a particular area. The detecting range of Light Fence Circuit is about 1.5 to 3 meters. It’s quite simple to design the circuit using LDR and Op-amp. This portable circuit can work smoothly with a commonly available 9V battery and the alarm sound generated from the buzzer is loud enough to detect the presence of a human, vehicle or object. This kind of security system can also built by using other sensors instead of using LDR, like:
|LIST OF EXAMPLES|
|-|
|1. PIR based Burglar Alarm Circuit |
|2. IR Based Security Alarm|
|3. Laser Security Alarm Circuit|
|4. Magnetic Door Alarm Circuit using Hall Sensor|


## **Components**
|LIST OF COMPONENTS|
|-|
|1. LM741 Op-amp IC|
|2. 555 timer IC|
|3. BC557 – PNP Transistor|
|4. LDR|
|5. Resistor (210, 1K, 5.7K, 100k, 1M)|
|7. Capacitor (0.1uf, 10uf)|
|8. Potentiometer – 100K|
|9. Buzzer|
|10. LED|
|11. Battery - 9V|
|11. Breadboard|


## **Circuit Diagram**



## **Working**
The op-amp IC is used as a voltage comparator and the 555 timer IC is placed in an astable mode. The LDR and the potentiometer are creating a voltage divider circuit. The output of this divider circuit will change according to the intensity of light falls on the LDR. The divider is connected to the inverting pin of the Op-amp IC. The non-inverting pin is connected with supply through a 5.7Kohm resistor, so the voltage value at the non-inverting is fix. You can replace this resistor with a 10K potentiometer to adjust the voltage as per the requirement. We can adjust the sensitivity of the device by using the potentiometer VR1 connected in series with the LDR. When the voltage at non-inverting input is greater than or equal to the reference voltage the output (at pin 6) of the op-amp IC output (PIN 6) goes HIGH. Learn more about working of op-amp by following the various op-amp based circuits.


## **Result And Conclusion**
According to the circuit diagram, when LDR detects any activity the output of the Op-amp IC goes LOW, and PNP transistor T1 start conducting. Hence, the LED starts glowing and the 555 timer IC get triggered. Here, 555 timer IC is in Astable mode and a preset time delay is provided by R3, R5 and C1. So whenever some person or object enters in prohibited area, his shadows will be sensed by the LDR and the circuit triggers the alarm.






