# EXPERIMENT--01-ALP-FOR-8086
Name : John Wilfred Thomas J W
Reg no : 212224040141
Date of experiment : 16.02.2026

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
Mov Ax,5782H
Mov Bx,23ABH
Add Ax,Bx
Mov [3001H],Ax
HLT
```
## Output  
 <img width="1434" height="1055" alt="image" src="https://github.com/user-attachments/assets/56291228-577c-4b31-befb-2af7e6d1ece2" />

## Subtraction   of 8-bit numbers  ALP 
 ```
Mov Ax,5782H
Mov Bx,23ABH
Sub Ax,Bx
Mov [3003H],Ax
HLT
```
## Output  
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f5dd146e-eafc-49c2-bef3-484f0b188c5c" />

## Multiplication alp 
```
mov AX,5782H
mov BX,23ABH
mul BX
mov [3005H],AX
mov [3007H],DX
HLT
```
## Output  
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/df1813b2-f345-4592-af2d-96255897689a" />

## Division alp 
```
mov AX,5782H
mov BX,23ABH
div BX
mov [3009H],AX
mov [300BH],DX
HLT
```
## Output  
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/b5755e0d-20df-4d18-8718-245e862cec96" />

## AND GATE ALP
```
mov AX,5782H
mov BX,23ABH
AND AX,BX
MOV [4001H],AX
HLT
```
## OUTPUT

<img width="1919" height="1021" alt="and" src="https://github.com/user-attachments/assets/cdf5d468-c722-4c49-a30b-e862b006fbda" />

## OR GATE ALP

```
mov AX,5782H
mov BX,23ABH
OR AX,BX
MOV [4003H],AX
HLT
```
## OUTPUT

<img width="1918" height="1013" alt="or" src="https://github.com/user-attachments/assets/1231bcdb-621c-4d3f-99a8-6bfb9e149f7f" />

## NOT GATE ALP

```
mov AX,5782H
NOT AX
MOV [4005H],AX
HLT
```
## OUTPUT

<img width="1919" height="1017" alt="not" src="https://github.com/user-attachments/assets/ad1fa78d-834b-4bc8-b8d3-97b707a3b7f7" />

## XOR GATE ALP

```
MOV AX,5782H
MOV BX,23ABH
XOR AX,BX
HLT
```

## OUTPUT

<img width="815" height="431" alt="image" src="https://github.com/user-attachments/assets/5f335be4-2d4d-43c3-8df3-7de8ed60b3d5" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
