<h2><b>Module 1 coverage: </b></h2>
<li>
1. Rule of sum : n objects of first type and k objects of second type , so there are n+k objects of one of two types. <br>
2. Rule of Product : n objects of the first type and k objects of second type and you want to select a pair then there are n*k objects of the first and second type. <br>
3. Tuples : sequences of length k out of n symbols (symbols can be repeated) then total symbols are n^k. <br>
4. Sets : n objects of first type and k objects of second type , so there are occ(n) + occ(k) - occ(n and k). occ-> occurence <br>
5. k-Permutations : sequences of length k with no repetitions composed out of n symbols : n*(n-1)....*(n-k+1) = nPk <br>
</li>
<br>
<h2><b>Module 2 coverage: </b></h2>
1. Combinatorics : sequences of length k in which order doesn't matter to be placed by n symbols n*(n-1)..(n-k+1) divided by k! as everything will be repeated k times -> nCk => (n k) => n choose k. Combinations are also called as substes. <br>
n C k = n C n-k <br>
n C k = n!/(k! * (n-k)!)  <br>
2. Pascal's Triangle : nCk = n-1 C k-1 + n-1 C k  <br>
nC0 +.. nCk + .. nCn = 2^n   <br>
0  = nEk(Even) = nOk (Odd) = (-1)^k nCk  , n>0   <br>
nC1 + nC3 + ... = nc0 + nC2 + ..   <br>
(a+b)^n = nC0a^n + ... nCk a^n-k b^k + .. + nCn b^n <br>

<h2><b> Module 3 coverage: </b></h2>

                         With Repetitions    |   Without Repetitions 
            Ordered   | (Tuples) n^k         |   (Permutations) nPk  
            Unordered | (k+n-1) C (n-1)      |   (Combinations) nCk  

Combinations With repetitions: (k+n-1)C(n-1) , n -> number of things to place, k-> total size, so (n-1) delimiter. <br> 
Suppose there are 3 items to be placed on a rack of 10. n = 3, k=10 (Repetitions allowed). So you will mark (n-1) 2 delimiters extra and add it to k positions. Now you simply have to choose these (n-1) delimiters positions in these n+k-1 options. 

<h2><b> Module 4 coverage: </b></h2>
<br> Probability

Paradox of probability theory:- Values actually become more equivalent to its probability after a long set of iterations.  <br>
Galton Board:- Pascal triangle problem <br>
Probability theory -> Distinction between mathematical and natural science. We assume <b>independence and equally likely</b> while computing probability. <br>

<b>Terminologies:</b> <br>
<b>Probability Space:</b> All outcomes <br>
<b>Event:</b> Some outcome(favourable) <br>
<b>Probability:</b> (#favorable)/total events <br>

3 types of distribution in probability: (Other than equally likely!) <br>
1. Non-Uniform distributions <br>
2. Unknow distributions <br>
3. Continous distributions <br>

<b>Probability cases:</b> <br>
1. Non Equiprobable Outcomes.  <br>
2. Disjoint set of outcomes || Not disjoint set. <br>
3. Sequentional Choice <br>

<b>Probability:</b> If A and B are mutually exclusive P[A or B] = P[A] + P[B]. <br>
P[A and B] = 0 <br>

If A and B are not mutually exclusive, P[A or B] = P[A] + P[B] - P[A and B] <br>

<b>Question:</b> Optimize the chances of getting a white ball. There are 2 bags and a total of 15 white and 15 black balls. Atleast one ball is required in each bag. <br>

<b>Answer:</b> Put 1 white and 0 black in bag1 and put 14 white and 15 black in bag2. <br>

<b>Conditional probability: </b><br> 
P[A and B] = P[A] * P[B/A] <br>

False positive and false negative can easily be shown with the use of conditional probability. <br>

P[A] = P[B].P[A/B] + (1-P[B]) P[A/ not B]   <br>

<b>Bayes theorem:</b> <br>
H for hypothesis, E for evidence
(arbitary two events having a common probability space) 
P[H/E] = P[H and E] / P[E] = (P[E/H] * P[H]) / P[E]

<b>For independent events: </b>
P[A and B] = P[A].P[B]

<h2><b> Module 5 coverage: </b></h2>
<b>Random Variables:</b> They are usualy represented by upper case characters. It is used to quantify the output of a probabilty so a lot more operations can be performed on it. <br> <br>

Eg. X = { 0 if head, 1 if tail } <br>

<b>Expected value</b> is the average value of the random variable. <br>
Expectation is calculated as a1p1 + a2p2 + .... (a(random variable) is the value of each outcome, p is probability of each outcome.)

<b>Linearity of Expectation:</b> If f ang g are random variables on the same probability space then the following hold: <br>
E(f+g) = E(f) + E(g) <br>

<b>Example of linearity expectation:</b> Suppose we throw 2 dices, what is the probablity of expectation of sum of the 2 dices. <br>

E(f+g) = E(3.5) + E(3.5) // For each dice, so expectation is 7.  <br>
 
<b>Markov's Inequality:</b> Suppose that f is a non negative random variable. Then for any number a>0 we have <b>P[f>=a] <= E[f]/a</b> <br>
