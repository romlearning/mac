# MAC
MAC is a really simple virtual machine. It's written in C and is [as of writing this]
only one small C file.

[Blog Post!](http://blog.felixangell.com/virtual-machine-in-c/)

Check out the [improved version](mac-improved/) to see an implementation of more instructions,
registers, etc...

## Instructions

	op   val    usage    			function
	---------------------------------------------------------------------
	HLT  0      hlt 	 			halts program
	PSH  1      psh val  			pushes <val> to stack
	POP  2      pop 	 			pops value from stack
	ADD  3      add 	 			adds top two vals on stack


Line 1
Line 2
Line 3

| Block cipher        | Performance, Mbit/s |
|---------------------|--------------------:|
| Kalyna-128/128      | 2611.77  |
| Kalyna-128/256      | 1779.52  |
| Kalyna-256/256      | 2017.97  |
| Kalyna-256/512      | 1560.89  |
| Kalyna-512/512      | 1386.46  |
| AES-128             | 2525.89  |
| AES-256             | 1993.53  |
| GOST 28147-89       | 639.18   |
| STB 34.101.31-2011  | 1055.92  |
| Kuznyechik          | 1081.08  |


| Block cipher        | Performance, Mbit/s |
|---------------------|--------------------:|
| Kalyna-128/128      | 1788.88  |
| Kalyna-128/256      | 1236.32  |
| Kalyna-256/256      | 1315.40  |
| Kalyna-256/512      | 1023.76  |
| Kalyna-512/512      | 1177.91  |
| AES-128             | 1645.97  |
| AES-256             | 1189.04  |
| GOST 28147-89       | 569.48  |
| STB 34.101.31-2011  | 936.66  |
| Kuznyechik          | 1158.67  |
