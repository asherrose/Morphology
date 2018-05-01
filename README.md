# Morphology
Implementation of the four Elementry Morphology Operations

1 Input1 (argv[1]): a txt file representing a binary image with header.

 2. Input2 (argv[2]): a txt file representing a binary image of a structuring element 
   with header and the origin of the structuring element. The format of the structuring element is as follows: 
   1th text line is the ordinary image header; the 2nd text line is the position (w.r.t. index) of the origin, 
   then follows by the rows and column of the structuring element.
II. OutPuts:
	- Console output 
	- Output1 (argv[3]): the result of dilation image with header, should be the same dimension as input1
     	- Output2 (args[4]): the result of erosion image with header, should be the same dimension as input1
    	- Output3 (args[5]): the result of closing image with header, should be the same dimension as input1
    	- Output4 (args[6]): the result of opening image with header, should be the same dimension as input1
