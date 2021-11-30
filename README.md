# DIY-Mic
A DIY microphone built using the design of DIY Perks and modified by me. I wanted a decent mic and I didnt want to spend the money on one, so when I saw this video it seemed like the perfect opportunity for me to both have fun with a electronics project and get a decent mic.

# Credit
This would not be possible without DIY Perks and the resources he provided. The stripboard and base wiring diagram are extremely helpful as well as his overall attention to detail. Video link here: https://www.youtube.com/watch?app=desktop&v=LoQu3XXIayc

# Aquiring Parts
For this build, there are a number of parts you will need. In the video he goes all out in brass, which for most of us at home, seems absurd because of how uncommon it is to have the exact diameter of brass tubing or brass mesh lying around. I ran into this problem early on, so I designed a box and lid for mine that should work in place of a ton of brass and wood, and is easily 3d printable (STLs above). I know most people don't have 3d printers but I feel like this is slightly more accessable for those without hordes of tools. I also used a mic arm I found in the trash to make the arm instead of building it. So, with the 'housing' out of the way, everything else can be found in this list (or at least what I used/needed):

https://docs.google.com/spreadsheets/d/1pQlkRerO5geoDNLEWXTUVbyJalM7nESn/edit#gid=497893649

As you can probably tell, the pricing is pretty high compared to the sticker price. That was the number I was able to get it down to after some alternatives (and using the wrong materials and finding out they dont work. The electronics can either be found on alibaba or ebay, I chose ebay because that was the only way I could finish this in less then 2 months. With all of that, I nicked a old audio cable, a old rc car motor, and some resistors in order to start buuilding.

# Actually Building the Thing
The first thing I did (and this pretty much goes with the order the parts arrived to me) was the preamp box. I put some brass mesh on the bottom and glued the template on some protoboard, soldered all of the parts on and drilled corner holes. In hindsight, the pegs I included were pretty useless (and off center) so they should probably just be removed. I layered some tape over the bottom mesh to preevent shorts and plopped the whoile thin in. I then added the potentiometer to the lid. Note, I live in the US, so I was unable to get a THAT1512, and I had to go with a INA217. This isn't really a problem, just know that on my final build, I attached a 2.2kOhm reesistor to the potentiometer because of how the gain settings work. I assume there may be some overall gain differences, but we'll get to that in the review section. I pretty much did that and threw in the ADC (Analog Digital Converter) with some tape covering it. I ordered a pretty cheap one, but it has a led and I kind of like that because of how much easier it made troubleshooting. All of these parts can be connected to the main board and the ADC can be connected to the USB-C breakout board. Power wires can be connected and that should be everything that is directly connected.

Partially Assembled:
![image](https://user-images.githubusercontent.com/51302710/144125291-565f24c1-3dd9-46f5-9dc7-01acb22c6510.png)


Some notes real quick before putting anything on the board:

![image](https://user-images.githubusercontent.com/51302710/144122027-1740cdab-1119-45a4-ba0c-7c951bffd989.png)

The two capacitors on the right need to be filpped 180 degrees so the polarities are swapped, and all of the rest are fine, with the white being positive and dark being neagtive. Other then that, you can build it however you want. I found that its better to use a littlbe bit thicker audio cable, because the stuff that i used was really thin and I ened up having to solder it a bit to get the connectors to stay on.

![image](https://user-images.githubusercontent.com/51302710/144125186-f541898c-78db-453a-9723-6b566a6a3f21.png)

And on that note lets talk about the cables. So yes, you can use solder removing copper strips like he did. But I had extremely bad luck with mine all just being flat to begin with, and thus not folding back into a tube. So as a result I just ordered some proper sheathing. Honestly, worth it. I eneded up threading the enameled wires through much easier then I thought it would be. So with those two out of the way, IU soldered them together and used a heatshrink for the binding. Now, I just want to note that the way DIY Perks sands the enamel off of those thin wires is correct, however, be extremely careful because if you go too far they are super easy to short (trust me I know from experience). So with that, you can plug the cable into the preamp and work on the mic. 

![image](https://user-images.githubusercontent.com/51302710/144125398-0a70cf0e-e4d7-462c-a5d9-1f4843830502.png)

The mic, from my eperience has the parts that take the longest to get here. First of all, if you can get a JLI mic module, be my guest, but they seem to be always out of stock. I ordered mine from another place for a signifigant markup and I'm not even mad. At least its here. The transistors took a hot minute to get here (they were the last thing I needed and I actually moved on to another project I got so sick of waiting on them. Once they did arrive though, its pretty much exactly as he said. However, I should note my module housing is also 3d printed and the grills are shaped using 3d printed parts. Crushed the mesh in between the mold and formed the grills, soldered them with the transistor mic combo like a sandwitch, and jammed it into the housing. I added all of those holes for maximum sound quality and it seems to work. I will note that you should probably put something between the grill and transistor, as well as between the legs due to possible shorting, as that is what cause a lot of my eary trouble. With that, thats basically evertything. I used some tape to secure the lid onto the box and hot glue to keep some loose things secured and it just kind of works. 

![image](https://user-images.githubusercontent.com/51302710/144125371-e0664250-f5e9-4656-b29e-008234af8e29.png)

The rear of the module is really jank for me. Don't do this lol:
![image](https://user-images.githubusercontent.com/51302710/144125468-87f54e5f-f0b7-46fa-9680-573abef5bf29.png)

# Review
Overall its a good mic. I've been using it for the past few weeks and everyone whos seen it really likes it. It's kind of scuffed but sounds fantastic (most of the time). I should note that I had a insane amount of gain until I added a resistor between the potentiometer. I still do, and I probably just need more sheilding, but it sounds fine over discord and for personal use so I don't mind too much. I'll fix it when I need it. 

The big things about this project I would note for anyone looking to do this is that a.) it costs more then you expect, b.) it's not going to look anything like the video, and c.) there will be more noise then you think there will be. Other then that, happy building!
