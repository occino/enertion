# "Raptor 2.1 GTX" | R-SPEC DRIVE | FOCBOX Unity | 12S3P | 3D printed custom enclosure

![Complete1](https://raw.githubusercontent.com/occino/enertion/master/complete/DSC_0062.JPG)

**Hi guys,**

I'm Nico from Berlin, Germany and I'm building electrial longboards since two years now. I would like to share with you my latest and easiest build which is basically a Raptor 2.1 with at GTX deck. I'm also motivated to write this post because of the "Enertion R-SPEC DRIVE KIT | Best Build Competition" [[click here](https://www.electric-skateboard.builders/t/enertion-r-spec-drive-kit-best-build-competition-win-cash-back/ "Enertion")].


## Specs & features:

* R-SPEC DRIVE KIT w/ 90mm wheels
* FOCBOX UNITY ESC
* Evolve GTX deck
* Custom 12S3P (Sony Konion US18650VTC5 2600mAh - 30A) + BMS
* 3D printed custom enclosure + PVC bottom plate
* Enertion Nano-X 2.4Ghz Controller
* Voltage display
* USB charging port module
* Loop key

## GTX deck
![GTX1](https://raw.githubusercontent.com/occino/enertion/master/deck/DSC_0008.JPG)
The GTX deck by evolve is perfectly suited in my opinion because it comes with a notch for the battery pack. Furthermore it's flexible and looks nice.

In order to use a 10S4P battery, the notch had to be enlarged for about 1 cm. I used the original screw holes to mount the battery enclosure.

## Enclosure
![Enclosure1](https://raw.githubusercontent.com/occino/enertion/master/enclosure/enclosure.png)
The enclosure is a modular 3D printed frame with a pvc plate underneath. Due to the dimension limits of 3D printing I decided to design a modular system which can be printed in multiple parts. To ensure water resistence I used a tongue and groove technique which makes the enclosure flexible as well. I also used sponge rubber between deck and enclosure and pvc plate and enclosure.
You can find all parts on [thingiverse](https://www.thingiverse.com/thing:3382660 "Thingiverse")

![Enclosure2](https://raw.githubusercontent.com/occino/enertion/master/enclosure/IMG_20190126_122641.jpg)
In order to mount the pvc plate underneath I pasted M4 threaded sleeves (5mm x 18mm) ([link](http://www.lignoshop.de/gewindehuelse-stahl-m4-5mm-37811022000.html "link")) into the parts as you can see in the picture below. This way I can use proper thread screws. The threaded sleeves are also used by the deck screws from the other side. This makes the construction pretty strong. 

![Enclosure3](https://raw.githubusercontent.com/occino/enertion/master/focbox/DSC_0018.JPG)

### FOCBOX UNITY case
![FOCBOX1](https://raw.githubusercontent.com/occino/enertion/master/focbox/focbox_case.JPG)
This case contains is the FOCBOX UNITY as well as a battery voltage display and the power switch provided by enertion. The voltage display is powered by the CAN  bus port (5V, GND) and the measuring wire is connected to the BATT+ pin of the AUX port. Because the the FoxBox sits tightly in the compartment there is no need to mount it with screws.

### Connector box
![ConnectorBox1](https://raw.githubusercontent.com/occino/enertion/master/connectorBox/connectorBox.jpg)
The connector box is the middle part and contains the receiver, 3A USB charging module (LM2596HV), XT60 charging port, XT60 key loop and all the wiring. The charging port is connected to the BMS via XT30 in order to switch the battery easily. The receiver of the Enertion Nano-X 2.4Ghz Controller fits perfectly in a small compartment and doesn't need to be mounted with screws.

### Battery pack (12S3P, Sony Konion VTC5)
![Battery1](https://raw.githubusercontent.com/occino/enertion/master/battery/battery.jpg)
12S3P or 10S4P? I chose both variants. 12S for more fun and 10S for more range. For the 12S3P pack I used 36 **Sony Konion US18650VTC5 cells 2600mAh** with a total capacity of 336Wh. I paid 128€ for 36 VTC5 cells on [eu.nkon.nl](https://eu.nkon.nl/ "eu.nkon.nl"). 36 VTC6 cells with 3000mAh would have cost 207€ for additonal 53Wh. Because range is not that important to me I took the cheaper option.

#### Spotwelding
![Battery1](https://raw.githubusercontent.com/occino/enertion/master/battery/spotwelder.JPG)

For spotwelding I used the amazing kWeld by [keenlab](https://www.keenlab.de/ "keenlab") which is powered by a high discharge lipo. The nickels strips are pure nickel with 8mm x 0.3. I made some tests and figured out that they can easily handle 25A. In order to archive the full rated 90A of the cells I used 4 layers of nickel (pyramid technique) at the S-transitions to be on the safe side.

![Battery2](https://raw.githubusercontent.com/occino/enertion/master/battery/batterySetup.jpg)

![Battery3](https://raw.githubusercontent.com/occino/enertion/master/battery/pyramid.jpg)

![Battery4](https://raw.githubusercontent.com/occino/enertion/master/battery/pack_raw.jpg)

The BMS is a cheap 13S circuit which can be used for 12S as well. It is only used for charging and not for discharging. To prevent the battery from over discharge I used the cut off setting of the FOCBOX UNITY.
As I mentioned before I would like to use 12S3P and 10S4P. In order to get the same dimensions I printed 4 dummy cells as your can see on the picture below.

![Battery5](https://raw.githubusercontent.com/occino/enertion/master/battery/pack_bms.jpg)

After adding all the wires I added felt pads on all edges which should absorb shocks. 

![Battery6](https://raw.githubusercontent.com/occino/enertion/master/battery/pack_padding.jpg)

Finally I used 200mm shrink tube and a hot air gun to close the battery pack.

![Battery7](https://raw.githubusercontent.com/occino/enertion/master/enclosure/IMG_20190126_150100.jpg)

After inserting the battery and connecting the XT60 and XT30 the only thing left is the bottom plate.

![Battery8](https://raw.githubusercontent.com/occino/enertion/master/enclosure/enclosure_bottom.jpg)

That's it. Just and easy, modular build :)

What do you think? Any suggestions for improvements?

Cheers, Nico

