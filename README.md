# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
 A ^ B ^ ¬C
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	0
1	0	1	0
1	1	0	1
1	1	1	0

### b
A ^ ¬(B ^ ¬C)
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	1
1	0	1	1
1	1	0	0
1	1	1	1

### c
(A V ¬B) ^ (A V C)
A	B	C	Q
0	0	0	0
0	0	1	1
0	1	0	0
0	1	1	0
1	0	0	1
1	0	1	1
1	1	0	1
1	1	1	1

### d
A ^ ¬(B V ¬C) ^ (¬A ^ D)
A	B	C	D	Q
0	0	0	0	0
0	0	0	1	0
0	0	1	0	0
0	0	1	1	0
0	1	0	0	0
0	1	0	1	0
0	1	1	0	0
0	1	1	1	0
1	0	0	0	0
1	0	0	1	0
1	0	1	0	0
1	0	1	1	0
1	1	0	0	0
1	1	0	1	0
1	1	1	0	0
1	1	1	1	0

## Question 2

### a
A ^ B ^ ¬C
https://imgur.com/a/LaU0xDD
### b
A ^ ¬(B ^ ¬C)
https://imgur.com/a/LaU0xDD
### c
(A V ¬B) ^ (A V C)
https://imgur.com/a/LaU0xDD
### d
A ^ ¬(B V ¬C) ^ (¬A ^ D)
https://imgur.com/a/LaU0xDD

## Question 3

### a
¬(A V B)
A	B	Q
0	0	1
0	1	0
1	0	0
1	1	0

¬A ^ ¬B
A	B	Q
0	0	1
0	1	0
1	0	0
1	1	0

### b
¬(A ^ B)
A	B	Q
0	0	1
0	1	1
1	0	1
1	1	0

¬A V ¬B
A	B	Q
0	0	1
0	1	1
1	0	1
1	1	0

### c
(A ^ B) V (A ^ C)
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	0
1	0	1	1
1	1	0	1
1	1	1	1

A ^ (B V C)
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	0
1	0	1	1
1	1	0	1
1	1	1	1

### d
(A V B) ^ (A V C)
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	1
1	0	0	1
1	0	1	1
1	1	0	1
1	1	1	1

A V (B ^ C)
A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	0
1	0	0	0
1	0	1	1
1	1	0	1
1	1	1	1

## Question 4

### a
¬A ^ B = ¬(A V B)
A	B	Q
0	0	0
0	1	1
1	0	0
1	1	0

A	B	Q
0	0	1
0	1	1
1	0	1
1	1	0
They are not the same result?
0100 != 1110

### b
IF (A ^ C) V (B ^ C) = IF (A V B) ^ C
Where A = type(x) == int, B = type(x) == float, C = x > 7

### c
A ^ B → Q = ¬A V ¬B → ¬Q
Where A = X==0, B = Y==0, Q == do_somthing()
A	B	Q
0	0	0
0	1	0
1	0	0
1	1	1

A	B	Q
0	0	0
0	1	0
1	0	0
1	1	1

### d
A V (B ^ C) = B ^ (A V C)
Where A = X > 10, B = X > 0, C = Y > 0

A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	1
1	0	0	0
1	0	1	0
1	1	0	0
1	1	1	1

A	B	C	Q
0	0	0	0
0	0	1	0
0	1	0	0
0	1	1	1
1	0	0	0
1	0	1	0
1	1	0	1
1	1	1	1
00010001 != 00010011?
