# PongForCalliope
Pong for two Calliope Mini and one LED-Matrix (Adafruit NeoPixel 8X8)

A live presentation/trailer thingy: https://youtu.be/MS8AlEOjadA

If you want to build it yourself you will need to get two Calliope Mini and one Adafruit NeoPixel 8X8.

- connect the Calliopes together at ground
- connect P0 from Calliope A to P1 from Calliope B
- connect P1 from Calliope A to P0 from Calliope B
- connect the NeoPixel to C16
- it needs to look something like this: https://imgur.com/mdsuK7t 
- flash mini-pa.hex on Calliope A
- flash mini-pb.hex on Calliope B

If you want to use other pins you will need to change these in the code.

In the code the variables have german names but I commented this whole thing in english in the Javascript side of things. For programming I used https://makecode.calliope.cc.
