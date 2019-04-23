Module 1 coverage:
1. Rule of sum : n objects of first type and k objects of second type , so there are n+k objects of one of two types.
2. Rule of Product : n objects of the first type and k objects of second type and you want to select a pair then there are n*k objects of the first and second type.
3. Tuples : sequences of length k out of n symbols (symbols can be repeated) then total symbols are n^k.
4. Sets : n objects of first type and k objects of second type , so there are occ(n) + occ(k) - occ(n and k). occ-> occurence
5. k-Permutations : sequences of length k with no repetitions composed out of n symbols : n*(n-1)....*(n-k+1) = nPk

Module 2 coverage: 
1. Combinatorics : sequences of length k in which order doesn't matter to be placed by n symbols n*(n-1)..(n-k+1) divided by k as everything will be repeated k times -> nCk => (n k) => n choose k. Combinations are also called as substes.
n C k = n C n-k
n C k = n!/(k! * (n-k)!)
2. Pascal's Triangle : nCk = n-1 C k-1 + n-1 C k
nC0 +.. nCk + .. nCn = 2^n
0  = nEk(Even) = nOk (Odd) = (-1)^k nCk  , n>0
nC1 + nC3 + ... = nc0 + nC2 + ..
(a+b)^n = nC0a^n + ... nCk a^n-k b^k + .. + nCn b^n

Module 3 coverage: 
            With Repetitions              Without Repetitions
Ordered          (Tuples)n^k              (Permutations) nPk
Unordered   (k+n-1) C (n-1)               (Combinations) nCk

Combinations With repetitions: (k+n-1)C(n-1) , n -> number of things to place, k-> total size, so (n-1) delimiter 

Module 4 coverage: Probability

Paradox of probability theory:- Values actually become more equivalent to its probability after a long set of iterations. 
Galton Board:- Pascal triangle problem
Probability theory -> Distinction between mathematical and natural science. We assume <b>independence and equally likely</b> while computing probability.

Terminologies:
Probability Space: All outcomes
Event: Some outcome(favourable)
Probability: (#favorable)/total events

3 types of distribution in probability: (Other than equally likely!)
1. Non-Uniform distributions
2. Unknow distributions
3. Continous distributions

Probility cases:
1. Non Equiprobable Outcmoes. 
2. Disjoint set of outcomes || Not disjoint set.
3. Sequentional Choice
