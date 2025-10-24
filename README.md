# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.


<img width="915" height="556" alt="Screenshot 2025-10-24 100856" src="https://github.com/user-attachments/assets/40f6b669-7880-492f-832b-62d283746fec" />

Developed by:VISHAL R RegisterNumber:25004464

*/

**RTL LOGIC FOR SISO Shift Register**


<img width="1202" height="691" alt="Screenshot 2025-10-24 100918" src="https://github.com/user-attachments/assets/8f3a4da3-6455-4c0e-bde2-6345b048455d" />

**TIMING DIGRAMS FOR SISO Shift Register**



<img width="1203" height="278" alt="Screenshot 2025-10-24 100934" src="https://github.com/user-attachments/assets/b94b0057-c5a2-4928-a175-f9794777f681" />

**RESULTS**
Thus, the Serial-In Serial-Out (SISO) Shift Register is implemented using Verilog, and its functionality is validated with the truth table and timing diagrams.
