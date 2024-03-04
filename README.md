# 4-Week-VSD-internship

### BOARD SPECIFICATIONS

Board	Name- VSDSquadron Mini

Microcontroller- CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set

USB connector	USB 2.0 Type-C

Pins:
  1) Built-in LED Pin- 1X onboard user led (PD6)
  2) 15 Digital I/O pins
  3) 10-bit ADC, PD0-PD7, PA1, PA2, PC4 Analog I/O pins
  4) 14X PWM pins
  5) 8 external interrupt edge detectors, but it only maps one external interrupt to 18 I/O ports

Communication:
  1) USART- 1x, PD6(RX), PD5(TX)
  2) I2C- 1x, PC1(SDA), PC2(SCL)
  3) SPI- 1x, PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO)
  4) Onboard RISC-V programmer/debugger, USB to TTL serial port support

I/O voltage- 3.3 V

Input voltage (nominal)-	5 V

Source Current per I/O Pin-	8 mA

Sink Current per I/O Pin-	8 mA

Clock speed- Processor	24 MHz

Memory- 2kb onchip volatile sram,16kb external program memory

## Task 1- Installing Libraries

sudo apt install git-all

### Installing Yosys

git clone https://github.com/YosysHQ/yosys.git 

cd yosys

sudo apt install make

sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev

make config-gcc

make

sudo make install

![Yosys](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/a5426693-5e25-4400-a01e-bbbeaddcc082)
![Yosys1](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/0e5dbb85-c540-4d9e-89ce-f6f8746c67ee)
![Screenshot 2024-03-02 185612](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/d4edb2b9-e926-465c-a42f-e81b0bd320c5)
![Screenshot 2024-03-02 190403](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/bc0c9dec-eb3c-4081-9d4e-4d77d1f8a941)

### Installing iVerilog

sudo apt update

sudo apt-get install iverilog

![iverilog](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/a8ea274b-d2e9-4b65-b0e0-1c18f639a40e)

### Installing GTKwave

sudo apt-get install gtkwave

![GTKWave](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/ecf04608-caa6-418b-803b-fddc9783dbb2)

## Taks 2- Universal Asynchronous Receiver Transmitter Protocol based Hardware Transmitter

### Block Diagram

![image](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/73f69cee-add4-4361-91b6-4c96492db2eb)

### Input Waveform

<img width="905" alt="input waveform" src="https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/e36c148c-fba0-49f3-b15c-12d240853c9b">

### Output Waveform

<img width="956" alt="output waveform" src="https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/3488956f-4de2-48fb-92ca-c9c127e2be21">

## Task 3

![task3](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/3fd9b911-cdf0-4976-8a95-7b1da9790d10)

![Screenshot 2024-03-03 115401](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/bcc48322-6eed-4c8d-895a-46420391f1bc)

## Task 4

![Screenshot 2024-03-04 205520](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/b0c96cd7-8e00-4a19-a741-8af17b5432a3)

![Screenshot 2024-03-04 205536](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/972faa78-2058-4cd5-bac2-bb98f9d862ea)

![Screenshot 2024-03-04 205613](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/60cdabd5-ed53-48c4-a2d2-c123cff29c36)

![Screenshot 2024-03-04 205632](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/f7911e6a-5228-4459-930c-cedfba4f7648)

![Screenshot 2024-03-04 205649](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/0b637d08-006a-41e7-9fea-8009dfbf25b4)

![Screenshot 2024-03-04 143722](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/c03423bb-425b-488f-b92a-f4d85c8c268b)

![Screenshot 2024-03-04 204508](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/a1920b5c-0427-4f3c-afc6-d63d2bbec626)

![Screenshot 2024-03-04 204540](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/b8be2eb1-6570-462a-86ae-dcc28a15b502)

![Screenshot 2024-03-04 204604](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/7c0cd730-10d5-4f3f-81da-702d1ac1306c)

![Screenshot 2024-03-04 204629](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/66ac6da6-8caf-4afd-a5dc-4a4349f63837)

![Screenshot 2024-03-04 204726](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/47af2ec9-6fff-4ab5-9e10-6da118bd2da8)

![Screenshot 2024-03-04 204755](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/0415ea4c-82c4-435e-841c-c93b3e3acc1c)

![Screenshot 2024-03-04 204826](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/89ae08cd-8dbe-4267-a640-73dacc7171c5)

![Screenshot 2024-03-04 204851](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/05e4f227-a9e3-4980-beb4-8ac56cef87d0)

![Screenshot 2024-03-04 204936](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/25ee449d-6017-4093-a26d-d8b4a0e989d3)

![SC2](https://github.com/nayakmaithreyi/4-Week-VSD-internship/assets/160585878/ef328afa-51fa-4dab-bace-87e0c92b8b72)
