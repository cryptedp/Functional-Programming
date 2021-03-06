# Functional Programming Papers

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*


- [Why Functional Programming Matters (1984)](#why-functional-programming-matters-1984)
- [Composing contracts: an adventure in financial engineering(functional pearl)](#composing-contracts-an-adventure-in-financial-engineeringfunctional-pearl)
- [Learn Physics by Programming in Haskell](#learn-physics-by-programming-in-haskell)
- [Monads for functional programming](#monads-for-functional-programming)
- [FUNCTIONAL PEARL - Applicative programming with effects](#functional-pearl---applicative-programming-with-effects)
- [Monadic parsing in Haskell](#monadic-parsing-in-haskell)
- [The Typeclassopedia](#the-typeclassopedia)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



Papers in this repository.

### Why Functional Programming Matters (1984)

[PDF](Why_Functional_Programming_Matters-John_hughes.pdf)

Abstract

As software becomes more and more complex, it is more and more important to structure it well. Well-structured software is easy to write, easy to debug, and provides a collection of modules that can be re-used to reduce future programming costs. Conventional languages place conceptual limits on the way problems can be modularised. Functional languages push those limits back. In this paper we show that two features of functional languages in particular, higher-order functions and lazy evaluation, can contribute greatly to modularity. As examples, we manipulate lists and trees, program several numerical algorithms, and implement the alphabeta heuristic (an algorithm from Artificial Intelligence used in game-playing programs). Since modularity is the key to successful programming, functional languages are vitally important to the real world.

```
Hughes, John. "Why functional programming matters." 
The computer journal 32.2 (1989): 98-107.
```

Bibtex
```bibtex
@ARTICLE{Hughes84whyfunctional,
    author = {John Hughes},
    title = {Why Functional Programming Matters},
    journal = {The Computer Journal},
    year = {1984},
    volume = {32},
    pages = {98--107}
}
```


### Composing contracts: an adventure in financial engineering(functional pearl)

[PDF](Composing_Contracts_an_adventure_in_financial_engineering.pdf)
[ACM Link](http://dl.acm.org/citation.cfm?id=351267)


Abstract:

Financial and insurance contracts do not sound like promising territory for functional programming and formal semantics, but in fact we have discovered that insights from programming languages bear directly on the complex subject of describing and valuing a large class of contracts.We introduce a combinator library that allows us to describe such contracts precisely, and a compositional denotational semantics that says what such contracts are worth. We sketch an implementation of our combinator library in Haskell. Interestingly, lazy evaluation plays a crucial role.


```
Jones, Simon Peyton, Jean-Marc Eber, and Julian Seward. 
"Composing contracts: an adventure in financial engineering(functional pearl).
" ACM SIGPLAN NOTICES 35.9 (2000): 280-292.
```

Bibtex
```
@article{jones2000composing,
  title={Composing contracts: an adventure in financial engineering(functional pearl)},
  author={Jones, Simon Peyton and Eber, Jean-Marc and Seward, Julian},
  journal={ACM SIGPLAN NOTICES},
  volume={35},
  number={9},
  pages={280--292},
  year={2000},
  publisher={ACM; 1999}
}
```

### Learn Physics by Programming in Haskell

[PDF](Learn_Physics_by_Programming_In_Haskell-Scott-N-Walck.pdf)

Site: http://arxiv.org/abs/1412.4880

Abstract:

We describe a method for deepening a student's understanding of basic physics by asking the student to express physical ideas in a functional programming language. The method is implemented in a second-year course in computational physics at Lebanon Valley College. We argue that the structure of Newtonian mechanics is clarified by its expression in a language (Haskell) that supports higher-order functions, types, and type classes. In electromagnetic theory, the type signatures of functions that calculate electric and magnetic fields clearly express the functional dependency on the charge and current distributions that produce the fields. Many of the ideas in basic physics are well-captured by a type or a function. 

```
Walck, Scott N. "Learn Physics by Programming in Haskell." 
arXiv preprint arXiv:1412.4880 (2014).
```

Bibtex
```
@article{walck2014learn,
  title={Learn Physics by Programming in Haskell},
  author={Walck, Scott N},
  journal={arXiv preprint arXiv:1412.4880},
  year={2014}
}
```

### Monads for functional programming

[PDF](Monads_for_functional_programming-Phillip_Walder.pdf)

Abstract:

The use of monads to structure functional programs is described. Monads provide a convenient framework for simulating effects found in other languages, such as global state, exception handling, output, or non-determinism. Three case studies are looked at in detail: how monads ease the modification of a simple evaluator; how monads act as the basis of a datatype of arrays subject to in-place update; and how monads can be used to build parsers.

```
Wadler, Philip. "Monads for functional programming." 
Advanced Functional Programming. Springer Berlin Heidelberg, 1995. 24-52.
```

Bibtex:
```
@incollection{wadler1995monads,
  title={Monads for functional programming},
  author={Wadler, Philip},
  booktitle={Advanced Functional Programming},
  pages={24--52},
  year={1995},
  publisher={Springer}
}
```

### FUNCTIONAL PEARL - Applicative programming with effects

[PDF](Functiona_Pearls-Applicative_Programming_With_Effects.pdf)

Abstract:

In this article, we introduce Applicative functors – an abstract characterisation of an applicative style of effectful programming, weaker than Monads and hence more widespread. Indeed, it is the ubiquity of this programming pattern that drew us to the abstraction. We retrace our steps in this article, introducing the applicative pattern by diverse examples, then abstracting it to define the Applicative type class and introducing a bracket notation that interprets the normal application syntax in the idiom of an Applicative functor. Furthermore, we develop the properties of applicative functors and the generic operations they support. We close by identifying the categorical structure of applicative functors and examining their relationship both with Monads and with Arrow.


```
McBride, Conor, and Ross Paterson. 
"Applicative programming with effects." 
Journal of functional programming 18.01 (2008): 1-13.
```

Bibtex
```
@article{mcbride2008applicative,
  title={Applicative programming with effects},
  author={McBride, Conor and Paterson, Ross},
  journal={Journal of functional programming},
  volume={18},
  number={01},
  pages={1--13},
  year={2008},
  publisher={Cambridge Univ Press}
}
```

### Monadic parsing in Haskell

This paper is a tutorial on defining recursive descent parsers in Haskell. In the spirit of one-stop shopping, the paper combines material from three areas into a single source. The three areas are functional parsers (Burge, 1975; Wadler, 1985; Hutton, 1992; Fokker, 1995), the use of monads to structure functional programs (Wadler, 1990; Wadler, 1992a; Wadler, 1992b), and the use of special syntax for monadic programs in Haskell (Jones, 1995; Peterson et al. , 1996). More specifically, the paper shows how to define monadic parsers using do notation in Haskell.
Of course, recursive descent parsers defined by hand lack the efficiency of bottom up parsers generated by machine (Aho et al., 1986; Mogensen, 1993; Gill & Marlow, 1995). However, for many research applications, a simple recursive descent parser is perfectly sufficient. Moreover, while parser generators typically offer a fixed set of combinators for describing grammars, the method described here is completely extensible: parsers are first-class values, and we have the full power of Haskell available to define new combinators for special applications. The method is also an
excellent illustration of the elegance of functional programming. The paper is targeted at the level of a good undergraduate student who is familiar
with Haskell, and has completed a grammars and parsing course. Some knowledge of functional parsers would be useful, but no experience with monads is assumed. A Haskell library derived from the paper is available on the web from:

```
Hutton, Graham, and Erik Meijer. 
"Monadic parsing in Haskell." 
Journal of functional programming 8.04 (1998): 437-444.
```

Bibtex
```
@article{hutton1998monadic,
  title={Monadic parsing in Haskell},
  author={Hutton, Graham and Meijer, Erik},
  journal={Journal of functional programming},
  volume={8},
  number={04},
  pages={437--444},
  year={1998},
  publisher={Cambridge Univ Press}
}
```

### The Typeclassopedia

[PDF](Typeclassopedia.pdf)
Site: https://wiki.haskell.org/Typeclassopedia

Abstract:

The standard Haskell libraries feature a number of type classes with algebraic or category-theoretic underpinnings. Becoming a fluent Haskell hacker requires intimate familiarity with them all, yet acquiring this familiarity often involves combinig through a mountain of tutorials, blog posts, mailing list archives, and IRC logs. The goal of this article is to serve as a starting point for the student of Haskell
wishing to gain a firm grasp of its standard type classes. The essentials of each type class are introduced, with examples, commentary, and extensive references for further reading.

```
Yorgey, Brent. "The typeclassopedia." 
The Monad. Reader Issue 13 (2009): 17.
```

Bibtex
```
@article{yorgey2009typeclassopedia,
  title={The typeclassopedia},
  author={Yorgey, Brent},
  journal={The Monad. Reader Issue 13},
  pages={17},
  year={2009}
}
```
