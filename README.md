# Project-DIY-Ventilator- ![icon](https://img.icons8.com/color/48/000000/patient-oxygen-mask.png "icon")

An Open-source ventilator which can be reproduced with easily available components.This ventilator can supply uninterrupted mechanical ventilation for patients.This device is compatible with Ambu bag / self inflating bag

![Prototype](https://raw.githubusercontent.com/Mayoogh/Project-DIY-Ventilator/master/Reference%20Photos/Render1.png)

According to my calculation, a single prototype can be produced within 90 minutes (1.5 Hrs).
Here is the breakdown of time 
+ The required laser cut pieces and 3D printed parts require a minimum of 1 hour (if printed on multiple machine)
+ The assembly of the remaining parts can be done under 20-30 minutes. 

This prototype uses 2 **Nema17 stepper motor** (can be replaced using **servo** or even **normal dc motor**, depending upon the availability). Both motors are placed facing opposite to each other. The shaft of both motors is attached to a **rack and pinion mechanism** with a compressing **Arm Block** fixed to the end of both rack. Which compresses the 2 Arm Block when the motor is rotated in the opposite direction. An **self inflating bag** or **ambu bag** is placed in between the 2 Arm Block. So when the 2 block comes closser the bag will compress and act as mechanical ventilation and the cycle continues till the pre defined time.

![Prototype](https://raw.githubusercontent.com/Mayoogh/Project-DIY-Ventilator/master/Reference%20Photos/Snapshot%201.png)

## The Main Features of this prototype
 + Users can set the `duration` and `speed` of the compression and expansion cycle separately. [Under Progress]
 + Monitoring the status of the cycle on an LCD display.
 + Limit switch is placed on both sides of the arm to get proper feedback of each cycle.
 + If the Limit switch is not triggered it will alert the user with a buzzer, regarding the issue.
 
 ### Things to do
 - [x] Create the working simulation
 - [ ] Start on prototype development 
 - [ ] Progamming
 
 ### Resources 

+ http://oedk.rice.edu/apollobvm
+ CAD Models
   - Ambu bag : https://grabcad.com/library/ambubag-bag-valve-mask-1
   - Nema17   : https://grabcad.com/library/nema17-stepper-motor-5
   - Endstop  : https://grabcad.com/library/limit-switch-10t85-gsfy-10-1
   

**There can be lots of improvement made on this, looking for good contributions to make it better and more feasible**
