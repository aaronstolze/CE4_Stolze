CE4_Stolze
==========

Computer Exercise 4

# Analysis

## Program A 

The first program was fairly simple in its implementation.  In order to achieve the desired response, a new value would be placed into the accumulator and then stored in a position in the memory.  This was done by using the LDAI and STA commands.  The first value would be loaded into the accumulator by using the LDAI command.  Once the value was in the accumulator, it was stored at a desired position in the memory by linking the two locations by using the same label name. This was done for every value that needed to be stored. In order to prevent the program from continuing beyond what's necessary, an infinite loop was created at the end of the program.  


## Program B 

In order to complete this program, any random value had to first be placed into the B0 memory location.  After this value was placed, it was then taken from memory and loaded into the accumulator.  The value was then doubled by adding to it the same value from the B0 location.  This was achieved by using ADDD which took the value from the memory and added it to the accumulator value.  The value of 4 was subtracted by using ADDI which added the value given into the accumulator.  The final value was then output to Port 2 using the OUT command.  Once again an infinite loop was added in order to essentially terminate the continuation of the program.  

## Program C

This program took the value of whatever was in Input 3 by using the IN command.  Once it had this value, it was displayed on Port 0 by using the OUT command.  Ports 1 and 2 were then output by decrementing each successive Port by 1.  Essentially Port 1 will show 1 less than Port 0, and Port 2 will show 1 less than Port 1.  This was done using the ADDI command combined with the 2's complement of 1 which became $F.  The values were then output to their respective ports.  An infinite loop was added which started the program again from the first output in order to keep the process going indefinitely.      
