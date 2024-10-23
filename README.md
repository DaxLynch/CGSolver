# LUPDecomp
Implementation of a LUP decomposition in Julia
I was proud of this work because the teacher had taught us a relatively naive algorithm of calculating the intermediate L_k matrices. After some work I figured out a much simpler method. So instead of performing a product of N matrices, L1 . . . LN , I can just keep adding ℓk vector to the matrix at each step, swapping an O(N^3) matrix multiply for an O(N) column operation.
