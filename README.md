# dismathportfolio-BiIIy
dismathportfolio-fidesbetito created by Classroom for GitHub

##Week 1:

* I was introduced to a new subject called, DISCRETE MATHEMATICS or DISMATH.
* This subject soon proved to be really challenging if it was not taken seriously when studying.
* I've learned that DISMATH deals with mathematical truth only.
* I learned about logical connectives as presented in the table:

###LOGICAL CONNECTIVES TABLE

| *Logical Symbol*  |  *Logical Operator* | *Logical Expression* | *Shorthand* | *Formula* | 
| :-----: |:-------:|:--------:| :-------: | :-----: |
| ¬ | Negation | val(¬p) = 1 - val(p) | not | ¬p |
| ∧ | Conjunction | val(p ∧ q) = min(val(p), val(q)) | and | p ∧ q |
| v | Disjunction | val(p v q) = max(val(p), val(q)) | or | p v q |
| ⊕ | Exclusive Disjunction | if val(p)  not equal val(q) = 1 , otherwise  0 | xor |  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if val(p)  ≤ val(q) = 1 , otherwise  0 | if, then | p → q ≡  ¬p v q |
| ↔ | Biconditional | if val(p) equals val(q) = 1 , otherwise  0 | iff |  p ↔ q ≡ (p → q) ∧ (q → p) |

* I learned how to test the verification of a statement by using TRUTH TABLES.

* I learned about IMPLICATION which gets confusing as more complicated expressions were presented.

* I learned about PROPOSITIONAL LOGIC such as:
    - inverse of p→q which is ¬p → ¬q
    - converse of p→q which is q → p
    - contrapositive of p→q which is ¬q → ¬p

##Week 2:

* I learned the laws in mathematics called **LOGICAL EQUIVALENCES**:

### LOGICAL EQUIVALENCES

|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  p ∨ F ≡ T  ;;  p ∧ F ≡ T  |
|  _Domination Laws_  |  p ∨ T ≡ T  ;;  p ∧ F ≡ F  |
|  _Negation Laws_  |  p ∨ ¬p ≡ T  ;;  p ∧ ¬p ≡ F  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
|  _Idempotent Laws_  |  p ∨ p ≡ p  ;;  p ∧ p ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  ;;  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  ;;  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  ;;  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  ;;  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  ;;  p ∧ (p ∨ q) ≡ p  |

* With the help of this table, I was able to conclude, in my assignment, that Superman does not exist.

* I was able to prove that **p → q ≡ ¬p ∨ q** using a Truth Table and Logical Equivalences. 

* **Predicate Logic**, much like in the English language, is not only concerned with its relation to logic but also with their internal structure in terms of subject and predicate.
* **Propositional Logic** deals with propositions, _subject and predicate_, as a whole.
* **Quantifiers** indicate the generality of the open sentence in which a variable occurs.
    - Existential Quantifier - "there exists" - if and only if P(x) is true for at least one value of x in the domain.
    - Universal Quantifier - "then exists" - many mathematical statements assert that a property is true for all values of a variable in a particular domain.

### Week 3:

* **Rules of Inference** was introduced:
    - _Argument_ is a series of statements that end with a conclusion.
    - _Valid_ is the conclusion which must follow from the truth of the preceding statements or premises of the argument.
    - _Fallacy_ is the common form of incorrect reasoning which leads to invalid arguments. 

* The tools that can be used to prove statements are:
    - Truth table
    - Logical Equivalences
    - Quantifiers
    - Rules of Inference
 
### RULES OF INFERENCE TABLE   
|  **TYPE**  |  **RULE OF INFERENCE**  |  **TAUTOLOGY**  |
| -------: | :--------------: | :--------- |
|  _Modus Ponens_  |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
|  _Modus Tollens_  |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
|  _Hypothetical Syllogism_  |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
|  _Disjunctive Syllogism_  |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
|  _Addition_  |  p ∴ p ∨ q  |  p → p ∨ q  |
|  _Simplification_  |  p ∧ q ∴ p  |  (p ∧ q) → p  |
|  _Conjunction_  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
|  _Resolution_  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

