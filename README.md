# Sage-BDN21

SageMath code for "Arithmetic and Thin Monodromy in Sp(6)" (Bajpai, Dona, Nitsche) 

The code deposited here refers to a SageMath program referring to the paper "Arithmetic and Thin Monodromy in Sp(6)" (available as arXiv:2112.12111v2), by Jitendra Bajpai, Daniele Dona, and Martin Nitsche.

The program is written in SageMath, version 8.9.

There are two files, one for the program itself, and the other for the inputs that verify the assertions of the paper.

There are two main functions in the first file, and the reader chooses which one to use depending on whether the order of the companion matrix of g. The function for the finite order case is designed to take two polynomials f,g and a matrix M, and find whether the cone spanned by the rays defined by the columns of M satisfies the structural requirements of Section 4.1. The function for the infinite order case works in the same way, but it may take either one matrix M or two matrices M,M1 depending on whether we wish to construct the cone D as well from the columns of M1.

The second file lists the 63 cases of thin groups collected in Tables 2 and 3, and the corresponding verification matrices of Sections 5 and 6. The reader can just append the relevant case at the end of the program file and compile to proceed with the verification. All outputs are "True".
