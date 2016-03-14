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
