# Syllabus: Category Theory Study Group, Winter 2020


This study group meets twice a week for 6 weeks for two hours each from 
**Feb 5 - March 27, 2020** to study 
[Programming with Categories](https://youtu.be/NUBEB9QlNCM)
with Brendon Fong, David Spivak and Bartosz Milewski. The original course runs 

## Calendar

Day | Date | Videos | Notes
----|----|----|----
1 |  2/5/20 | [Programming with Category Theory 0](https://youtu.be/NUBEB9QlNCM) | prelims
1 |  2/5/20 | [Programming with Category Theory 1](https://youtu.be/3W0h3WzxgIE) | David Spivak presents a naive form of set upon which category theory is based.  We do not use [Zermelo Fraenkel set theory](https://en.wikipedia.org/wiki/Zermelo%E2%80%93Fraenkel_set_theory). Instead, think of a set as a sack of dots where you can uniquely identify one dot from all others. [Isomorphism](https://en.wikipedia.org/wiki/Isomorphism) is more important than set equality. Functions are rules for assigning values of one set to another. How many functions are there from the set with 2 elements to the set of 3 elements? Ans: each one in a picks one of 3 in b. Three picks per element in a multiplied by the number of elements in b. 3x3 = 9. Here is answer in a 3x3 grid: (11, 12, 13; 21, 22, 33; 13, 23, 33). Generally n^m  ("from to the to"). Composition: "g composed with f" same as "g circ f" same as "g(f(x))". Identity functions are like zero in Integers. Definition of [Isomorphism](https://youtu.be/3W0h3WzxgIE?t=30m36s). The [defintion of a category](https://youtu.be/3W0h3WzxgIE?t=36m10s) 1) set of elements called objects, 2) for objects c and d in Cat(c,d) there is a set of morphisms from c to d. Aside: in the category of sets, the objects are sets and the morphisms are functions. The set of all morphisms from c to d is the Hom set, H(c,d), ie, the set of ALL functions from set c to set d. 3) For each object (set) in C, there is a chosen morphism (function in cat of sets) there is an identity function in set Cat(c,c). id_c: c -> c. 4) For any object c,d,e and morphisms f:c->d, g:d->e, there is a chosen morphism, g circ f is a function mapping c -> e. In summary, 1) What are the Objects? 2) What are the Morphisms? 3) What are the Identites and 4) How do you compose? Someone gives you a category, you can check them on two rules, a) Unitality which says id_a circ f is same as f circ id_a. and b) Associativity which basically means paraentesis do not matter. Ends with an example of monoid which is a category with a single object which brings rise to a convenient HomSet(a,a) which is the collection of identity morphisms, each labeled with an interger such that 7 followed by 14 composes to yield 21. And thus the morphisms are isomorphic to the natural numbers N.
