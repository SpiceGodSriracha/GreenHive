# BoxGarden
## _Design basics_

1. Inspirations
2. Design Considerations
    a. Sizing and growth constraints
    b. Heat and power constraints
3. Takeaways

---

## Inspirations
### Many variations of pot with light bar
[Example Planter](https://www.amazon.com/AeroGarden-901103-1200-Harvest-Elite-Platinum/dp/B07CKNX6CJ/ref=sr_1_3_sspa?crid=363WKNV3NXMD2&keywords=smart+indoor+garden&qid=1644418294&sprefix=smart+indoor+garden%2Caps%2C74&sr=8-3-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFLU1hXUVYzVFFESzAmZW5jcnlwdGVkSWQ9QTAzMzcyNDIySUI1TVVVN1o2MUpRJmVuY3J5cHRlZEFkSWQ9QTAwMDYwNzQxMDNBWjExMU5HWkdLJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)
##### Primary features
- Top mounted LED bar/Bottom based electronics.
- Pot is a submerged root type, uses plant food as replacement nutrients.

### [Adafruit Smart IOT Planter](https://learn.adafruit.com/pyportal-pet-planter-with-adafruit-io/)
##### Primary features
- No LED Bar, just a planter with smart sensors.
- Includes a screen, raspi, and a lot of data functionality.
- Pot is a full soil type, no food needed, but not automated/stable watering system.


###### There are a few others such as MudPi, but most are too large (outdoor/plot gardens) or just dumb and too similar to ones from above.


---

## Design Considerations
### Sizing and growth constraints
Due to the restricted height of the Kallax, building to focus on the vertical space would be best. Although there are several design considerations to be made to ensure the best possible end experience. For this case I am just gonna be looking at placement options/concepts to break down their pros and cons.
## Pot designs
### Submerged soil pods
This is the design seen in a lot of products, it involves various sizes of inserts, that consist of a plastic frame, soil, and the seeds (often pre set)

#### Pros
- Water needs less attention
- Easy to replace and remove plants as no soil
#### Cons
- Would require more printing for the frames
- Requires a pump in the water reservoir
- Requires liquid plant food in the reservoir to replace soil nutrients
- Pump is needed

### Full soil planter
This is whats seen in the smart planter, overall a simpler design. Just a soil pot with a moisture sensor.

#### Pros
- No need for a pump, and soil should provide most of the nutrients 
- Simple and overall the easiest to set up
#### Cons
- Replacement is hell.
- Moisture sensors can be a tough choice.
- Need to water manually, but with soil volume may not be a huge 


## Placement Variations
#### Top mounted electronics
Overall this is a very appealing design base. It keeps all electronics contained, with only sensors having to have cable runs. It also provides front visuals, which makes the option for status lights and option. Running the wires for the lights would be very short making potential wire power loss minimal.

##### Pros
- Short wire runs and all electronics contained
- Water is seperated from electronics with near 0% chance of splashing on to sensetive components
- Front access for status indication

##### Cons
- All electronics together, right by the LEDs, means lots of heat. High potential for issues there.
- Verticality is compromised as the components take up precious vertical space

##### Concensus 
Not the best option here, as with bottom mounted room is just too compromised.

#### Bottom mounted electronics
Again this is a very appealing design base. It keeps all electronics contained, with only LEDs having to have cable runs. It also provides front visuals, which makes the option for status lights and option. Design is similar to many leading products already present.

##### Pros
- Short wire runs and all electronics contained
- LEDs seperate for less likely heat issues.
- Front access for status indication

##### Cons
- Water over electronics, yummy. 
- Verticality is compromised as the components take up precious vertical space

##### Concensus 
Not the best option here, as with top mounted room is just too compromised. Plus on this option you get to pour water over your electronics. Yum.

#### Rear mounted electronics
This in general is a great setup, and could actually work if designed well, status LEDs seem to be the only issue as they'd have to be built into the led bar on top, but that isn't that big of an issue.

##### Pros
- Short wire runs and all electronics contained
- LEDs seperate for less likely heat issues.
- Good enough seperation of water from electronics. 
- Rear accecss also means power conversion can be done in box as there will be a bit more room available. (Still not smart though)
- Verticality not taken up by electronics

##### Cons
- More difficult to get status indication on it.
- Will be difficult to get to the electronics box is there are issues. 

##### Concensus 
Very good option, aesthetically and functionally it's up there only worry is maintenance pains.

#### Side mounted electronics
While the ugliest option to me, this is likely a better one.

##### Pros
- Short wire runs and all electronics contained
- LEDs seperate for less likely heat issues.
- Good enough seperation of water from electronics. 
- Rear accecss also means power conversion can be done in box as there will be a bit more room available. (Still not smart though)
- Verticality not taken up by electronics
- Side access means that the electronics can be accessed without removing entire garden.
- 

##### Cons
- Water is closer than the rear mount, but still seperated, and addressable by a designated fill hole underneath the box.
- Uglier option maybe
- Lose some horizontal grow space but tbh thats not critical.


##### Concensus 
Very good option,might be ugly but best operationally.


## Takeaways
Uh oh
###### Stinky