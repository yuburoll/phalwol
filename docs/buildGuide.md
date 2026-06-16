# Build Guide
this is build guide for phalwol.

the build guide contains photo of prototype version. newest version have following differences:

- the rims between first row and third row are 4mm wider, for easier assembly. these PCB have outline silkscreen.

- the corner screws of case aside fourth row are enforced, so they also have different plate design.

This documents are translated by generative AI, so there can be some misleading texts.

### Additional Resources
[**Soldering Tips**](solderingTip.md)

# PCB Preparation
Prepare two PCBs for the phalwol. Since these are reversible PCBs, be careful to place components on different sides for each board.

The side where components will be placed is treated as the back, and the side without components is treated as the front. **All components go on back side only, so please be careful when soldering.**

![phalwolPhotoPCB0](../images/phalwolPhotoPCB0.jpg)
![phalwolPhotoPCB1](../images/phalwolPhotoPCB1.jpg)

# Soldering the Diodes
Solder the diodes. The photos show SMD diodes being used, but THT diodes can also be used.

When using SMD diodes, first apply a solder blob to one side of the pad with a soldering iron, as shown in the following photo.

![phalwolPhotoDiode0](../images/phalwolPhotoDiode0.jpg)

Reheat the solder blob with the iron to melt it, align the diode in the correct orientation and place it in position, then remove the iron.

![phalwolPhotoDiode1](../images/phalwolPhotoDiode1.jpg)

Once it is seated properly, solder the opposite leg.

![phalwolPhotoDiode2](../images/phalwolPhotoDiode2.jpg)

# Soldering the Hot-swap Sockets
Solder the hot-swap sockets. The process is largely the same as soldering the diodes and LEDs.

As before, apply a solder blob to one side of the pad, reheat the blob to melt it, place the component and hold it in position, remove the iron, then solder the opposite leg.

![phalwolPhotoHotswap0](../images/phalwolPhotoHotswap0.jpg)
![phalwolPhotoHotswap1](../images/phalwolPhotoHotswap1.jpg)

# Soldering the TRRS Jack
Refer to the following photos to identify where the TRRS jack will be placed.

![phalwolPhotoJack0](../images/phalwolPhotoJack0.jpg)
![phalwolPhotoJack1](../images/phalwolPhotoJack1.jpg)

Solder the TRRS jack. When soldering the Tip and Sleeve pins, also bridge them to the adjacent pads as shown in the photo.

![phalwolPhotoJack2](../images/phalwolPhotoJack2.jpg)

# Soldering the Dev Board
First, check the header pins on the provided Pro Micro dev board. The outermost row of header pins past 5V is not needed, so trim them off.

![phalwolPhotoDevboard0](../images/phalwolPhotoDevboard0.jpg)
![phalwolPhotoDevboard1](../images/phalwolPhotoDevboard1.jpg)

Insert the header pins starting from 5V, align them, and solder the dev board. When soldering, make sure the components face upward as shown in the photo.

![phalwolPhotoDevboard2](../images/phalwolPhotoDevboard2.jpg)
![phalwolPhotoDevboard3](../images/phalwolPhotoDevboard3.jpg)

Place the dev board with the soldered header pins on top of the already-soldered hot-swap sockets. Press down firmly to ensure a tight fit.

![phalwolPhotoDevboard4](../images/phalwolPhotoDevboard4.jpg)
![phalwolPhotoDevboard5](../images/phalwolPhotoDevboard5.jpg)

Just like when soldering the TRRS jack pins, bridge the header pins to the adjacent pads as if soldering jumpers. Since a large amount of solder is used, there is a risk of bridging with flux, so be sure to clean the area with alcohol after soldering.

![phalwolPhotoDevboard6](../images/phalwolPhotoDevboard6.jpg)

# Soldering the Jumpers
On the front side seen when soldering the dev board, bridge the jumpers located just below. Apply enough solder so that a blob forms on top.

![phalwolPhotoJumper0](../images/phalwolPhotoJumper0.jpg)
![phalwolPhotoJumper1](../images/phalwolPhotoJumper1.jpg)

# Check before Assembly
a finished right side of PCB looks like following images. mirror it on the left side.

the photo didn't jumped the front jumper, but you may jump there if you building wired version.

![phalwolPhotoPCBFinish0](../images/phalwolPhotoPCBFinish0.jpg)
![phalwolPhotoPCBFinish1](../images/phalwolPhotoPCBFinish1.jpg)

# Assembly
First, assemble the case, plate, and switches together. (Note: If you assemble the plate, switches, and PCB first, the assembly will not fit into the case.)
The plate and case are fastened together with screws at four points.

![phalwolPhotoAssembly0](../images/phalwolPhotoAssembly0.jpg)
![phalwolPhotoAssembly1](../images/phalwolPhotoAssembly1.jpg)

Insert the protruding part of the TRRS jack into the hole in the case, then lower the PCB onto the switches to mate them together.

![phalwolPhotoAssembly2](../images/phalwolPhotoAssembly2.jpg)
![phalwolPhotoAssembly3](../images/phalwolPhotoAssembly3.jpg)

Place the backplate over the case and fasten it with screws at eight points per side to complete the build.

![phalwolPhotoAssembly4](../images/phalwolPhotoAssembly4.jpg)
