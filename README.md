# Arduino-Bluetooth-Car

## Arduino Car controlled by Labview
In this project We are going to learn how to build an Arduino Car Controlled by Labview from USB or Bluetooth. The components and materials are commom for makers and you will not have problem to find them.

## MAIN FEAUTURES
- Arduino Compatible ( You can used Model Uno, Mega, Due, Nano or others)
- Drivers in a board shield with borners ready to connect and work.
- HMI control with Labview.
- Power supply from 6 - 12 Volts
- Powerful control screen fast connection by USB
- Shield board with H brigde L293D
- Common components, very easy to find in our local electronic store.

## CAR  KIT REVIEW
The following tutorial is for this model of car that you can see below, with 2 DC motors, this model is small and practical, kind remind you that 2 DC motors need a separate power source, also you should consider that in your projects; for example if we use the car with 4 motors, our power supply will have to be of a hight capacity.

## SCHEMATIC DIAGRAM
The schematic diagram is very simple and flexible. First at all We use an Arduino Uno Board, but you can use another one with the same pinout like Arduino Mega, Due, Leonardo or others.
The schematic of the shield is attached in this tutorial, Basically we have to consider that We are working with DC motor which are the two wheels. I order to control the DC motors rotation We need an extra drive in this case the L293D which is very popular and well know. So I am leaving the connections that you should follow.

## PCB LAYOUT
Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing, believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger, so in this case We are going to use Proteus highly recommended if you want to enter in the pcb desing world like a professional. So after We finished and check our schematic circuit We need to switch from schematic to PCB layout. We can see the PCB with the Ground Plane, this helps for noise filter on the pcb.
Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, in some software we can get both GerberX2 and Gerber (In the case of Proteus).

## 3D MODEL
One of the features of Proteus is the 3D visualization, the 3d visualization is important and it give us the posibility to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions. Before I did not consider this feature so important at all, but the 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake, it does not matter if your components are SMT or PTH (small or big), it is always better to see that every component will fit correctly.
► Also very important to remember, if you are going to add 3d models, be carefull that you add in the Step AP214 format, the others extensions and formats can not work correctly.

## PCB MANUFACTURE
Once we finished our development board; it is time to bring it to life. In order to manufacture our board, We are going to use JLCPB Services.In case that you do not have an account yet, check out the bellow link►JLCPCB: https://jlcpcb.com/IAT
Also kind advice you to use JLCPCB services in order to Make and assembly your PCB board.
### Currently there is a special offer for new users:
### New users can get $30 coupons;
### Register : https://jlcpcb.com/PCW
