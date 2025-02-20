This creates a maze. It doesnt draw it but it does tell you where it has been and it always starts at (0,0). The visual grid is in the code at line 38.

The output will look something like this [5, 6, 1, 2, 7, 8, 13, 14, 9, 4, 3] it has gone from (0,0) to the 5th space to the 6th and so on until it reaches 3. 
You will notice that every cell around 3 being 2,8 and 4, have already been gone to, so now the code will go backwards until it finds a spot that it has not. 

In this example its 14, so the code will show itself going backwards.
[5, 6, 1, 2, 7, 8, 13, 14, 9, 4]
[5, 6, 1, 2, 7, 8, 13, 14, 9]

then it will go back to finding more spots 
[5, 6, 1, 2, 7, 8, 13, 14, 19, 24, 23, 18, 17, 16, 21, 22]
[5, 6, 1, 2, 7, 8, 13, 14, 19, 24, 23, 18, 17, 16, 21, 20, 15, 10, 11, 12]
