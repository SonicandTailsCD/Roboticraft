# Roboticraft
DomAmato/Roboticraft remake from the ground up! I still think creator's dead :P

## Information
The robot inside this Java mod is programmed through Python. This _should_ be installed in your OS :)
Using Windows? I've got you covered. Once you load up the mod, Forge *should* download a portable mini-Python executable stored within your Minecraft folder.

### This mod requires you to install Rabbit GUI client-side.
Unfortunately, I'm not currently focused on Rabbit GUI and I'm already upgrading the mod to 1.18.2, so for now, at least for the 1.12.2 version, download it from [here](https://github.com/CityOfLearning/rabbit-gui/releases/download/1.12.2.1/rabbit-gui.jar)!

## Items and crafting 
To keep the game interesting and fun, I'll still merge previous Survival methods to obtain the robot in my recode. Here's all you need to know:

### Expansion Chips
* Attack Chip

   Allows the robot to attack entities assuming it has a sword equipped. An entity ID must be passed as an argument and really the best way to find those is using the detection chip

![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/attack.png "Attack Chip")

* Build Chip

   Enables the robot to build using material from its inventory, will use it in order of slot unless specified which block to use.
   

![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/build.png "Build Chip")

* Climb Chip

   Enables the robot to climb ladders and vines. Will also climb steps 1 block high although the new walk processor also allows the robot to do that without explicitly telling it to.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/climb.png "Climbing Chip")

* Detection Chip

   Enables the robot to detect nearby entities and returns a list of all that were found. Can be enchanded with the power enchantment to increase the range by 10 per level. Works really well with the attacking chip or as a sentry that can chat with the player.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/detection.png "Detection Chip")

* Inspection Chip

   Enables the robot to inspect the surrounding blocks returning the type found at that location. Really useful for pathing and mining.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/inspection.png "Inspection Chip")

* Interaction Chip

   Gives the robot the ability to interact with simple redstone components, buttons, levers, doors, trapdoors. 
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/interact.png "Interaction Chip")

* Jump Chip (removing, as that's dumb. Your robot can jump without a chip. :) )


* Mining Chip

   What kind of robot in Minecraft would not have the ability to mine blocks? As long as it has inventory space blocks will go into the inventory, after that it will just drop them on the ground.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/mining.png "Mining Chip")

### Other Items
* Remote

   The remote is the most important part of interacting with the robots, it is needed to activate them and get to the programming screen.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/remote.png "Robot Remote")

* Redstone Sensor

  Equipping this sensor will allow the robot to detect (feel) redstone signals. When a redstone signal is detected, the robot can execute the code currently saved on its equipped SD card.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/meter.png "Redstone Meter")

* RAM

   Because Steve's a cheapass, the robot only has a bit of memory. You can expand the number of lines that can be processed by adding more RAM.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/ram.png "RAM")

* Robot

   I have no plans to make the robot spawn naturally in the world. Sorry, but it must be crafted and activated.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/robot_block.png "Robot")


* SD Card

   You can save your program to these SD cards, it will write the code to your computer and is also an exchangable item. Want to share your program with someone else? Save it to a card and give it to another player and the program will transfer over to them too.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/sd_card.png "SD Card")


* SIM Card

   Using your remote you can connect to robots within a 64 block area. Need to communicate with robots in different dimensions or over great distances? It's under development, but we'll see if I can add a *mobile* SIM card. (You're lucky to be here early. I'll spoil something - I'm gonna add 2 different kinds of SIM cards. Mobile and Landline. And if you put a landline SIM in a robot... I'm gonna make it so the company comes for you and kills you. :P)
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/sim_card.png "SIM Card")

* Wrench

   Robots (at least these) are pretty strong (yet are fragile), they are mostly immune to players attacks. Need to remove a robot you own? You will need a wrench.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/wrench.png "Wrench")

* Robot API Manual

   Need some help remembering how the API works? Make a manual for reference.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/manual.png "Robot API Manual")
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/gui/manual2.png "Robot API Manual")

* Magnet Block

   Warp over nearby robots to this block facing the set direction. Useful for setting inital starting direction and position.
   
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/magnet.png "Magnet Block")

**Reminder**: This mod (for now at least) WILL NOT WORK without Rabbit GUI. Download it already!

### Interfaces
You'll need to give your robot a name. Don't care? Good luck remembering numbers!
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/gui/activate.png "Activation Gui")

The robot will have an inventory. Why not? :P
![alt text](https://github.com/CityOfLearning/Robot/blob/master/images/gui/inventory.png "Robots Inventory")

This is the biggest component of this mod. 
Dom Amato included a native IDE to program your robot. INSIDE MINECRAFT. I'm doing that too, making it better. Credits to him for an amazing mod, so sad he (seems to be) is dead :skull:

Pulls always welcome, and I'll be overjoyed if you can post to YouTube about the mod. I don't give a care if it's a negative or positive review - I'll just be happy that I can correct whatever issues you have. :D
