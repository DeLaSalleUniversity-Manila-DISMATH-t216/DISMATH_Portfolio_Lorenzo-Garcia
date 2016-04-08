# DISMATH Portfolio - Lorenzo Garcia
Dismathportfolio-LorenzoGarcia created by Classrom for GitHub
## Week 1
what i learned:
- I was introduced to the course, DISMATH, which means Discrete Mathematics
- I learned that Mathematical Proof is a chain of logical deductions leading to the opposition from a base set of axioms.
- Axioms, is the statement of proposition that is regarded as being established, accepted or self-evidently true.
- Proposition, is a statement which is either true or false.
- Logical deduction, is the process of reasoning from one or more statements to reach on logically certain conclusion.
- Propositional Variables represents propositions, for example is p, q.
- Propositional Expressions are expressions with variable with connectives, for example, p V q.
- Truth table is a list of all possible combination of inputs with output.
- sign "^" means minimum.
- sign "v" means maximum.
- Truth table rows is 2 raise to n, where n is number of variables.
- Conditional p->q is TRUE if both p & q are true, and p is false.
- I learned symbols like: 

| Logical Symbol  |  Logical Operator | Shorthand | Logical Expression | Value |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | ¬p | opposite |
| ∧ | Conjunction | and | p ∧ q | minimum |
| v | Disjunction | or | p v q | maximum |
| ⊕ | Exclusive disjunction | xor |  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) | T iff exactly one of p and q is T, otherwise F|
| → | Conditional | if, then | p → q ≡  ¬p v q | F if p is T and q is F, otherwise T |
| ↔ | Biconditional | iff |  p ↔ q ≡ (p → q) ∧ (q → p) |  T iff p and q have the same truth values |

- Normal implication is p -> q
- Inverse is when, ¬p -> ¬q
- Converse is when, q -> p
- Contrapositive is when, ¬q -> ¬p
- Biconditional is when, p <-> q which means statement is true if and only if p and q have the same truth value.

## Week 2
what I learned:
- We learned some logical equivalences, namely:
  - Identity Laws
  - Domination Laws
  - Idempotent Laws
  - Double Negation Laws
  - Commutative Laws
  - Assosciative Laws
  - Distributive Laws
  - De Morgan's Laws
  - Absorption Laws
  - Negation Laws
- Propositional Logic deals with propositions as a whole.
- Predicate Logic is concerned not only with logic relations between sentences or propositions as whole.
- Quantifiers indicates the generality of open sentence.
- Existential Quantifier, is true if "there exist" at least only one value for x in p(x)
- Universal Quantifier, is true if "for All" possible value for x is true in p(x)
- "Mathematical Statements" are Universal Quantifier.
- Rules of Inference (Terms):
 - Argument, is a sequence of statements with conclusion.
 - Valid
 - Fallacy means invalid
- Rules of Inference Tautologies:
 - Modus Ponens
 - Modus Tollens
 - Hypothetical Syllogism
 - Disjunctive Syllogism
 - Addition
 - Simplification
 - Conjunction
 - Resolution
 
## Week 3
What I learned:
- Methods of proof:
 - Direct Proof
 - Contraposition
 - Vacuous&Trivial Proof
 - Contradiction
 - Equivalence

- Direct
 - 1ST: Assume p is true in p -> q
 - 2ND: Show q is true using step 1.
- Contraposition
 - 1ST: Assume ¬q is true in ¬q -> ¬p
 - 2ND: Show ¬p is true using step 1.
- Vacuous Proof
 - Show p is false, because p -> q must be true when p is false. 
- Trivial Proof
 - Show q is true, because p -> q must be true when q is true.
- Contradiction
 - 1ST: Assume NOT of the PREMISE.
 - 2ND: Show steo 1 ends up in a contradiction.
- Equivalence
 - p <-> q = (p -> q) v (¬q -> ¬p)

## Week 4
What I learned:
- Mathematical Induction
 - 1ST: Substitution (BASIS)
 - 2ND: Direct Proof (INDUCTIVE)
- Recursively Defined Functions
 - a proof technique used to prove results about a wide range of objects WHICH has two parts:
  - A. Basic Step:
   - Specify value of fucntion as zero (0).
  - B. Recursive Step:
   - Give a rule finding its value at an integer from values at its smaller integers.

