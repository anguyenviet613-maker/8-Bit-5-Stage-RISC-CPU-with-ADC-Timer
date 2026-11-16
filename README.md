NGUYEN VIET ANH - SE204450

# 8-Bit-5-Stage-RISC-CPU-with-ADC-Timer
An 8-bit System-on-Chip (SoC) featuring a custom 5-stage pipelined RISC CPU integrated with a Timer and SAR ADC controller via an Advanced Peripheral Bus (APB) interface. Developed in Verilog and verified using a Universal Verification Methodology (UVM) testbench in SystemVerilog. The system uses custom assembly firmware (`soc_demo.s`) compiled into machine code to verify.

How to Run
1. Clone the repository and open Vivado.
2. Add the RTL source files and Testbench files to your Simulation Sources (remember to add in the TB_UVM if you also use the ADC and Timer).
3. Ensure `soc_demo.hex` is classified as a **Memory Initialization File** in Vivado.
4. Run Behavioral Simulation to observe the boot sequence, peripheral configuration, steady-state PWM generation and the ADC converting the values.