* I was taught the **Methods of Proof**.
    - Why study methods of proof?
        1. Software - debug a program beyond a doubt
        2. Hardware - useful in debug before pre-production hardware

* **Direct Proof**:
    - 1. Assume _p_ is _T_
    - 2. Show that _q_ is also true

### Week 4:

* Continuation of Methods of Proof

* **Contraposition (Indirect)**:
    - 1. Assume _¬q_ is _T_
    - 2. Show that _¬p_ is also true


* **PROOF BY CONTRADICTION**:
    - 1. Assume that the premise is not true
       - ¬(premise)≡ T
    - 2. Show that step 1 will end up in a contradiction
    
  
* **Proof by Equivalence**:
    - To prove a theorem that a bio conditional statement, _p↔q_,
    - we show that
         - _(p↔q)→[(p→q)∧(q→p)]_
  
  ##Week 5:

* This week I learn **Counterexample**
    - uses an example to disprove a statement
  
* **Mathematical Induction**:
    - We treat the sequence of propositions like dominoes.
    - Q.E.D. (quod erat demonstrandum)
       - "which is what had to be proven" or signals the completion of the proof.
    - Show P(1) ≡ T
    - Direct proof
       - a. Assume P(k) ≡ T
       - b. Show that is also P(k+1) true

  ##Week 6:

	* Reviewed Nested Quantifiers:
		* The choices of x, some y, P(x,y) is true.
		
				∀x∃yP(x,y)
		
		* Some x, choices of y, P(x,y) is true.
		
				∃x∀yP(x,y)
		
	* Nagating Statements
		* Example: Negate the statement: Everyone loves someone.
		
				∀x∃yPoves(x,y)  into  ∃x∀y¬Loves(x,y)
	
	* Proof by cases
	* Proof by exhaustion
	* Existence Proofs
	* Uniqueness Proof
	
- Learned DISMATH Application.
	* f(a) = b means b is is the image of a. 
	
				f: A => B
	
	* One to one function (Injective) 
		
				{a,b,c,d} to {1,2,3,4,5}
				f(a)=5 , f(b)=3 , f(c)=4 , f(d)=1
				**∀x∀y(f(x)=f(y) → x=y)**

	* Onto function (Surjective) - functions have equal range and codomain. (all set of numbers should be assigned)

				{a,b,c,d} to {1,2,3}
				f(a)=3 , f(b)=2 , f(c)=1 , f(d)=3
				**f: A => B = {(a,3),(b,2),(c,1),(d,3)}**
				
	* Bijective is one to one function and onto function
	* Not a function
		* one to many

    *Studied, prayed, when to church, took the quiz, cried...
    
  ##Week 7:

* Did **PROJECT 0-0**.
	- **HelloWorldApp**
	- The minimum requirements are:
		* A button I am (First name, surname) of DISMATH (section).
		* A space in between the next button.
		* The next button is the talk button about the text from the above.
	
  ## Week 8:
* We were introduced to Algorithm.
	* Algorithm 
		* a set of finite set of precise instruction for performing a computation.
	* Finding the **Maximum Element Algorithm**
		1. **Set** the temporary maximum equal to the first integer in the sequence.
		2. **Compare** the next integer in the sequence to the temporary max.
		3. **Repeat the previous set** if there are more integers in the sequence.
		4. **Stop** when there are no integers left in the sequence.
	* Example:
	
			Precondition: {2,5,8,1,10,12,3} ∈ Z, finite
			Postcondition: max= maximum(A1,A2,A3,...,An)
			using for-loop (Pseudocode)
			for i=2 to n
				if(max<Ai)
					max=Ai

	* Pseodocode
		* high level description of an algorithm that uses the structural conventions of a programming language, but intended for human reading.
		* It is a human readable code.
	* Example of Algorithms
	* Algorithm 1:
	
			Linear Search
			
			Input: S={A1,A2,...,An} A1 ∈ Z; x ∈ Z
			Output: index, loc where Aloc=x
			loc=-1
			for i; 1 to n
				if(Ai==x)
					loc=i;
			final assertion: loc is the location of element

	* Algorithm 2:

			Binary Search
			
			Input: {A1,A2,...An:distinct integers}
			i=1 (i is the left endpoint of the search interval)
			j=n (j is the right endpoint of the search interval)
			while i<j
				mid = [(i+j)/2]
				if x>A(mid) then i=mid+1
				else j=mid
			if x=Ai then location=i
			else location=-1
			return location 

  ##Week 9:
