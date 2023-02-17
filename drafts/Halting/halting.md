# The Math Crisis and the Halting Problem


## Main Point
Formality and rigour have always had a place in math: Alan Turing, Euclid, Descartes, Newton, Leibniz, Gauss, 

## Sub Points
In classic definition, Formality is the adherance to laid down laws, rules, and principles. In mathematics, a theorem is called _"formal"_ when it is expressed in a form (usually mathematical) such that there is no ambiguity as to the meaning and implications of its expressions, rigour, as it relates to Formality in mathematics, is simply the strict adherence to the laws, principles, and rules guiding the proving of the formality of mathematical theorems. 



## Main Point
Intuitive explanations for the notions of axioms, theorems, mathematical expressions, and proofs

  ## Sub-Points
**Axioms:** Axioms originated from the greek word _"Axioma"_ which means  _"To deem worthy"_. In simple words, axioms are the starting point for any Logical theory or argument, that is, 	they are those universal basic truths everyone agrees on and no one argues about, for example, the _[axiom of choice](https://en.wikipedia.org/wiki/Axiom_of_choice)_ which simply states that 
for every collection of sets, one can create a new set using elements from each set in the original collection.

**Mathematical Expressions:** A mathematical expression is the use of mathematical symbols, variables, operators, and numbers to describe a relationship between two objects. A simple example of a mathematical expression is: _2x + 4 = 20_, this is a simple algebraic expression which describes the relationship the variable X and answer 20.

**Theorems:** A theorem is simply a mathematical statement that has been proven or is being proven through deductive reasoning. They provide the basis for the development of mathematical theory. A mathematical theorem everyone is no doubt familiar with is _[Pythagoras Theorem](https://en.wikipedia.org/wiki/Pythagorean_theorem) (C^2 = A^2+B^2)_. It should be noted that, although, used interchnageably, in a mathematical context, the words theory and theorem do not mean the same thing. In short, a theory is the comprehensive explanation of a subject or phenomena, while, a theorem is a proven mathematical statement. 

**Proofs:** In non-esoteric words, proofs are logical propsitions and arguments which prove the validity of a mathematial statement. Proofs begin from axioms and then proceed to a series of logical extrapolations/deductions, and then an end in the statement being proven(the end of every proof is called a thereom). 

Proofs are generally made to prove the logical soundness of a mathematical statement. Here is a basic example of a statement and its resulting proof:**Prove that an integer N that is not divisible by 3 cannot be divisible by 9**, this is basic example of something called a [Contrapositive Proof](https://en.wikipedia.org/wiki/Proof_by_contrapositive), and to prove our statement, we will simply say  **"if n is not divisible by 3, then n is not divisible by 9," we will prove the equivalent statement "if n is divisible by 9, then n is divisible by 3."**

## Main Point

First-order logic was mostly developed by the end of the 19th century, including set theory (with Cantor) and its weird ideas about infinity

## Sub-Point
In simple words, [Logic](https://en.wikipedia.org/wiki/Logic) is the study of correct reasoning, i.e, the systematic understanding of how things should go. Logic is also used as means of fomarlizing natural language, the process of which is called, [first order logic](https://en.wikipedia.org/wiki/First-order_logic).

First order Logic (also known as predicate logic) is a collection of formal systems used in the sciences of i.e maths and computer sciences, etc. It is a formal language used in mathematical logic and computer science to describe the relationships between objects and concepts, It allows us to express statements that involve objects, their properties, and their relationships to one another, using symbols and a set of rules to form well-formed axioms, theorems, and proofs, for example, here are some basic instances where natural language is transpiled into the syntax of first order logic, it is worthy to note that to fully understand firt ordr logic, you should take a look at the [syntax](https://en.wikipedia.org/wiki/First-order_logic#Syntax); 

**Natural Language:** _All humans are mortal_ 

**First Order Logic:**_Universal quantification: ∀x [human(x) → mortal(x)])_

**Natural Language:** _Alan Turing is a human_

**First Order Logic:** _(Predicate: human(Alan Turing))_

Set theory is crucial for understanding, implementing, and manipulating first order logic due to the fact that with regards set theory, the basic objects of importance are sets, which can contain elements and be related to other sets through set-theoretic operations. This allows first-order logic to talk about objects, features, and relationships in a precise and unambiguous way, making it a powerful tool for formal reasoning in Computer Science.

A German Mathematician, Georg Cantor formulated a theory called [Cantor's Theorem](https://en.wikipedia.org/wiki/Cantor%27s_theorem), his theory simply states that a set is as a collection of distinct objects (elements), and sets can also be elements of other sets. Cantor's Theroem bears similarities to First Order Logic in the sense that both provide a way to represent mathematical objects and properties using formal systems. Using simple extraplation it's safe to state that due to the fact that if we can implement everthing in First Order Logic Syntax then we can easily prove all thereoms due to the fact that proofs are generally promulgated to prove the logical soundness of a theorem. 


## Main Point
Russell discovers insidious logical statements that undermine the notion that all human thought can be axiomatized in a formal system 

## Sub-Point
In the 19th century, [Betrand Russel](https://en.wikipedia.org/wiki/Bertrand_Russell) began working on creating a rigorous logical framework which served to prove that all human thought could be expressed logically, this framework came to be known as [Logicism](https://en.wikipedia.org/wiki/Logicism), but while working on his framework he came across a paradox, which undermined the notion his framework was aimed to uphold. 

The paradox proposes amental experiment where you have a Set (called Set A) which contains all the lists in existence, that list must list itself else it would be incomplete, but if that Set(Set A) does list itself then it is transformed into another set (Set B) which will in turn need to list itself and will end in the generation of another list, and this ends up becoming an endless loop, the paradox (which came to be known as [Russel's paradox](https://en.wikipedia.org/wiki/Russell%27s_paradox#:~:text=In%20mathematical%20logic%2C%20Russell's%20paradox,comprehension%20principle%20leads%20to%20contradictions.) led Russel to believe that not all of human thought could be described logically (axiomatized).


## Main Point

Hilbert’s dream of axiomatizing all mathematics and solving all important problems, including problem No 7 (Diophantine equations) which will be relevant to Computer Science later on

## Sub-Point
German Mathematician [David Hilbert](https://en.wikipedia.org/wiki/David_Hilbert), had the goal of creating a generalized axiomatic system for all of mathematics which would serve as the foundation for mathematics. Hilbert believd that if all of mathematics could b reducced to a set of simple truths (axioms) then all the mathematical solutions conceived could be deduced from that axiomatic system through the use of logic. 

He believed that the axiomatic system could help in solving all of the important problems in mathematics and said system could help decide which problems could be solved and which couldn't. David Hilbert compiled a lit of problems which he termed "The most important problems in mathematics", among which lies the Diophantine problem (AKA Problem number 7), the problem proposes the question; if there exists an algorithm which aids in determining whether there exists an algorithm for determining whther a given [Diophantine equation](https://en.wikipedia.org/wiki/Diophantine_equation#:~:text=In%20mathematics%2C%20a%20Diophantine%20equation,monomials%2C%20each%20of%20degree%20one.) has a soluiton in integers. 

Hilbert believed that this problem and a host of others could be solved by the creation of an axiomatic system of logic.

Hil


## Main Point
Relationship between theorems and axioms.

## Sub-Point
Theories are sets of sentences that explain ideas. They have basic ideas called axioms and other ideas that come from the axioms called theorems. There may also be sentences that define new words in the theory. The theorems of the theory include everything that comes from the axioms and the definitions. In simpllistic words, theories are made up of a set of theorems and theorems are made up of a set of axioms. 



 

## Main Point

Hilbert and Ackerman pose the Entscheidungsproblem

## Sub Point
The [Entscheidungsproblem](https://en.wikipedia.org/wiki/Entscheidungsproblem) was posed by two scientists; David Hilbert and Wilhelm Ackerman, it is a concept from Computer Science and mathematics which poses the question of the existence of a systematic way (Algorithm) of solving all mathematical problems in Existence or if there are some problems which cannot be solved using this _'systematic way'_.




## Main Point

Godel proves that first-order logic is complete and consistent, but obliterates the dream of proving all math complete and consistent

## Sub-Point
As discussed easrlier in order for a mathematical thereom to be accepted, it must be rigourously formalized, but according to [Kurt Godel's Incompleteness theorem](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems), it is impossible to to completley describe a mathematical theroem fully in the sense that, it is in general impossible to explicitly state all the necessary and sufficient conditions for a particular thereom to be valid. There always remains an element of indeterminacy, and completely unambiguous description is impossible. 

Godel argues that the goal of formality in mathematics is not to completely remove every element of indeterminacy and ambiguity from a mathematical expression, but to formally describe it in manner that can be easily understood, because mathematical expressions must have a minimal formality in order to be understandable at all.
