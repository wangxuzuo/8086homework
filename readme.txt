computor environment MacOS ventera i5 core
I use 1.sh to start up my cpusim app which javaFX necessary 
------  bash 1.sh 
but macos can not use app emu8086

**********************************
if you like my project please star Thank you

**********************************
task1
chinese version 
利用CPU SIM进行类8086的指令模拟，并完成100-150的整数求和，并把结果保存到寄存器AX中。流程：在CPU SIM中新建一个机器，设置需要的寄存器（寄存器名称与位宽要与8086一一对应）和内存（1MB内存）。之后，设计求和算法需要的指令（具体指令执行流程、通用取址流程、指令格式）。最后，基于你设计的指令，完成求和算法的汇编语言，并给寄存器最终情况与代码截图。
注1：寄存器除了通用寄存器，还需要模拟ALU的执行过程，设置数据与地址计算的ALU输入输出等6个寄存器。
注2：指令格式不需要与8086完全一致
注3：可以参考官方demo，但不能直接使用设计好的指令
注4：除了加法指令和循环体外，还需要在程序末尾加上暂停指令
The 8086-class instruction is simulated by CPU SIM, and the integer sum of 100-150 is completed, and the result is saved to the register AX. Process: Create a new machine in CPU SIM and set the required register (register name and bit width should correspond to 8086) and memory (1MB memory). After that, the instructions required by the summation algorithm (specific instruction execution flow, general addressing flow, instruction format) are designed. Finally, based on the instructions you design, complete the summation algorithm in assembly language, and give the register final situation with the code screenshot.
Note 1: In addition to the general registers, 6 registers need to simulate the execution process of the ALU and set the input and output of the ALU for data and address calculation.
Note 2: The instruction format does not need to be exactly the same as 8086
Note 3: You can refer to the official demo, but you cannot use the designed instructions directly
Note 4: In addition to the addition instruction and the loop, it is necessary to add the pause instruction at the end of the program
**********************************
task2
chinese
基于emu8086模拟器完成汇编语言的编写。为04H,F9H,F2H,39H,05H分配空间（分配空间时顺序固定为这样）。对于这五个数据，设计排序算法让数列从低到高排列，并分别输出到BL、BH、CL、CH、DL中（或基于软中断，打印排序后的数列到屏幕上）。
注：可使用任意排序算法，保证结果正确即可。
Based on emu8086 simulator to complete the compilation of assembly language. The space allocation sequence is 04H,F9H,F2H,39H, and 05H. For these five data, the sorting algorithm is designed to arrange the sequence from lowest to highest and output the sequence to BL, BH, CL, CH, DL (or print the sorted sequence to the screen based on soft interrupts).
Note: Any sorting algorithm can be used to ensure that the results are correct.