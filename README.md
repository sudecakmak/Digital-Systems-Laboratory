# Digital-Systems-Laboratory
Projects I made in Introduction to Microcomputers. I used Logisim for my projects.

## Table of Contents

- [Parity bit generator circuit](#parity-bit-generator-circuit)
- [Combinational logic circuit](#combinational-logic-circuit)
- [Half adder circuit](#half-adder-circuit)
- [Full adder circuit](#full-adder-circuit)
- [Adder or Subtractor circuit](#adder-or-subtractor-circuit)
  - [IC 7483](#ic-7483)
- [SR Latch](#sr-latch)
- [D Latch](#d-latch)
- [Flip Flop 1](#flip-flop-1)
  - [J-K Flip Flop](#j-k-flip-flop)
  - [IC 7476](#ic-7476)
- [Flip Flop 2](#flip-flop-2)
  - [D Flip Flop](#d-flip-flop)
  - [IC 7474](#ic-7474)
- [Mealy Machine](#mealy-machine)
  
# Parity bit generator circuit 

with 4 line-to-1 line multiplexer and external gates.

> It is combinational circuit that accepts an n-1 bit data and generates the additional bit that is to be transmitted with the bit stream. This additional or extra bit is called as a **Parity Bit**.

![Screenshot 2022-10-30 123315](https://user-images.githubusercontent.com/102357822/198871889-6bed9be5-871e-4ebf-9d15-d30d03c5389d.png)


# Combinational logic circuit

•	If A+B is EVEN, Z1Z2=01

•	If A+B is ODD, Z1Z2=10

with 3-to-8 line decoders and external logic gates.

![Screenshot 2022-10-30 123409](https://user-images.githubusercontent.com/102357822/198871891-021ccaf9-9ff0-4d1e-8487-094647c7471e.png)


# Half adder circuit

using only XOR and NAND gates.

> Half Adder is a combinational logic circuit which is designed by connecting one XOR gate and one NAND gate. The half adder circuit has **two inputs**: A and B, which add two input digits and generates a **carry and a sum**. The output obtained from the XOR gate is the sum of the two numbers while that obtained by NAND gate is the carry. 

![half](https://user-images.githubusercontent.com/102357822/200165800-b05408c4-f2a9-45da-b6f1-233abed289df.png)

## Output Example
![Screenshot 2022-11-21 030802](https://user-images.githubusercontent.com/102357822/202934254-eac21488-5ed9-4655-a823-cf25f36b9c3b.png)


# Full adder circuit

using only XOR and NAND gates.

> Full Adder is the circuit that consists of two XOR gates and three NAND gates. Full Adder is the adder that adds **three inputs** and produces two outputs which consist of two XOR gates and three NAND gates. The first two inputs are A and B and the third input is an input carry as **C-IN**. The output carry is designated as **C-OUT** and the normal output is designated as S which is SUM. The equation obtained by the XOR gate is the sum of the binary digits. While the output obtained by NAND gate is the carry obtained by addition. 

![full](https://user-images.githubusercontent.com/102357822/200165823-4236fc2b-4dc1-4796-bfea-26961be6cf0a.png)

## Output Example
![Screenshot 2022-11-21 031113](https://user-images.githubusercontent.com/102357822/202934267-83126154-8757-4ff8-8fc4-ea46a6af8a9a.png)

# Adder or Subtractor circuit

Implemented with IC 7483. The circuit uses signed 2’s complement system for negative numbers.

> A Binary Adder-Subtractor is one that is capable of both the addition and subtraction of binary numbers in one circuit itself. The operation is performed depending on the binary value the control signal holds. It is one of the components of the ALU (Arithmetic Logic Unit). 

![Screenshot 2022-11-11 134245](https://user-images.githubusercontent.com/102357822/201324524-5f1fd0f6-2e65-4ad7-b457-082f58582702.png)

## Output Example
![Screenshot 2022-11-24 010929](https://user-images.githubusercontent.com/102357822/203654362-77aa3b1d-deb5-4c5d-a6a8-1a9b51d0b304.png)


## IC 7483

![Screenshot 2022-11-11 134327](https://user-images.githubusercontent.com/102357822/201324534-f5353036-8632-4389-ad8b-4e45257f3479.png)


# SR Latch

![Screenshot 2022-11-16 010631](https://user-images.githubusercontent.com/102357822/202035456-1b56413c-2d04-4556-80f9-35cafc80aad0.png)


# D Latch

> A D Flip Flop (also known as a D Latch or a ‘data’ or ‘delay’ flip-flop) is a type of flip flop that tracks the input, making transitions with match those of the input D. The D stands for ‘data’, this flip-flop stores the value that is on the data line. It can be thought of as a basic memory cell.


![Screenshot 2022-11-24 011356](https://user-images.githubusercontent.com/102357822/203654899-9a2bc4e9-b60a-44a2-be45-a4b886b34b15.png)

![Screenshot 2022-11-20 223220](https://user-images.githubusercontent.com/102357822/202933342-d42412d2-a8c7-42c1-8e72-eb844a060ffd.png)

## Output Example
![Screenshot 2022-11-24 011304](https://user-images.githubusercontent.com/102357822/203654963-266739ed-b1aa-4d19-968d-9af4f66995cb.png)


# Flip Flop 1

Implemented with IC 7476.

![Screenshot 2022-11-24 005413](https://user-images.githubusercontent.com/102357822/203652472-81623066-eb37-460c-a7f1-a37f59596334.png)

![Screenshot 2022-11-24 004510](https://user-images.githubusercontent.com/102357822/203652529-053a7a57-2328-4529-80f6-9265ce6e4090.png)

## Output Example
![Screenshot 2022-11-24 005321](https://user-images.githubusercontent.com/102357822/203652489-b8117994-0bea-4657-9cc0-92a7f6e09abc.png)

## IC 7476
![Screenshot 2022-11-24 004538](https://user-images.githubusercontent.com/102357822/203652615-53ac8ac8-222a-404a-9af1-96ba79ae8c1e.png)

## J-K Flip Flop
![Screenshot 2022-11-24 004618](https://user-images.githubusercontent.com/102357822/203652709-99c21b5d-023f-4740-acec-19c9d3468fcb.png)


# Flip Flop 2

Implemented with IC 7474.

![Screenshot 2022-11-27 202922](https://user-images.githubusercontent.com/102357822/204150656-93bf0343-c06d-4ec8-bd5a-a6de38ae464a.png)

![Screenshot 2022-11-27 201615](https://user-images.githubusercontent.com/102357822/204150221-9cfb9670-1f28-490d-b4b8-0ce037f5a4f2.png)


## Output Example
![Screenshot 2022-11-27 202945](https://user-images.githubusercontent.com/102357822/204150722-16685484-eb0e-4949-bfcc-d0a71a3428cc.png)


## IC 7474
![Screenshot 2022-11-27 201639](https://user-images.githubusercontent.com/102357822/204150237-249a81cb-ee38-4d80-83e5-19d92252e3fc.png)

## D Flip Flop
![Screenshot 2022-11-27 201710](https://user-images.githubusercontent.com/102357822/204150812-8baf1418-7928-423d-8e1c-4612eb45f942.png)


# Mealy Machine
A synchronous sequential circuit with one input x, and one output z. When x=1, this circuit goes through the following repeated binary state sequence: 00, 01, 11, 10. When x=0, the state of the circuit remains the same. The output z=1 if the present state is either 00 or 11.

![Screenshot 2022-11-28 211823](https://user-images.githubusercontent.com/102357822/204352151-3deb9560-d307-4e52-ae92-1fdf089bb45c.png)