## Week 5
What I learned:
- Recursive Algorithm
 - These are algorithms that continuosly reduce a problem to a same problem with smaller input.
- Program Correctness
 - Tought how to know if a program is correct by checking if it produces the correct output for every possible input.
 - Program Verification is also used to prove correctness
- Program Verification
 - A. Partial Correctness
  - Correct answer can be obtained if program terminates.
 - *Hoarse Triple - notation that indicates that the program, S is partially correct with respect to the initial assertion P and the final assertion Q.
 - B. Show that the program terminates correctly
- Power Series
 - Can be solved using GEOMETRIC SERIES formula: a1/ 1-r
 - example would be: Zeno's Paradox
- Set
 - An unordered collection of distinct objects, which may be anything.
 - Empty Set 
  - contains no elements adn is denoted by { } or ∅.
 - Subset
  - A set S is a subset of a set T (denotes S ⊆ T) if all elements of S are also elements of T.
 - Power Set
  - A set containing all subsets.
- Cardinality
 - Number of elements in a set.
 
## Week 6
What I learned:
- Review was done during this week. A review for the quiz.The focus was about Nested Quantifiers.
- Function
 - There exist a function if for every x there is only one y.
  - TYPES:
   - A. One to one or Injunction
    - Functions that has only one specific Y for every domain elements.
   - B. ONTO or Surjection
    - Each co-domain is assigned to a domain.
   - C. Bijection
    - Both One to one and ONTO.

## WEEK 7
--- NO CLASSES THE WHOLE WEEK ---

## Week 8
What I learned:
- Algorithms
 - It is a finite set of precise instruction.
  - Precondition - describes the input
  - Post Condition - describes what the output should satisfy
  - Properties that Algorithm have:
   - Input - values from specific set
   - Output - solves a given problem
   - Definiiteness - precised and defined steps
   - Correctness - produces the correct output values
   - Finiteness - produces the desired output values
   - Effectiveness - performs the given steps 
   - Generality - applicable to all problems of desired form.
- Pseudocode
 -  A high-level description of an algorithm that uses the structural conventions of a programming language, but is only for human reading.
- Searching Algorithms
 - locates an element in an ordered list.
 - examples are: LINEAR and BINARY
 
## Week 9
What I learned: 
- Sorting Algorithms
 - organizes elements in increasing order.
 - examples are: BUBBLE Sort (compares who's greater then swap), INSERTION Sort (Inserting elements according to its value)
- Greedy Algorithm
 - minimizes or maximizes the value of some parameters.
 - Selects the best choice instead of considering all sequences.

## Week 10
What I learned:
- Growth of Function
 - defined as Big O Notation
  - BIG O Notation - used to determine the upperbound of a functino.
  - BIG Omega Notation (Big-Ω) - used to determine lowerbound of a function.
  - BIG Theta Notation (Big-Θ) - used to determine both lower and upperbound.
- Algorithm Time Complexity
 -  expressed in terms of the number of operationsused by the algorithm when the input has a particular size

## Week 11
--- NO CLASSES BECAUSE OF HOLY WEEK ---

## Week 12
- Graph Theory
 - Graphs are structures that contains vertices which are interconnected through the edges.
 - Degree of a vertex is the number of connections in a vertex.
- Euler Path
 - a path that contains all edges but doesn't go back to the start. Must have exact 2 odd degree.
- Euler Circuit
 - simple circuit that passes through every edge present in the graph and goes back to the start without getting back through the same direction. Must have all degree in even.
- Hamilton Path
 - a path that passes through all the vertices without repitition.
- Hamilton Circuit 
 - a circuit that contains all the vertices and goes back to the starting vertix without repitition.
- Matrices of Graphs
- Isomorphisms in Graphs
- Planar and Non-Planar Graphs
- R = E - V + 2

## Week 13
**THE FINAL WEEK**
- Elementary Subdivisions
- Tree Graphs
- Four-Colour Theorem
- Languages
- Gramar
- Formal and Natural Languages
- Syntax and Semantics
- Finite-State Machines


**THE END OF PORTFOLO OF LORENZO C. GARCIA EK**
 
 


