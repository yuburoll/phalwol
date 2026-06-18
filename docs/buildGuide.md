# Build Guide
this is build guide for phalwol.

the build guide contains photo of prototype version. newest version have following differences:

- the corner screws of outside top are moved 1u inside, so do the PCB design.

- lower pinky modifier keys are not changeable. as black marked in prototype PCB

This documents are translated by generative AI, so there can be some misleading texts.

### Additional Resources
[**Soldering Tips**](solderingTip.md)

# PCB Preparation
Prepare two PCBs for the phalwol. Since these are reversible PCBs, be careful to place components on different sides for each board.

The side where components will be placed is treated as the back, and the side without components is treated as the front. **All components go on back side only, so please be careful when soldering.**

# Soldering the Diodes
Solder the diodes. The photos show SMD diodes being used, but THT diodes can also be used.

In the photo, the hot-swap sockets are soldered first, but I recommend soldering the diodes first.

When using SMD diodes, first apply a solder blob to one side of the pad with a soldering iron, as shown in the following photos.

![phalwolBuildDiodes1](../images/phalwolBuildDiodes1.jpg)
![phalwolBuildDiode2](../images/phalwolBuildDiodes2.jpg)

Reheat the solder blob with the iron to melt it, align the diode in the correct orientation and place it in position, then remove the iron.

![phalwolBuildDiode3](../images/phalwolBuildDiodes3.jpg)

Once it is seated properly, solder the opposite leg.

![phalwolBuildDiode4](../images/phalwolBuildDiodes4.jpg)

# Soldering the Hot-swap Sockets
Solder the hot-swap sockets. The process is largely the same as soldering the diodes and LEDs.

As before, apply a solder blob to one side of the pad, reheat the blob to melt it, place the component and hold it in position, remove the iron, then solder the opposite leg.

![phalwolBuildSocket2](../images/phalwolBuildSocket2.jpg)
![phalwolBuildSocket4](../images/phalwolBuildSocket4.jpg)

# Soldering the TRRS Jack and the Jumper
Refer to the following photos to identify where the TRRS jack will be placed. The jack will be placed on back side, so you may solder that on front side.

![phalwolBuildJack0](../images/phalwolBuildJack0.jpg)

Solder the TRRS jack. When soldering the Tip and Sleeve pins, also bridge them to the adjacent pads as shown in the photo.

And, On the front side seen when soldering the jack, bridge the jumpers located aside. Apply enough solder so that a blob forms on top.

![phalwolBuildJack1](../images/phalwolBuildJack1.jpg)

# Soldering the Dev Board
First, check the header pins on the provided Pro Micro dev board. The outermost row of header pins past 5V is not needed, so trim them off.

![BuildBoard0](../images/BuildBoard0.jpg)
![BuildBoard1](../images/BuildBoard1.jpg)

Insert the header pins starting from 5V, align them, and solder the dev board. When soldering, make sure the components face upward as shown in the photo.

![BuildBoard2](../images/BuildBoard2.jpg)
![BuildBoard3](../images/BuildBoard3.jpg)

Place the dev board with the soldered header pins on top of the already-soldered hot-swap sockets. Press down firmly to ensure a tight fit.

![phalwolBuildBoard1](../images/phalwolBuildBoard1.jpg)
![phalwolBuildBoard2](../images/phalwolBuildBoard2.jpg)
![phalwolBuildBoard3](../images/phalwolBuildBoard3.jpg)

Just like when soldering the TRRS jack pins, bridge the header pins to the adjacent pads as if soldering jumpers. Since a large amount of solder is used, there is a risk of bridging with flux, so be sure to clean the area with alcohol after soldering.

![phalwolBuildBoard4](../images/phalwolBuildBoard4.jpg)

# Check before Assembly
The finished PCBs look like following images.

![phalwolBuildAssembly1](../images/phalwolBuildAssembly1.jpg)
![phalwolBuildAssembly2](../images/phalwolBuildAssembly2.jpg)

If you're a keyboard enthusiast, I'd recommend installing stabilizers at keycap positions 2u or larger, as shown in the following photo.

![phalwolBuildStabilizer](../images/phalwolBuildStabilizer.jpg)

# Assembly
First, assemble plate and switches together with proper direction, and assemble PCB on it.

You can fasten all the switches to the plate first and then join it to the PCB, but I also recommend the method shown in the photo: attach the switches to the four corners first, place the PCB, and then assemble the remaining switches one by one.

![phalwolBuildKeyswitches1](../images/phalwolBuildKeyswitches1.jpg)
![phalwolBuildKeyswitches2](../images/phalwolBuildKeyswitches2.jpg)
![phalwolBuildKeyswitches3](../images/phalwolBuildKeyswitches3.jpg)
![phalwolBuildKeyswitches4](../images/phalwolBuildKeyswitches4.jpg)

Place the plate assembly over the case and fasten it with screws at eight points per side to complete the build. also, you may add four bumpons on the bottom of the case.

![phalwolBuildFinish](../images/phalwolBuildFinish.jpg)
