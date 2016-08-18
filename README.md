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
