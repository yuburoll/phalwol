# Build Guide
this is build guide for phalwol.

the build guide contains build of prototype version. newest version have following differences:

- the corner screws of outside top are moved 1u inside, so do the PCB design.

This documents are translated by generative AI, so there can be some misleading texts.

### Additional Resources
[**Soldering Tips**](solderingTip.md)

# PCB Preparation
Prepare two PCBs for the phalwol. Since these are reversible PCBs, be careful to place components on different sides for each board.

The side where components will be placed is treated as the back, and the side without components is treated as the front. **All components go on back side only, so please be careful when soldering.**

# Soldering the Diodes
Solder the diodes. The builds show SMD diodes being used, but THT diodes can also be used.

When using SMD diodes, first apply a solder blob to one side of the pad with a soldering iron, as shown in the following build.

![phalwolBuildDiode1](../images/phalwolBuildDiode1.jpg)

Reheat the solder blob with the iron to melt it, align the diode in the correct orientation and place it in position, then remove the iron.

![phalwolbuildDiode1](../images/phalwolbuildDiode1.jpg)

Once it is seated properly, solder the opposite leg.

![phalwolbuildDiode2](../images/phalwolbuildDiode2.jpg)

# Soldering the Hot-swap Sockets
Solder the hot-swap sockets. The process is largely the same as soldering the diodes and LEDs.

As before, apply a solder blob to one side of the pad, reheat the blob to melt it, place the component and hold it in position, remove the iron, then solder the opposite leg.

![phalwolbuildHotswap0](../images/phalwolbuildHotswap0.jpg)
![phalwolbuildHotswap1](../images/phalwolbuildHotswap1.jpg)

# Soldering the TRRS Jack
Refer to the following builds to identify where the TRRS jack will be placed.

![phalwolbuildJack0](../images/phalwolbuildJack0.jpg)
![phalwolbuildJack1](../images/phalwolbuildJack1.jpg)

Solder the TRRS jack. When soldering the Tip and Sleeve pins, also bridge them to the adjacent pads as shown in the build.

![phalwolbuildJack2](../images/phalwolbuildJack2.jpg)

# Soldering the Dev Board
First, check the header pins on the provided Pro Micro dev board. The outermost row of header pins past 5V is not needed, so trim them off.

![phalwolbuildDevboard0](../images/phalwolbuildDevboard0.jpg)
![phalwolbuildDevboard1](../images/phalwolbuildDevboard1.jpg)

Insert the header pins starting from 5V, align them, and solder the dev board. When soldering, make sure the components face upward as shown in the build.

![phalwolbuildDevboard2](../images/phalwolbuildDevboard2.jpg)
![phalwolbuildDevboard3](../images/phalwolbuildDevboard3.jpg)

Place the dev board with the soldered header pins on top of the already-soldered hot-swap sockets. Press down firmly to ensure a tight fit.

![phalwolbuildDevboard4](../images/phalwolbuildDevboard4.jpg)
![phalwolbuildDevboard5](../images/phalwolbuildDevboard5.jpg)

Just like when soldering the TRRS jack pins, bridge the header pins to the adjacent pads as if soldering jumpers. Since a large amount of solder is used, there is a risk of bridging with flux, so be sure to clean the area with alcohol after soldering.

![phalwolbuildDevboard6](../images/phalwolbuildDevboard6.jpg)

# Soldering the Jumpers
On the front side seen when soldering the dev board, bridge the jumpers located just below. Apply enough solder so that a blob forms on top.

![phalwolbuildJumper0](../images/phalwolbuildJumper0.jpg)
![phalwolbuildJumper1](../images/phalwolbuildJumper1.jpg)

# Check before Assembly
a finished right side of PCB looks like following images. mirror it on the left side.

the build didn't jumped the front jumper, but you may jump there if you building wired version.

![phalwolbuildPCBFinish0](../images/phalwolbuildPCBFinish0.jpg)
![phalwolbuildPCBFinish1](../images/phalwolbuildPCBFinish1.jpg)

# Assembly
First, assemble the case, plate, and switches together. (Note: If you assemble the plate, switches, and PCB first, the assembly will not fit into the case.)
The plate and case are fastened together with screws at four points.

![phalwolbuildAssembly0](../images/phalwolbuildAssembly0.jpg)
![phalwolbuildAssembly1](../images/phalwolbuildAssembly1.jpg)

Insert the protruding part of the TRRS jack into the hole in the case, then lower the PCB onto the switches to mate them together.

![phalwolbuildAssembly2](../images/phalwolbuildAssembly2.jpg)
![phalwolbuildAssembly3](../images/phalwolbuildAssembly3.jpg)

Place the backplate over the case and fasten it with screws at eight points per side to complete the build.

![phalwolbuildAssembly4](../images/phalwolbuildAssembly4.jpg)
