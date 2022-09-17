# Sage-BDN21

SageMath code for "Thin Monodromy in Sp(4) and Sp(6)" (Bajpai, Dona, Nitsche) 

The code deposited here refers to a SageMath program referring to the paper "Thin Monodromy in Sp(4) and Sp(6)" (available as arXiv:2112.12111v3), by Jitendra Bajpai, Daniele Dona, and Martin Nitsche. Any licence that may apply to the paper "Thin Monodromy in Sp(4) and Sp(6)" applies to all the files contained here as well.

The program is written in SageMath, version 8.9.

There are two files, one for the program itself ("Program"), and the other for the inputs that verify the assertions of the paper ("Cases").

There are two main functions in the file "Program", and the reader chooses which one to use depending on whether the order of the companion matrix of g. The function for the finite order case is designed to take two polynomials f,g and a matrix M, and find whether the cone spanned by the rays defined by the columns of M satisfies the structural requirements of Section 3.1. The function for the infinite order case works in the same way, but it may take either one matrix M or two matrices M,M1 depending on whether we wish to construct the cone D as well from the columns of M1.

The file "Cases" lists the 66 cases of thin groups collected in Tables 1-2-4, and the corresponding verification matrices of Sections 4-5-6. The reader can just append the relevant case at the end of the program file and compile to proceed with the verification. All outputs are "True".
