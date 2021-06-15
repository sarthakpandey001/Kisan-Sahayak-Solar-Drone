# Kisan-Sahayak-Solar-Drone

This Projected is implemented under the Unnat Bharat Abhiyaan with an aim to provide drones for farming purposes at reasonable costs.

## Tools/Specifications:

1. Size of drone 1.5 m (diagonal)
2. Carbon fiber Arm
3. 3D printing use
4. Design based on reducing sloshing effect on Pesticide tank.
5. Propeller blades material- ABS plastic
6. 2 GPS sensor
7. Software to control and automatic
8. Pesticides nozzle on all 4 legs
9. A compressor pump (to send liquid to the nozzle).

## Why do we select 4 rotors?

* After estimating the weight, we decided “Not to use Wing included aircrafts” because both wing and stabilizers increase unnecessary weight, leading to lesser battery life.

* Bicopters are unstable in the Longitudinal direction i.e in the direction of the fuselage, based on this, solve this by opting for a swashplate mechanism as the control of rotors but it would complex the system. Bicopter UAVs task performance is also quite lower than that of Quadcopters and Hexacopters so we discluded the Bicopter.

* Quadcopters are mostly used UAVs, they have better “Controllability, Power Efficiency, Maneuverability, Ease of Payload packaging”. So, we selected 4 rotors, as we increase the number of rotors the stability gets increased but at the same time maneuverability decreases. In our project, we need More maneuverability. 


## Time difference b/w manual and drone

![image](https://github.com/sarthakpandey001/Kisan-Sahayak-Solar-Drone/blob/master/img/pesticide.jpg)

Humans can cover 0.65 acres manually in 8 hours while Drone(UAV) can cover 1.33 acres in 1 hour.



| |Manual |Drone  |
|----- |----- |----- |
|Size of field (in acre) |1  |1  |
|Time required (in hrs)|12.3 |.16 |
|Cost per hour (is rs)|37.5 |500 |
|Total cost (in Rs)|461 |80 |

The increased efficiency of work is (738.5-45)/738.5 = 94%.

The cost-saving per acre land on drone usage is 461-80=381 and the percentage saving is 381/461*100 = 82.6%

## How to use a solar panel?

```Battery Discharge Rate = Capacity (Ah) * C-rate ```

For a 4S14.8 V lipo cell with nominal voltage 3.7V.

Capacity: 1300 mAh=1.3Ah

120 C battery

`Discharge rate: 1.3 * 120 = 156 Ah`

## Compressor select criterion:
Compressor is selected mainly on the basis of Flow rate, type of fluid, suction pressure, temperature and discharge pressure

The required quantity for different pesticides are:

![image](https://github.com/sarthakpandey001/Kisan-Sahayak-Solar-Drone/blob/master/img/pesticide.jpg)

On average, we get the required amount of pesticide per acre = 400ml/acre.

Now our drone covers 1 acre in .16 hrs.

So the required flow rate = 400/.16 ml/hr=2.5 litre/ hr= .69ml/sec

## Aero vs non-aero:
We thought of 2 main ideas regarding Solar drones. One was to make our drone in an aerodynamic shape and fit the solar panel 
on the wing and the other one was to make our drone simpler and lighter and fit the solar panel on the top.
   
For shortlisting One from these two types we have gone through the following advantages and disadvantages and accordingly,
we have shortlisted the one which is convenient to us.

## Aerodynamic Shape:
     
### Advantages:
- Extra lift is produced by the wing.
- Less Drage
- More surface area available forfeiting the panel

### Disadvantages:
-  As mentioned in Advantages, that extra lift will be produced by the wing but it is at a higher speed but in our case, the drone won’t fly at higher speeds.
- To make a wing-like structure we have to make a tail to overcome the pitch down moment at Positive AOA. otherwise, we have to control it with  our rotors which may be tough for Farmers and require more practice.
- The transition phase of the rotor from vertical to horizontal axis is more difficult because during this process, the net thrust vector will come, and our drone may get unstable. Proper coding and proper controls are required.
Heavyweight, so we need to produce more downward force to lift u, resulting in more power consumption.

So, According to the above advantages and disadvantages we can see for our application a simpler drone with low weight is more convenient.




