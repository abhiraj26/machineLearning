<b>Module 1 coverage: </b>
1. Rule of sum : n objects of first type and k objects of second type , so there are n+k objects of one of two types.
2. Rule of Product : n objects of the first type and k objects of second type and you want to select a pair then there are n*k objects of the first and second type.
3. Tuples : sequences of length k out of n symbols (symbols can be repeated) then total symbols are n^k.
4. Sets : n objects of first type and k objects of second type , so there are occ(n) + occ(k) - occ(n and k). occ-> occurence
5. k-Permutations : sequences of length k with no repetitions composed out of n symbols : n*(n-1)....*(n-k+1) = nPk

<b>Module 2 coverage: </b>
1. Combinatorics : sequences of length k in which order doesn't matter to be placed by n symbols n*(n-1)..(n-k+1) divided by k! as everything will be repeated k times -> nCk => (n k) => n choose k. Combinations are also called as substes.
n C k = n C n-k <br>
n C k = n!/(k! * (n-k)!)  <br>
2. Pascal's Triangle : nCk = n-1 C k-1 + n-1 C k  <br>
nC0 +.. nCk + .. nCn = 2^n   <br>
0  = nEk(Even) = nOk (Odd) = (-1)^k nCk  , n>0   <br>
nC1 + nC3 + ... = nc0 + nC2 + ..   <br>
(a+b)^n = nC0a^n + ... nCk a^n-k b^k + .. + nCn b^n <br>

<b> Module 3 coverage: </b>

                         With Repetitions    |   Without Repetitions
            Ordered   | (Tuples) n^k         |   (Permutations) nPk
            Unordered | (k+n-1) C (n-1)      |   (Combinations) nCk

Combinations With repetitions: (k+n-1)C(n-1) , n -> number of things to place, k-> total size, so (n-1) delimiter. <br> Suppose there are 3 items to be placed on a rack of 10. n = 3, k=10 (Repetitions allowed). So you will mark (n-1) 2 delimiters extra and add it to k positions. Now you simply have to choose these (n-1) delimiters positions in these n+k-1 options. 

<b> Module 4 coverage: </b>
<br> Probability

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

Probability cases:
1. Non Equiprobable Outcmoes. 
2. Disjoint set of outcomes || Not disjoint set.
3. Sequentional Choice
