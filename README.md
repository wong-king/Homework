# Homework
In this question, we shall use the following definitions. For any positive integer n, the hailstone
sequence H(n) is the sequence of numbers obtained from n by repeatedly applying the following
rule until the number becomes equal to 1:

• If the number is even, divide it by two; and

• If the number is odd, multiply it by three and add one.

The hailstone number h(n) is the length of the sequence H(n). As an example, H(5) = <16, 8, 4, 2, 1>
and thus h(5) = 5. Note that by definition, the starting number 5 is not included in the sequence H(5) itself. As another example, H(6) = <3, 10, 5, 16, 8, 4, 2, 1>, which gives h(6) = 8.

(a) Write a C function named hailstone with a parameter n of type unsigned int that computes
and returns h(n). The return type of hailstone should be unsigned int. 

(b) Write a C program that uses your function hailstone from part (a) to compute h(n) for all
n ∈ {1, 2, . . . , 30} and prints them in a table. Let the table have two columns: one for n and
one for h(n). Your program does not need to output H(n)
