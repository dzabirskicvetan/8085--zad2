# 8085--zad1


Секој 30ms од изолирана порта со адреса 0Ah се чита
податок. Ако битовите 2 и 5 се 1 и 0 соодветно на мемориска
пресликана порта на адреса F00Ah се испраќа прочитаниот
податок поделен со 2, инаку се испраќа прочитаниот податок
помножен со 7. Фреквенцијата на кристалот на осцилаторот е
5MHz.


     If bit 2,5==1,0 
            F00Ah <- Data/2
     Else
            F00Ah <- Data*7



![sl1](https://github.com/dzabirskicvetan/8085--zad2/assets/171508405/f75c8df2-0ba9-475d-bb46-d897ab5a8a4b)
![sl2](https://github.com/dzabirskicvetan/8085--zad2/assets/171508405/f65ed467-7fce-4508-846e-f7b48ca43132)

 

**Developed by:**

(https://github.com/dzabirskicvetan)


**Subject**

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [8085 simulator](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file): Assembler and emulator for the Intel 8085 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8085 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using e8085.exe:

1. Download and install 8085 simulator from [here](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file).
2. Clone this repository to your local machine.
3. Open 8085 simulator and load the `zadaca1.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.
