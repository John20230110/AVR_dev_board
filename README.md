# AVR_dev_board

The schematics of this AVR development board are mainly taken from Mao Chao's book "AVR单片机嵌入式系统原理与应用实践"("The principles and applications of AVR embedded systems") with some modifications.

The first modification is to combine the AT89S5X and Mega16 sockets to just one socket because the limitation of the space on the PCB. A 10cmX10cm PCB can be made in 10 Chinese yuan(about 1.3 US dollar) for 5 pieces by the online shop on Taobao, but the cost would soar if the size of PCB beyond that. Therefore, I put the schematics on two 10cmX10cm PCBs connected through wires. Although this division,  the space of a single board is still limited. The second modification is to add some schematics, for example a 3.3V power source and a rotator encoder.

The schematics and the PCB files of the two 10cmX10cm PCBs  are put into two directories, AVR_dev_board_main and AVR_dev_board_per_devices.  The PCB disign software used is kicad( version: 6.0.2).

In the  AVR_dev_board_main directory, there are the files of schematics and the PCB containing the MUC socket and the components connected colsely to it, for example, the crystal oscillator, the seiral connector, the power source, and the programming connector.

In the AVR_dev_board_per_devices directory, there are files of schematics and the PCB containing the peripheral devices, mainly used for input and output, such as the keyboard, the buzzer, the display, and the rotator encoder.

Here are the pictures of the first version boards. The boards are compatible to AT89s5X MCUs.

![Main_Board](https://github.com/John20230110/AVR_dev_board/blob/main/pictures/main_board.JPG)

![Peripheral_Device_Board](https://github.com/John20230110/AVR_dev_board/blob/main/pictures/per_board.JPG)

After some experiments, I found the layout, especialy PCB of the peripheral device, could be impoved. 
