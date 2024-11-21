# Embedded-Project

This project is about Electric Vechicle Safety System using STM32 Board. The main components of this project are STM32F board, temperature and humidity sensor,buzzer,Led,Switch and lcd display.We all have got a huge impact about the electric vehicles which are used to reduce the amount of carbon emission. But the major issue in that is there are many cases of bike explosion on catching fire. 

In order to prevent this problem, we have devised a idea using the embedded systems. The project works on the basis starting by first the STM32F board which is the main component which is used to connect all other devices and program it using C -Programming.The temperature and humidity sensor is used to detect the temperature and humidity level in the bike and it will send these information to the stm32f board to which it was connected.There is also a LCD connected to this system which is used to display the temperature and humidity values so that the person driving can also able to know about the values. The program work on the logic where whenever the humidity value raises over certain value ,then the LED which is connected will glow indicating about the rise in the humidity. Similary if the temperature value raises over certain degree then the buzzer gets alarmed . There is also a emergency switch connected to this system, So if the above cases happen then the person who is driving can press the emergency switch so that the vechicle gets stopped Immediately.

Looking about the techinical part of it,The LCD works on the principle of I2C(Inter Integrated Circuit) protocol, the emergency switch works as a interrupt on the principle of NVIC(Nested Vector Interrupt Controller)
and the other components are connected on the basic logic of connection.

This project was done by a team of 4 consisting of Abishek K, Vedha Vishal,Dasari Vishal and Vishwanth

Canva Video Link -> https://www.canva.com/design/DAGWcRPNhEo/oxRbVioTL9k2HqF2vNA5-g/watch?utm_content=DAGWcRPNhEo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hc01963dfe4
