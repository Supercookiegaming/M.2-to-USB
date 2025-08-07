## PCB Ordering Instructions

This project is designed to be built using JLCPCB with a specific stackup to ensure impedance on USB signals. If another stackup or manufacture is need, recalculating the impdance for the USB signals is required. It is recommened to use a calculator like the uSimmics Transmission Line Calculator Tool. This project used uSimmics 5.8 which can be downloaded [here](https://qucsstudio.de/download/). 

The target differential impedance for USB 2.0 signals is 90Ω. In uSimmics the trace width, gap and clearence are modified so Z_odd is close 45Ω as seen in the calculation settings seen for this project. ![uSimmics Impedance Calculation](/Instructions/Instruction_Pictures/USB_differntial_impedance_calculation.JPG)

It recommened to also purchase a solder paste stencil for this board. 

### Required Options for this Design
1. Upload the Gerber Zip file found in [M.2-to-USB/Gerber](https://github.com/Supercookiegaming/M.2-to-USB/tree/v1.1/Gerber) to JLCPCB Instant Quote tool.

2. Set the Layers to `4`, if not already done so by the tool.

3. Set the Dimensions to `22 x 30 mm`, if not already done so by the tool.

4. Select a PCB thickness of `0.8mm`.

5. Set the Outer Copper Weight to `1oz` and the Inner Copper Weight to `0.5oz`.

6. Select Specify Stackup to `Yes` and select `JLC04081H-3313` for the Layer Stackup.

7. Select `Yes` for Gold Fingers.

8. Select `Yes` for Castellated Holes and set Edges to `1`. (this is technically not needed but may result in errors in the m.2 mounting hole)

### Recommended Options
1. The `ENIG` platting option with `2 U` thickness is recommended but can be expensive. The `1 U` thickness is acceptable if multiple insertions aren't planned.

2. It is recommended that the Vias are at the very least plugged. Expoy Filled/Copper Paste Filled & Capped Vias are optimal but can be expensive.

3. The 4-Wire Kelvin Test and Paper between PCBs are both recommended.

### Stencil Ordering Instructions
1. The Stencil Side should be set to `Top only`.

2. It is recommended that a smaller custom size is selected, for example `50 x 50 mm`.

3. Paste the following into the Stencil Remark text box `Please follow the solder paste layer only, and ignore the difference between the solder mask layer and solder paste layer.`
