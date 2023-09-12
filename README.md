# 32-bit-carry-look-ahead-adder

A carry-look ahead adder (CLA) or fast adder is a type of electronics adder used in digital logic. A carry-look ahead
adder improves speed by reducing the amount of time required to determine carry bits. The carry generated by the full 
adder in the least significant bit stage must propagate through all the intermediate adders till it reaches the most 
significant bit adder .The sum and carry out of any stage depends on the carry output of the previous stage. The carry 
out of previous stage depends on the carry out of the stage prior to that and so on .So if we ensure that the sum and 
carry out of any stage is not dependent on the results of any previous stages then the ripple effect is eliminated and the 
speed of addition increases. The carry-look ahead adder calculates one or more carry bits before the sum, which 
reduces the wait time to calculate the result of the larger-value bits of the adder.

