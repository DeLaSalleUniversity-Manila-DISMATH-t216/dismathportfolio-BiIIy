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
  
  ###To be continued...
