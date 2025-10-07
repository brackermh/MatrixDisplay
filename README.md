# **FPGA driven LED Matrix Display**

Project that Displays a diamond bouncing off the corners in a pseudo-random fashion on the 32x32 HUB75 LED matrix display board using a Basys 3 Artix-7 FPGA.

___________________________________________________________
Pin-Out for use [Format : VHDL Signal <- Pin name (pin #)]:

RGB1(0) <- R0 (red / pin 1)

RGB1(1) <- G0 (green / pin 2)

RGB1(2) <- B0 (blue / pin 3)

RGB2(0) <- R1 (red / pin 5)

RGB2(1) <- G1 (green / pin 6)

RGB2(2) <- B1 (blue / pin 7)

a(0) <- A0 (pin 9)

a(1) <- A0 (pin 10)

a(2) <- A0 (pin 11)

a(3) <- A0 (pin 12)

SCLK <- Clock (pin 13)

Latch <- latch (pin 14)

Blank <- blank (pin 15)

____________________________________________________________
