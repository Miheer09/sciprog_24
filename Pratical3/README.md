## Practical03
This is the third practical where the code approximates the integral of the tangent function from $0^o$C to $60^o$C using the trapezoidal rule and compares this value with the actucal value of log(2).
There are loops to add contributions from various angles, looks for even angle and output the relevant results.

## Complie
*gcc -0 trap trap.c -lm
* gcc -0 printf use_printf.c -lm

# Execute:
* ./trap

output:

The value of sum before the loop is:1.732051
I am even and here's the value of sum: 1.907028
I am even and here's the value of sum: 2.795581
I am even and here's the value of sum: 4.456137
I am even and here's the value of sum: 7.011252
I am even and here's the value of sum: 10.689451
I am even and here's the value of sum: 15.929254
The value of sum after the loop is:15.929254
The final value of the sum is : 0.695045
The actual value is : 0.693147
abs diff = 0.001898
 rel_diff = 0.002738

* ./printf

Two ints 10 200 and two floats 1.110000 2.222200