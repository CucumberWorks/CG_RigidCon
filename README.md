# CG_RigidCon
A 3D-printable controller upgrade for the Contact Glove.

The design is inspired by but functionally different from the Magnetra controller. It reuses the existing electronics from the Contact Glove 1.0 set. 

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/GA6rscxaEAA5TjX.jpeg)

# Important: Before before you start
This project started as a very personal modification using the existing button and joystick components from the contact glove by diver-x.

Model based on the CAD files kindly offered by diver-x.

You are expected to heavily modify some of the components, although all modifications are designed to be modular and not destructive to the contact glove itself.

If you are not familiar with 3D printing or working with hardware in general, some of the steps might be challenging.

Using this controller will make certain gestures more difficult to perform. And I personally recommend remapping the trigger command to one of the three face buttons, and use the button next to the power switch as the system button.

Overall the project is still at a quite alpha state. 

# Before you start
You need a decent 3D printer. Most modern FDM machines will do. SLA printers will not work due to the use of threaded inserts and the fragility of resin. I printed the parts on a Prusa Mini and a A1 mini. Sufficient part cooling is required, as it will help with support removal. You only need PLA for these parts. Personal recomendation is PLA-CF. the carbon fiber reinforcement will further increase PLA's rigidity and help support removal easier. Use thick outerwalls(>4) for better strength. You may also use high infill(50%) to improve layer adhesion. 0.4mm nozzle for all parts but you can use 0.6mm for large structural components.

Heat inserts are used for threads. M3x3 and M3x5. Will probably move to locknuts.

Magnets are 4mm(D)x5mm(H) N52.

CA glue used to secure the magnets. Get a CA glue curing accelerator for a better experience. My personal recommendation is the Cyanon DW. High viscosity and easy to work with.

8mm elastic bands are used to help support the assembly even during active sessions.

# Instructions
## Step1
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/2103165752.png)
Recommended part layout.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/IMG_7847.jpeg)
Parts you need for this step.

You need 9 heat inserts and 8 magnets for this step.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/IMG_7849.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/IMG_7850.jpeg)

Make sure you insert the magnets at the right orientation. The swivel arm component should stick to the base component even without the screw installed.
For all 3mm through holes you may need to use a 3mm drill for clearance.
Use a M3x25 screw and a M3 heat insert installed on the SwivelArmBase for the swivel arm.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/IMG_7855.jpeg)
To intall the small Z-hinge component, apply a heat insert to the component itself, and another heat insert to the swivel arm. Use a M3x15 screw to secure it.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/base/IMG_7857.jpeg)
If all the joints spin freely and the swivel arm clicks magnetically to two positions, then you are good for step2. The two small plates are labeled with arrows and a dot. The plates are for grabbing onto the elastic bands and secured in place with 6 M3x8 screws. You do not need to tighten them at this point. Refer to the STEP file for a clearer 3D view of the assembly. 

## Step2
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/1077298468.png)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/224728256.png)
Recommended part layout.
Use 0.4mm nozzle and thick outer walls.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7878.jpeg)
Take the top cap, the mid frame and three button units.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7879.jpeg)
The three buttons first go into the top cap like shown.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7880.jpeg)
Press the mid frame into the top cap. You may need to apply some force as this is designed to be a tight fit.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7881.jpeg)
Harvest the button and joystick components from the original casing. There should be three PCBs. Careful not to lose the screws.
As the joystick module is in the same physical shape as the one used for the ROG Ally. You may use this chance to upgrade to a Hall effect joystick. The new joystick will have a higher stick and can be fitted with the newly designed larger joystick cap.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7882.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7883.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7885.jpeg)
Install the modules and the button assembly you put together previously. Secure the assembly with two M2x12 self tapping screws.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7886.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7887.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7888.jpeg)
Install the two magnets. Double check the polarities. The controller is designed to be stored in two positions, one fully folded and one rested at a temporary postion around the Z-hinge.
Use CA glue to secure the magnets.

## Step3
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7889.jpeg)
Due to the flipping mechanism, longer cables are required. The cable used for the button and joysticks are 4-pin and 5-pin JST 1.25mm connectors.
*Important* Pay attenstion to the cable order. The cable needs to be in the "Same Direction" configuration as shown in the image.
The recommended cable length is 30cm.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7890.jpeg)
Use a cable cover to protect the cables. I find soft fabric types to be the most confortable.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7891.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7892.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7893.jpeg)
![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7894.jpeg)
Connect the cables and secure the back cap with a M2x12 self tapping screw.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7895.jpeg)
Connect the cables to the Contact Glove main unit. You can refer to Diver-X's guides for more detail.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7896.jpeg)
Install the assembly to the main unit with two M2x8 screws. The original screws are a bit short so you need your own.
The assembly also prevents the tracker from flying out.

![alt text](https://github.com/CucumberWorks/CG_RigidCon/blob/main/img/instruction/controller/IMG_7897.jpeg)
Use the two small caps and six screws to secure two elastic bands. You can tighten the bands while wearing it and tighten the screws all the way when you are comfortable with the length. Cut any excess elastic bands. This should prevent the asssembly from detaching from the glove.

## Finish up
The steps only covers the leftside. The rightside is the same, only mirrored.
