# Principles-of-programming-languages
This course uses the Scheme language (Racket) and TypeScript for teaching the general theory and practice of language design and implementation. Meta-programming tools are developed to demonstrate the advantage of a formal definition of programming languages syntax and semantics to "reason about code". 

#Syllabus

This course studies principles underlying the design of programming languages. It has four main objectives:
1.	Learning principles of programming languages: elements of programming languages; abstraction means in programming languages; formal definition of programming languages – concrete syntax, abstract syntax, operational semantics; program correctness – type checking and type inference systems.
2.	Describing program execution by studying evaluators: interpreters, transformers and compilers. 
3.	Comparing programming paradigms: Functional programming, Logic programming and Imperative programming.
4.	Learning principles of program design: Abstraction, contracts, modular architecture, testing.

The course is a mixture of theory and practice. 
Theoretical topics are supported by implemented software, and course assignments involve programming. 
The course interleaves two main threads: (1) learning new programming techniques (functional programming, logic programming) using practical examples in JavaScript, TypeScript and Prolog; (2) learning meta-programming by developing parsers, interpreters, and program transformers (illustrated by a type inference system for functional programming). 
The course uses the Scheme language (Racket) and TypeScript for teaching the general theory and practice of language design and implementation. Meta-programming tools are developed to demonstrate the advantage of a formal definition of programming languages syntax and semantics to "reason about code". These software tools are also used as practical examples of good software design, using functional programming.

#Topics

1.	Applied Functional Programming:
a.	Benefits of Functional programming (FP): safety, concurrency, asynchronous code
b.	Characteristics of FP: pure functions, immutability, higher-order functions, composition
c.	FP in JavaScript: function, map, filter, chain, flatmap, reduce, zip.
d.	Types in TypeScript: incremental typing, basic types, interfaces, contracts
e.	Hierarchical data types: Arrays, objects, JSON
f.	Higher-order procedures
g.	Polymorphic procedures: Generic types
2.	Syntax, Semantics, Types
a.	Concrete and abstract syntax: comparing JavaScript and Scheme
b.	Operational semantics: the substitution model
c.	Types: basic types, composite types, type constructors, algebraic data types
d.	Higher-Order Functions
|.	Functions and the processes they generate
||.	Anonymous functions, closures, lexical scope
||V.	Partial evaluation, currying and function composition
|V.	Primitive and user-defined procedures, derived expressions, special operators
3.	Abstraction on Data and on Control
a.	Data abstraction: Abstract Data Types (ADTs), Interfaces, Immutable data structures
b.	ADTs and Algebraic Data Types to model abstract syntax
c.	From iterators to streams to observables - push and pull data flow
d.	Control abstraction: Promises and asynchronous programming - reactive programming model
e.	Coroutines: generators, yield, async and await in JavaScript
f.	Continuation passing style programming in Scheme
g.	Tail Recursion Optimization, stack execution model
4.	Evaluators for Functional Programming
a.	Abstract syntax parser
b.	An evaluator for the substitution model
c.	The environment model evaluation algorithm
d.	Evaluator for the environment-based operational semantics
5.	Type Correctness
a.	Type checking and inference
b.	An algorithm for type inference
c.	Implementing a program transformer: Scheme to Typed Scheme.
6.	Logic Programming
a.	Relational logic programming
b.	Logic programming
c.	Meta-tools: Backtracking optimization (cuts); Unify;
d.	An evaluator for Prolog
7.	Conclusion: Techniques, Principles and Languages Comparison
