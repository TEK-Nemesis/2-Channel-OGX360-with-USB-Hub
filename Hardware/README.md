# Hardware

## Overview

For the most part, the OGX360s keep the same hardware.  This design uses mostly 0402 sized components in order to keep the PCB size to a minimum.  

### Part Sourcing

The majority of these parts can be purchased at Digikey however, at the time of writing this README, some stock was depleted there. 

**USB2422-I/MJ**: https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20210612110915&SearchText=USB2422-I%2FMJ

### Assembly Notes

Ensure to bridge the J1 points on the Arduino Pro 5V.  This will bypass the Arduino's voltage regulator and provide enough "juice" to safely run the ogx360 without the requirement of an external power source.

<img src="../Images/PCB.jpg" width="80%"/> 

