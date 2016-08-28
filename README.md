# dismathportfolio-kylereyes
Kyle Reyes 11048166 

Week 1:
</br>
+ I learned what are propositions. Propositions are sentences that declares a fact that is either true or false.
+ I learned that proposition has operations like the negation is the NOT in the logic circuits, conjuntion is the AND, disjunction is the OR and exclusive or is XOR.
+ I learned that propositions can be combinded using conditional statement. The conditional statement is like a promise like our prof said. The example that the prof has given us  is that "If you get a 100% in the finals, the prof will give us a 4.0 grade" in the example if we get a 100% in the finals then we will get a 4.0 grade then both statements are true but the 2nd statement can also be true even if we don't get a 100% in the finals.
+ I learned that there are different kinds of conditional statements. These are Converse, Contrapositive and Inverse
+ I learned that there is also a biconditional statement where the given p ↔ q. The statement can only be true if p → q are true and q → p are also true. both statements should be true for biconditional statement to be true.
</br></br>
Assignment #1
</br>
1.1</br>
33a. (p v q) → (p ⊕ q)
</br>
| p | q | (p v q) → (p ⊕ q) |</br>
| T | T |         F          |</br>
| T | F |         T          |</br>
| F | T |         T          |</br>
| F | F |         T          |</br>
</br>
35b. ¬p ↔ q
</br>
| p | q | ¬p ↔ q |</br>
| T | T |    F   |</br>
| T | F |    T   |</br>
| F | T |    T   |</br>
| F | F |    F   |</br>
</br>
37c. (p → q) v (¬p → r)
</br>
| p | q | r | (p → q) v (¬p → r) |</br>
| T | T | T |         T          |</br>
| T | T | F |         T          |</br>
| T | F | T |         T          |</br>
| T | F | F |         T          |</br>
| F | T | T |         T          |</br>
| F | T | F |         T          |</br>
| F | F | T |         T          |</br>
| F | F | F |         T          |</br>

Week 2:
</br>
+ I learned about compound propositions. there are the Tautology which is always true, Contradiction which is always false and Contingency which is nether true nor false.
+ I learned about the logical equivalence. there are the Identity Laws, Domination Laws, Indepotent Laws, Double negation Law, Commutative Law, Associative Law, Distributive Law, De Morgan's Law, Absorption Law and Negation Law. There are also logical equivalences involving condtional and biconditonal statements.
+ I learned about Quantifiers. There are the Universal quantifier which is "for all" where it is true if all are true and Exixtential quantifier which is "there exist" where it is true if there is one  true.
+ I learned about the Rules of Inference. There are Modus Ponens, Modus Tollens, Hypothetical Syllogism, Disjunctive Syllogism, Addition, Simplification, Conjunction and Resolution.
</br></br>
Assignment #2
</br>
1.5</br>
 7.Let T (x, y) mean that student x likes cuisine y, where the domain for x consists of all students at your school and the domain for y consists of all cuisines. Express each of these statements by a simple English sentence.</br>
a. ¬T (Abdallah Hussein, Japanese) Answer: Abdalla Hussein does not like japanese cuisine
</br></br>
 9.Let L(x, y) be the statement “x loves y,” where the domain for both x and y consists of all people in the world. Use quantifiers to express each of these statements.</br>
