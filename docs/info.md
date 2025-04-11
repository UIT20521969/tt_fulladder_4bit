<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Full adder 4 bit with A and B in LSB

## How to test

The final truth table is the result of the sum of the above twice with a carry in and out function and the results. So what we need to do is on paper write down every possible sum and every possible result and if a carry was required.....thats a lot of sums!  Lets get to it:

    0000 
 + 0000
    0000 - no carry in and no carry out
    
    0000 
 + 0001
    0001 - no carry in and no carry out
    0001 
 + 0000
    0001 - no carry in and no carry out

    0001 
 + 0001
    0010 - no carry in and 1 carry out

    0010 
 + 0000
    0010 - no carry in and no carry out

etc etc etc....
![image](https://github.com/user-attachments/assets/9a8742f5-664b-4686-84a2-562e479091c8)
![image](https://github.com/user-attachments/assets/5656ce93-b544-481a-9054-9b7d8cffd16d)

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
