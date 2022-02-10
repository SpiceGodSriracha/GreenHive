# BoxGarden
## _Design Doc_

1. Layout
2. Pot Design
3. Housing Material
2. Electrical Components
3. Potential Features

---
# Layout

For the layout it was decided that the side mount was overall the best. It allows for optimal vertical space use, easy access to the electronics if needed. Front and rear access for power and status designing.

![Basic Design Draft](/DesignStage/Assets/BasicDesign.png "Basic Design")

The rough draft design was seperated into 3 primary sections
1. Electronics box
2. LED hood
3. Water Basin

The electronics box is seperated from the water basic portion by a leg of the LED hood to prevent water crossover. Not too much else to say layout wise for this. Its simple.

---
# Pot design
![PotDesign](/DesignStage/Assets/Pot.png "Pot")

The base portion of the pot in a rough sense is very simple. Outside of the air pump, the bottom portion has little to no complexity.
##### BUT
There is a lid, and since it is a hydroponic garden, there is also lid variation. Since this overall design is very adaptable, the lids are simple panels with slots cut into them, to inset various sizes of cups/pods.
![Lids](/DesignStage/Assets/LidConcept.png "lids")

---
# Housing Material

I'll be looking at a few materials, and just judging them on their performance for each section.

### Wood
#### Pot
Not optimal, would look nice, but require epoxy most likely to guarentee water proof.
#### LED Hood
Not bad actually, heat may be an issue but with 20-60W LEDs it may not be an issue. 
#### Electronics box
Would look very nice, not many safety issues if made well, but might be a pain to assemble.

### Metal
#### Pot
Would require water resistant metal sheet and welding to be cost viable. 0/10
#### LED Hood
Okay but overkill.Heat dissapation is a plus, potential need to weld is not.
#### Electronics box
No.

### Acrylic
#### Pot
For the LIDs, its a no brainer yes. For the basin, while it would work, it would be a pain to assemble unless thicker acrylic is used. Potentially though.
#### LED Hood
Okay but boring. Would have to be thicker for stability.
#### Electronics box
Not bad, but a bitch to assemble.

### Concrete
#### Everything
It is expensive, but nice I guess. Water proofing isn't too hard, but just overkill again.

### Full Epoxy
#### Everything
It works, look has wide range, but god would it be costly AF. No

### 3d Printed
#### Pot
Okay, just might be a bit thin + water proofing would be a concern
#### LED Hood
Too much work for so little, but it can work.
#### Electronics box
Probably optimal, can easily get standoffs, sections and holes pre set.

## Material concensus

### Pot
Wood or thick acrylic would be best. Cut, nailed, edges fully sealed internally and then sealer on the wood. (Epoxy or whatever)

### LED Hood
Wood or acrylic. Both work but wood is cheaper.
### Electronics box
3d printed or wood are my picks. Wood looks nice and isn't too costly, but may be a pain, where as 3d printing is much more flexible.

---
# Electrical components

## The controller
For the controller there are 2 main schools, Single Board Computers or an MCU. For each, I have one in mind. Overall its a choice of feature set, so this will depend on those.

### Raspberry pi
#### Pros
- Better data collection
- Better front end
- Much stronger processing capability
#### Cons
- More power, not needed really
- Bigger as well, so space is a concern.
- Expensive
 
### ESP 32
#### Pros
- Smaller, and lower power.
- Cheaper
#### Cons
- Not a lot of processing power.


## Status indication
There are many things that can be portrayed and need to be monitored, but in reality not really. The main focus is water level. But there are lots of ways to display status

#### [WS 2811 LED](https://www.amazon.com/gp/product/B01AU6UG5C/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)
A single LED with its color controlled can display several status with only a single light. Plus I have a ton.
#### [E ink display](https://www.amazon.com/waveshare-2-13inch-HAT-Resolution-Raspberry/dp/B07Q22WDB9/ref=sr_1_5?keywords=Eink+display&qid=1644453485&sr=8-5)
An Eink/Epaper display can show basic metrics (Water level mainly) live with minial power draw. Just pricy at 20$ for a small boy.
#### [Touchscreen dispaly](https://www.amazon.com/LCD-Display-Inch-Screen-Touchscreen/dp/B09BZZXYJD/ref=sr_1_21?crid=3G2MBVDNN7TRZ&keywords=arduino%2Blcd&qid=1644453684&sprefix=arduino%2Blcd%2Caps%2C91&sr=8-21&th=1)
A cool option that would require the RPi. Enables easier user adjustment of time range for lights and water level standard. Pricey at ~30-50$ 

#### [OLED screen](https://www.amazon.com/1-5inch-RGB-OLED-Module-Communicating/dp/B07DB5YFGW/)
This is a lower power full color option. Same benefits of any color screen, just a bit pricier. ~20 for small boy and higher power draw than E ink.

#### [The Icon](https://www.amazon.com/SunFounder-Serial-Module-Display-Arduino/dp/B019K5X53O/)
Not really useful. Can display status but god will it look ugly. Rather use the oled at this size for the same price.

## Water level Sensor 

### [Non Contact High/Low](https://www.amazon.com/Taidacent-Contact-Liquid-Sensor-Controller/dp/B07FC5RGC7)
Nice because Non contact, not too pricey, but being high/low and no easy mounting point makes it a bad option.

### [Water Depth Level Sensor](https://www.amazon.com/Sensor-Module-Detection-Surface-Arduino%EF%BC%8810pcs%EF%BC%89/dp/B07THDH7Y4)
Overall good option, gives a range of water level control, not high/low, but corosion is a concern.

### Ultrasonic ?

## Air pump
## Grow Lights
## Power Management
---
# Potential Features
### Drawer Slides on basin
### IOT connection
### Status Screen
### Website
### Automated nutrient dispersal
### TimeLapse camera




