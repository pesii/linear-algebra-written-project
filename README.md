# linear-algebra-written-project

Code supplementing my 'written project' in Linear Algebra, Spring 2017.

This is a small implementation of the MixCol operation which is defined in the Rijndael (AES) algorithm, using trivial input. The objects we work with are from Galois Field (finite field) with 256 elements. The multiplication operation is defined in terms of polynomials while addition is defined by XOR'ing (^) the terms. 

Interesting Fact: A change in any elements (data) of the input vector would also change the resulting output vector.