* Continuation of the lesson, Algorithm:
	* Algorithm 3:
	
			Bubble Sort
			
			Input: {A1,A2,.....,Ai,....An} ∈ all real numbers, n>=2
			Output: {X1,X2,....,Xi,...,Xn} where X1<X2<.....<Xn
			for j=1 to n-1
				for i=1 to n-j
					if(Ai>A(i+1))
					swap(Ai,A(i+1))

	* Algorithm 4:
	
			Insertion Sort
			
			Input:{A1,A2,.....,Ai,....An} ∈ n>=2
			for j=2 to n
			{
				i=1
				while Aj>Ai
					i=i+1
				m=Aj
				for k=0 to j-i-1
					A(j-k)=A(j-i-1)
				Ai=m
			}
			Output: {X1,X2,X3,....,Xn:increasing order}

		* Outer for-loop is responsible of the sorting.
		* Inner for-loop is responsible for swapping.

	* Algorithm 5:
	
			Greedy Algorithm
			- selects the best choice at each step, instead of considering all sequences of steps that may lead to an optional solution.
			- applied in optimization problems where a solution to the given problem either minimizes or maximizes the value of some parameter.
			
			Denomination 
				C={25,10,5,1}
				x=amount of memory
			for i=1 to r
				x=0
			while (x>=Ci)
				x=x-Ci
				n=n+1

  ##Week 10:
  -Pray to God what I studied comes out in the exam
  -This week, we were introduced to growth of functions.
	* Using Big-O, Big-Ω and Big-ϴ
	* In Big-O, we are looking for the upper bound size of f(x).
	* In Big-O, let f and G be functions from Real numbers to Real numbers where f(x) is O(g(x)) if there are constants C and k such that:
	
			|f(x)| ≤ C|g(x)| where x > k
			C and k are the witnesses of Big-O

		* Example:
			
				x^2 + 2x + 1 is O(x^2) 
				x^2 + 2x + 1 is O(x^3)
				x^2 + 2x + 1 is O(x^4)

	* Same as in Big-Ω, but in this function, we are looking for the lower bound of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is Ω(x^2)
				x^2 + 2x + 1 is Ω(x)

	* Lastly, in Big-ϴ, we are looking for both the lower and upper bound size of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is ϴ(x^2)

		* There is only one answer in Big-ϴ.

* Next, Time Complexity in Algorithm, and Division and Modulo Operator
	
	* Time Complexity
		* can be expressed in terms of the number of operations used by the algorithms.
		* number of comparisons will be used as the measure of the time complexity.
	
		| Complexity | Terminology |
		| :---: | :---: |
		| ϴ(1) | constant complexity |
		| ϴ(logn) | log complexity |
		| ϴ(n) | linear complexity |

		* Time complexity of finding max comparison: 2n-1, ϴ(n)
		* Time complexity of linear search: 2n+2, ϴ(n)
	
	* Division and Modulo
	
			* Example:
				Let a = integer, d = positive integer
				Unique integers Q and r
					with 0<=r<d such that a=dQ+r
				9 mod 2 = 1 (r)
				9 div 2 = 4 (Q)
				a=d*Q+r
				a=2*4+1
				a=9

	* Last topic for quiz 2: Ceasar Cipher
	
			* How can you make your message secret?
				Example:
				LOVE = ORYH
				(p+3) mod 26

## **Week 11:**
* **NO CLASSES**