b.Everybody loves somebody Answer:  ∀x∃yL(x,y)</br>
i.Everyone loves himself or herself Answer: ∀xL(x,x)</br></br>
1.6</br>
35.Determine whether this argument, taken from Kalish and Montague [KaMo64], is valid.</br>
If Superman were able and willing to prevent evil,he would do so. If Superman were unable to prevent evil, he would be impotent; if he were unwilling to prevent evil, he would be malevolent. Superman does not prevent evil. If Superman exists, he is neither impotent nor malevolent. Therefore, Superman does not exist.</br></br>
Let:</br>
a - Superman is able</br>
w - Superman is willing</br>
p - Superman prevent evil</br>
i - Superman is impotent</br>
m - Superman is malevolent</br>
e - Superman Exist</br>
</br>
(1) (a ∧ w) → p - If Superman were able and willing to prevent evil,he would do so</br>
(2) ¬a → i - If Superman were unable to prevent evil, he would be impotent</br>
(3) ¬w → m - if he were unwilling to prevent evil, he would be malevolent</br>
(4) ¬p - Superman does not prevent evil</br>
(5) e → (¬i ∧ ¬m) - If Superman exists, he is neither impotent nor malevolent</br>
∴ ¬e - Superman does not exist</br></br>
Soulution:</br>
Modus Tollens of (4) and (1):</br>
¬p</br>
(a ∧ w) → p</br>
∴ ¬(a ∧ w) (6)</br>
De Morgan's Law and Commutative Law of (6):</br>
¬(a ∧ w) ≡ ¬a ∨ ¬w ≡ ¬w ∨ ¬a (7)</br>
Implication Equivalence of (3):</br>
¬w → m ≡ w → m (8)</br>
Resolution of (8) and (7) and Commutative Law (9):</br>
w ∨ m</br>
¬w ∨ ¬a</br>
∴ m ∨ ¬a (9) ≡ ¬a ∨ m (10) </br>
Implication Equivalence of (2):</br>
¬a → i ≡ a ∨ i (11)</br>
Resolution of (11) and (10):</br>
a ∨ i</br>
¬a ∨ m</br>
∴ i ∨ m (12)</br>
De Morgan's Law of (12):</br>
i ∨ m ≡ ¬(i ∨ m) ≡ ¬i ∧ ¬m (13)</br>
Modus Tollens of (13) and (5):</br>
¬(¬i ∧ ¬m)</br>
e → (¬i ∧ ¬m)</br>
∴ ¬e - Superman does not exist</br>
</br>
+ I learned about the rules of inference in quantified statements which are the Universam Instantiation, Universal generalization, Existential instantiation and Existential generalization.
+ We answered some exercises in the Rules of Inference.
</br>
</br>
Week 3:</br>
</br>
+ I learned about the kinds of proofs, there are the direct proof, proof by contraposition, vacuous proof, proof by contradiction and proof by equivalence.
+ I learned that in direct proof, assume the 1st statement to be true to prove the 2nd statement to be true
+ I learned that in proof by contradition, assume the NOT of the 2nd statement to be true to prove the NOT of the 1st statment to be true
+ We answered some exercises in Proofs</br></br>
Assignment #3:</br>
1.7</br>
13.Prove that if x is irrational, then 1/x is irrational.</br>
Let:</br>
p - x is irrational</br>
q - 1/x is irrational</br>
p → q</br></br>
Solution:</br>
Proof by contraposition:</br>
¬q - 1/x is rational</br>
¬p - x is rational</br>
1/x = a/b; x = b/a</b>
subtitute to ¬p:</br>
x = b/a ∴ rational</br></br>
27.Prove that if n is a positive integer, then n is odd if and only if 5n + 6 is odd.</br>
Let:</br>
p - n is odd</br>
q - 5n+6 is odd</br>
p ↔ q</br></br>
Solution:</br>
prove p → q</br>
Direct proof:</br>
n = 2k+1</br>
substitute to q:</br>
5(2k+1)+6 = 10k+11 = 2(5k+5)+1 ∴ odd</br>
prove q → p</br>
Proof by contraposition:</br>
¬p - n is even </br>
¬q - 5n+6 is even</br>
n = 2k</br>
substitute to ¬q:</br>
5(2k)+6 = 10k+6 = 2(5k+3) ∴ even</br></br>
Assignment #4</br>
1.8</br>
15.Show that each of these statements can be used to express the fact that there is a unique element x such that P(x) is true.[Note that we can also write this statement as ∃!xP(x).] </br>
a.∃x∀y(P(y) ↔ x = y)</br>
b.∃xP(x) ∧ ∀x∀y(P(x) ∧ P(y) → x = y)</br>
c.∃x(P(x) ∧ ∀y(P(y) → x = y))</br></br>
Week 4:</br></br>
+ I learned about the set. the set is an undored collection of objects called an element.
+ I learned about elements. the elements are the members of the set.
+ Examples of sets are set of natural numbers and set of integers
+ I learned about the empty set or null set. the empty or null set can be denoted by { } or  ∅.
+ I learned about the cardinality of a set. the cardinality of a set is denoted by |S|. the cardinality of a set can be determined if the elements of a set is a nonnegative integer.
+ I learned about the power set. the power set can be denoted by P(S). the power set is the set of all subset of the given set.
+ I learned about the cartesian product. the cartesian product is denoted by A x B. the cartesian product is the set of all the ordered pairs of set A and Set B.
</br></br>
Week 5:</br></br>
+ I learned about the functions.a function is an assignment of exaclty one element of one set to each element of the other set. the functions i sometimes called mappings or transformation.
+ I learned about the domain, codomain and range. the domain is the elements of the first set, the codomain is the elemnt of the second set. the range is the mapping of the first set to the second set.
+ There are three types of function. the one-to-one, the onto, and the one-to-one correspondence function.
+ The one-to-one function is also called injunction. a function is said to be injunction if the function of the first set has exactly one element of different element in the second set
+ The onto function is also called surjection. the function is said to be an onto function if and only if every element in the second set has an element in the first set.
+ The one-to-one correspondence is also called bijenction. the function is said to be bijective if the function is both one-to-one and onto function at the same time.</br></br>
Assignment #5</br>
2.3</br>
11.Which functions in Exercise 10 are onto?</br>
10.Determine whether each of these functions from {a,b,c,d} to itself is one-to-one.</br>
a) f(a) = b, f(b) = a, f(c) = c, f(d) = d</br>
b) f(a) = b, f(b) = b, f(c) = d, f(d) = c</br>
c) f(a) = d, f(b) = b, f(c) = c, f(d) = d</br>
Answer:</br>
a) is both onto and one-to-one</br>
b) is neither onto and one-to-one</br>
c) is neither onto and one-to-one</br>
∴ only a) is onto </br></br>
Week 6:</br></br>
+ I learned about the Algorithms. Algorithms is a finite sequence of precise instructions for performing a computation or for
solving a problem.
+ I learned about the properties of Algorithms. T he properties are,</br></br>
Input - has input values from a specified set.</br>
Output - for each set of input values an algorithm produces output calues which is the solution to the problem.</br>
Definiteness - steps of an algorithm must be defined precisely.</br>
Correctness - the algorithm should produce the correct input values for each set of input values.</br>
Finiteness - the algorithm should produce the desired output after a finite number of steps for any input.</br>
Effectiveness - must perform each step of the algorithm exactly adn in a finite amount of time.</br>
Generality - the procedure should be applicable to all problems of the desired form.</br></br>
+ there are 7 algorithms used as an example,Algorithm 1 is used to find the maximum element in a finite set.</br></br>
procedure max(a1, a2,...,an: integers)</br>
max := a1</br>
for i := 2 to n</br>
if max < ai then max := ai</br>
return max{max is the largest element}</br></br>
+ Algorithm 2 is used to search for the location of an element using linear search.</br></br>
procedure linear search(x: integer, a1, a2,...,an: distinct integers)</br>
i := 1</br>
while (i ≤ n and x = ai)</br>
i := i + 1</br>
if i ≤ n then location := i</br>
else location := 0</br>
return location{location is the subscript of the term that equals x, or is 0 if x is not found}</br></br>
+ Algorithm 3 is used to find the location of an element using binary search.</br></br>
procedure binary search (x: integer, a1, a2,...,an: increasing integers)</br>
i := 1{i is left endpoint of search interval}</br>
j := n {j is right endpoint of search interval}</br>
while i<j</br>
m := [(i + j )/2] {brackets should be in floor function}</br>
if x>am then i := m + 1</br>
else j := m</br>
if x = ai then location := i</br>
else location := 0</br>
return location{location is the subscript i of the term ai equal to x, or 0 if x is not found}</br></br>
+ Algorithm 4 is used to sort the elements using bubble sort.</br></br>
procedure bubblesort(a1,...,an : real numbers with n ≥ 2)</br>
for i := 1 to n − 1</br>
for j := 1 to n − i</br>
if aj > aj+1 then interchange aj and aj+1</br>
{a1,...,an is in increasing order}</br></br>
+ Algorithm 5 is used to sort the elements using insertion sort.</br></br>
procedure insertion sort(a1, a2,...,an: real numbers with n ≥ 2)</br>
for j := 2 to n</br>
i := 1</br>
while aj > ai</br>
i := i + 1</br>
m := aj</br>
for k := 0 to j − i − 1</br>
aj−k := aj−k−1</br>
ai := m</br>
{a1,...,an is in increasing order}</br></br>
+ Algorithm 6 is a greedy algorithm finding the fewest coins possible.</br></br>
procedure change(c1, c2,...,cr: values of denominations of coins, where
c1 > c2 > ··· > cr; n: a positive integer)</br>
for i := 1 to r</br>
di := 0 {di counts the coins of denomination ci used}</br>
while n ≥ ci</br>
di := di + 1 {add a coin of denomination ci}</br>
n := n − ci</br>
{di is the number of coins of denomination ci in the change for i = 1, 2,...,r}</br></br>
+ Algorithm 7 is a greedy algorithm used for scheduling talks.</br></br>
procedure schedule(s1 ≤ s2 ≤···≤ sn: start times of talks, e1 ≤ e2 ≤···≤ en: ending times of talks)</br>
sort talks by finish time and reorder so that e1 ≤ e2 ≤ ... ≤ en</br>
S := ∅</br>
for j := 1 to n</br>
if talk j is compatible with S then</br>
S := S ∪ {talk j }</br>
return S{S is the set of talks scheduled}</br></br>
+ We answered some excercises involving algorithms. I answered the question #9 in the excercies.</br></br>
3.1</br>
9.A palindrome is a string that reads the same forward and backward. Describe an algorithm for determining whether a string of n characters is a palindrome.</br>
Solution:</br>
procedure palindrome check(a(1),a(2), ..., a(n) in strings)</br>
answer = true</br>
for i = 1 to [n/2] {bracket should be in floor function}</br>
if a(i) = a(n+1−i) then answer = false</br>
return answer</br></br>
Week 7: </br></br>
+ I learned about the Big-O Notation. The Big-O notation shows where the function is bounded on the upper side of the graph.
+ In the definition of the Big-O Notation. f(x) is O(g(x)) if there are constants C and k such that f(x) is less than or equal to C multiplied bt g(x) whenever x is greater than k.
+ Some functions can pass through their Big-O function once but there will be a time when the value of Big-O will be greater than the function and the function will never pass through the Big-O function.</br></br>
Assignment #6:</br>
3.2</br>
13.Show that 2n is O(3^n) but that 3n is not O(2^n).</br>
Solution:</br>
Because 2^n ≤ 3^n for all n > 0, with witnesses C = 1, k = 0, 2^n is O(3^n). But in 3^n is O(2^n) at witnesses c = 2, k = 0, 2^n will be larger but as the value of k increases 3^n will become larger than 2^n even if it has a value equal to c. concluding that 3^n is not O(2^n)).</br></br>
Week 8: </br></br>
+ I learned about the  time complexity of algorithms. the time complexity is the number of operations used in an algorithm. these can be either the number of comparisons of integers, the number of addition of integers, the number of subtraction of integers, the number of multiplication of integers and the number of division of integers.
+ I learned about the worst-case complexity and the average-case complexity. the worst case complexity is the larges number of operations needed to solve the given problem of an algorithm. the average-case complexoty is the average number of operations used to solve the given problem of an algorithm.</br></br>
Week 9: </br></br>
+ I learned about Graphs, Agraph is consists of set of vertices and set of edges with one or two vertices connected to its end point.
+ Vertices are the nodes of the graph and edges are the line connecting the vertices.
+ There are also two types of edges. the undirected edges and the directed edges. directed edges are edges with arrows to know if the edge is pointing out or pointing in. there are also edges that connect to tha same vertex called loop.
+ There are types of graphs.</br></br>
Simple Graph - graph that has undirected edges.</br>
Multigraph - graph that has multiple undirected edges.</br>
Pseudograph - graph that has multiple undirected edges and loops.</br>
Simple Directed Graph - graph that has directed edges.</br>
Directed Multigraph - graph that has multiple directed edges and loops.</br>
Mixed Graph - graph that has both undirected and directed edges and has loops.</br>
