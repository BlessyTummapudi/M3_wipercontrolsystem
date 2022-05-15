# Wiper control report

## Introduction:
A wiper is a vital component that removes rainfall or any other liquid from the windscreen of a vehicle. The previous method required manual wiper activation, and raising the wiper was a tough task. As a result, this system is being presented as a solution to these problems. The project's goals are to supply wiping systems for older automobiles, improve the system by using actuators and pull switches (using the same switch for various functions by stepwise switching), and manage engine and wiper speed with a single switch. This System regulates the wiper's operation speed in response to the amount of rain. This Wiper Speed Control System is utilised in all sorts of automobiles, and its primary function is to remove rain air drops from the vehicle's front screen.
Wipers may be powered by a variety of means, although most in use today are powered by an electric motor through a series of mechanical components, typically two 4-bar linkages in series or parallel.

On some vehicles, a windscreen washer system is also used to improve and expand the function of the wiper(s) to dry or icy conditions. This system sprays water, or an antifreeze window washer fluid, at the windscreen using several well-positioned nozzles. This system helps remove dirt or dust from the windscreen when it is used in concert with the wiper blades.
Vehicles with air-operated brakes sometimes use pneumatic wipers, powered by tapping a small amount of pressurized air from the brake system to a small air operated motor mounted on or just above the windscreen. These wipers are activated by opening a valve which allows pressurized air to enter the motor.

Early wipers were often driven by a vacuum motor powered by manifold vacuum. This had the drawback that manifold vacuum varies depending on throttle position, and is almost non-existent under wide-open throttle, when the wipers would slow down or even stop. That problem was overcome somewhat by using a combined fuel/vacuum booster pump.

 # 4W's and 1H
 ## Who
 Who is driving or controlling the car
 ## What
 wiper control system 
 ## When
 When the weather condition is bad (like in rain and snow) the wiper is activate and clean the car window
 ## Where
 Inside and out side the car
 
# High Level Requirements

|ID	|Description|	Category	|Status|
|---|---|---|---|
|HR1	|Can be able to keep the windscreen clean	|Technical|	Implemented|
|HR2	|Can be able to windshield wipers clear the windshield of rain and snow	|Technical	|Implemented|
|HR3	|Can be able to improve headlight visibility at night|	Technical|	Implemented|
|HR4|	Can be able to driver to have a clear view|	Technical	|Implemented|

# Low Level Requirements

|ID	|Description	|Status (Implemented/Future)|
|---|---|---|
|LR1	|Driver can be able see the windscreen clean|		IMPLEMENTED|
|LR2	|Same operation for windshield wipers clear the windshield of rain and snow |IMPLEMENTED|
|LR3	|Same operation for improve headlight visibility at night|	IMPLEMENTED|
|LR4	|Same operation for driver to have a clear view|	IMPLEMENTED|

# SWOT Analysis

### Strengths:

  1.No human interaction with car
  
  2.Manages all commands with one key automatically
  
### Weaknesses:
  
  1.Unable to monitor status of car
  
  2.Range is limited

  3.Wait for certain time after every command to press new command
  
### Opportunities:

   1.The Scope of this sytem is huge in automation or car control

   2.Less cost
   
   3.Changing lifesytle.
  
### Threats:

  1.When new command is given without completing the current command it will not take current command
  
  2.Rising competition.
  
###  Features:

  1.When the button is pressed once the car will start (Ignition key postion at ACC)
  2.When the button is pressed again the wiper will start(Wiper On)
  3.When the button is pressed again the wiper will off(Wiper Off)
  4.When the button is pressed thrice the car will stop(Ignition key position at Lock)
### Block Diagram
  ![pic](https://github.com/BlessyTummapudi/M3_wipercontrolsystem/blob/main/2_Design/BLOCK%20DIAGRAM.png)
  
  
### Structural diagram
 ![pic](https://github.com/BlessyTummapudi/M3_wipercontrolsystem/blob/main/2_Design/Structural%20Diagram.png)
 
 ### Behavioral diagram
 ![pic](https://github.com/BlessyTummapudi/M3_wipercontrolsystem/blob/main/2_Design/behavioral%20diagram.png)
 
 
 ## High level test plan


|TestID|	Description|	Exp.i/p	|Exp.o/p|	Actual o/p|	Status|
|---|---|---|---|---|---|
|H1	|check if the BUTTTON is pressed|	Program execution|	MicrocontrollerEngine starts| LED ON(RED)	|PASS|
|H2 | check if the BUTTTON is pressed|	Program execution	|WIPER starts| LED ON(BLUE)|	PASS|
|H3	|check if the BUTTTON is pressed|	Program execution|	WIPER starts	| LED ON(GREEN)	|PASS|
H4	|check if the BUTTTON is pressed	|Program execution	|WIPER starts	| LED ON(ORANGE)	|PASS|
H5|	check if the BUTTTON is pressed	|Program execution |	Microcontroller/Engine stops|	LED TURNED OFF	|PASS|


## Low level test plan

|TestID|	Description	|Exp.i/p|	Exp.o/p|	Actual o/p|	Status|
|----|----|----|----|----|----|
|L1	|check if the BUTTTON is pressed	|Program execution|	MicrocontrollerEngine starts| LED ON(RED)|	PASS|
|L2|	check if the BUTTTON is pressed	|Program execution|	WIPER starts|LED ON(BLUE)|	PASS|
|L3|	check if the BUTTTON is pressed|	Program execution	|WIPER starts	| LED ON(GREEN)|	PASS|
|L4	|check if the BUTTTON is pressed	|Program execution|	WIPER starts	| LED ON(ORANGE)|	PASS|
|L5|	check if the BUTTTON is pressed|Program execution|	Microcontroller/Engine stops|	LED TURNED OFF|	PASS|


## Advantages
* Power usage is reduced.
* The operating premise is simple. The setup is straightforward.
* By offering an On/Off switch, it is possible to run manually or automatically.
* Because conductive sensors are used, sensor costs are very inexpensive.
* Free from wear adjustment.


## Applications
* It's found in four-wheelers.
* It's utilised in planes.
* It's found in six-wheelers.
* It is used in trains.
 
  
