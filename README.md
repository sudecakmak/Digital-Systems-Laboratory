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
- [Flip Flop](#flip-flop)
  - [J-K Flip Flop](#j-k-flip-flop)
  - [IC 7476](#ic-7476)

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

![Screenshot 2022-11-11 134245](https://user-images.githubusercontent.com/102357822/201324524-5f1fd0f6-2e65-4ad7-b457-082f58582702.png)


## IC 7483

![Screenshot 2022-11-11 134327](https://user-images.githubusercontent.com/102357822/201324534-f5353036-8632-4389-ad8b-4e45257f3479.png)


# SR Latch

![Screenshot 2022-11-16 010631](https://user-images.githubusercontent.com/102357822/202035456-1b56413c-2d04-4556-80f9-35cafc80aad0.png)


# D Latch
![Screenshot 2022-11-20 223220](https://user-images.githubusercontent.com/102357822/202933342-d42412d2-a8c7-42c1-8e72-eb844a060ffd.png)


# Flip Flop

Implemented with IC 7476.

![Screenshot 2022-11-24 005413](https://user-images.githubusercontent.com/102357822/203652472-81623066-eb37-460c-a7f1-a37f59596334.png)


![Screenshot 2022-11-24 004510](https://user-images.githubusercontent.com/102357822/203652529-053a7a57-2328-4529-80f6-9265ce6e4090.png)

## Output Example
![Screenshot 2022-11-24 005321](https://user-images.githubusercontent.com/102357822/203652489-b8117994-0bea-4657-9cc0-92a7f6e09abc.png)

## IC 7476
![Screenshot 2022-11-24 004538](https://user-images.githubusercontent.com/102357822/203652615-53ac8ac8-222a-404a-9af1-96ba79ae8c1e.png)

## J-K Flip Flop
![Screenshot 2022-11-24 004618](https://user-images.githubusercontent.com/102357822/203652709-99c21b5d-023f-4740-acec-19c9d3468fcb.png)
