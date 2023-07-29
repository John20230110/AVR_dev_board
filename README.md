# AVR_dev_board

The schematics of this AVR development board are mainly taken from Mao Chao's book "AVR单片机嵌入式系统原理与应用实践"("The principles and applications of AVR embedded systems") with some modifications.

The first modification is to combine the AT89S5X and Mega16 sockets to just one socket because the limitation of the space on the PCB board. A 10cmX10cm PCB board can be made in 10 Chinese yuan(about 1.3 US dollar) for 5 pieces by the online shop on Taobao, but the cost would soar if the size of PCB board beyond that. Therefore, I put the schematics on two 10cmX10cm PCB boards connected by wires. Although this division,  the space of a single board is still limited. The second modification is to add some schematics, for example a 3.3V power source and a rotator encoder.

The schematics and the PCBs layout of the two 10cmX10cm PCBs  are put into two files, AVR_dev_board_main and AVR_dev_board_per_devices.  The PCB disign software is kicad( version: 6.0.2).

In the file AVR_dev_board_main, there are the schematics and the PCB layout of the MUC socket and the components connected colsely to it, for example, the crystal oscillator, the seiral connector, the power source, and the programming connector.

In the file AVR_dev_board_per_devices, there are the peripheral devices, mainly used for input and output, such as the keyboard, the buzzer, the display, and the rotator encoder.

Here is the first version of the PCBs. The board is compatible to AT89s5X MCU.

![Main Board](pictures/main_board "main board")

![Peripheral Device](pictures/main_board "Peripheral Device")

After some experiments, I found the layout, especialy of the peripheral device  board, could be impoved. 