## **Week 12:**
* We discussed about Graph Theory.
	* Graph
		* discrete structures consisting of vertices and edges that connect the vertices.
		* a set composed of vertices and edges. (V,E)
			* G={V,E}
	* Application
		* Networks
		* Job Assignments
	* Basic Terminology
		* degree of a vertex in an undirected graph is the number of edges incident with it, except that the loop at a vertex contributes twice to the degree of that vertex.
	* Handshaking Theorem
		* Let G=(V,E) be an undirected graph with edges.
		
				Then,
					2e = ∑deg(v)
					where v=V

		* For example, how many edges are there in a graph with 10 vertices each of the degree 6?
		
				10 x 6 = 60
				2e = 60
				e = 30 edges

	* Subgraph of a graph
		* G=(V,E) is a graph of H=(W,F), where W ⊆ V and F ⊆ E
		* subgraph of H of G is a proper subgraph of G if H ≠ G
	* Path
		* sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph.
	* Euler Ciruit
		* all nodes have even degrees 
		* you can go back to where you started
	* Euler Path
		* only one way path
		* exactly 2 nodes with odd degree
	* Euler's Formula
			
				r=e-v+2
			
	* Hamilton Circuit
		* circuit passes through every vertex exactly once.
	* Hamilton Path
		* path passes through every vertex exactly once.
	* Matrices of Graphs
	* Isomorphism of Graphs
	* Planar Graph
		* drawn in the plane without edges having to cross.
	* Nonplanar Graph
		* when everything is interconnected to one another

## **Week 13:**
   -* Homeomorphic Graphs
	* Elementary Subdivision
		* removing an edge and reconnecting it with a node at the middle.
		* same graph, unequal number of nodes and edges.
* **Graph Coloring**
	* minimal use of color
	* assignment of a color to each vertex
	* Chromatic number 
		* least colors needed for a coloring of graph
	* best algorithms known for finding the chromatic number
* Four Color Theorem
	* only applies to planar graphs
* **Trees** 
	* connected undirected graph with no simple circuits
	* data structure with a set of linked nodes
	* no circuit
	* cut connection to form a tree
	* should not have a loop
* Rooted Tree
	* a tree in which one vertex has been designated
	* internal nodes
		* parents
	* leaves
		* Children
* m-ary tree
	* m = 2, binary tree
	* m = 5, 5-ary tree
	* A full m-ary tree:
		* n vertices has i=(n-1)/m internal and l=[(m-1)n+1]/m leaves
		* i internal vertices has n=mi+1 vertices and l=(m-1)i+1
		* l leaves has n=(ml-1)/(m-1) internal vertices
* Ordered rooted tree
	* rooted tree where the children of each internal vertex are ordered.
* Tree traversal
	* Universal Address Systems
		* vertex v at level n, for n≥1, labeled x1,x2,....,xn
* Preordered Traversal
	* ordered rooted tree T
	* visit root (subtrees from left to right)
* Inordered Traversal
	* visit leftmost subtree to the root to other subtrees from left to right
* Postordered Traversal
	* visit subtrees left to right then to root
* **Modeling Computation**
	* Grammars
		* generate the words of a language and determine whether a word is in a language
		* important in constructing a sentence and compiling a program
	* Language
		* generated by grammars
		* provides model for both natural language
		* grammar of English tells us whether a combination of words is a valid sentence
		* concerned of the syntax and semantics 
		* Strings talk about words and numbers
		* Alphabet talks about set of symbols
	* Finite-state machines
		* S = {S0,S1,S2,S3}
		* I = {0,1}
		* O = {0,1}
	* Turing Machines
	* Automata Theory
		* Laws of computation
		* Finite Automation
			* simplest model of a computing device
	* Lexical Analyzers
		* process where stream characters making up the source program which read from left to right.
	* Token 
		* where the program makes sense.

## **Week 14:**

	* Pray To God, Hear Mass, Buy all Lucky Charms, Pray to Allah, Pray to Budda, Meditate, Preach the Word of God, Make a deal with the Devil, and lastly... HOPE THAT AFTER THIS WEEK MY BRAIN WILL STILL BE WORKING.
	* Submitted DISMATH project
