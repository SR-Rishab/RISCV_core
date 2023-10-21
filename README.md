# RISCV core

## RV Day-3 Digital logic with TL-verilog and makerchip IDE
<details>
  <summary>Combinational logic in TL-verilog using makerchip</summary>

  ### 1. Full adder
     
  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/edd6e110-d13f-43a7-b8b5-a1f76f49825c)

  ### 2. Vectors 

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/50771ba7-22b6-4b2b-9019-2e993ad8d119)

  ### 3. 4:1 MUX
  
  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/91e129cc-5096-416c-a9cd-4ef04f4f3b9e)

  ### 4. Simple Calculator 

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/36f8da0e-07eb-422d-8092-429275b45c97)

</details>

<details>
  <summary>Sequential logic</summary>

  ### 1. Fibonacci series

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/d60959c5-383e-4f46-9041-aeb03585378b)

 ### 2. Up-counter

 ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/d4859a53-0528-440c-8cfa-fd5ed4fcf858)

 ### 3. Sequential calculator

 ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/006f4899-da30-43a5-b39a-59db34103213)
</details>

<details>
  <summary>Pipelined logic</summary>

  ### 1. Pipeline through pythogorean example

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/70d2003a-7d53-422f-8b5b-f0176363cafd)

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/d40fbf3c-2141-4e47-a4b4-2ffe0916f4bc)

  ### 2. Pipeline implementation

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/96dec07f-f46a-4384-8068-5df00be8ff0f)

  ### 3. 2-cycle calculator

  ![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/a265441f-d867-416f-93d8-a26b6895afe6)

</details>

## RV Day-4 Basic RISC-V CPU micro-architecture
<details>
  <summmary>Introduction to simple RISC-V micro-architecture</summmary>
The below diagram is a micro-architechture for a RISC-V implementation.
![image](https://github.com/SR-Rishab/RISCV_core/assets/107171044/81034c7d-2ec6-4c5d-9ef6-1836bcf6cc18)

  It consists of 
  - **Program counter**- Points to the instruction which to be executed.
  - **Instruction memory**- Stores the program instructions, it outputs the intruction to be executed.
  - **Decoder**- Decodes the instructions which can be present in different formats eg: I-format,R-format,U-format.
  - **Register file read**-Obtains the value present in the registers specified by the instruction.
  - **ALU**-For performing arithematic operations.
  - **Registers file write**-To perform write operations on registers.
  - **Memory**
</details>
 <details>
      <summary>Fetch and decode</summary>
    </details>
   <details>
      <summary>RISC-V control logic</summary>
    </details>
