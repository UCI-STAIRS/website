---
title: How verified (or tested) ismy code? Falsification-driven verification and testing
date: 2019-02-01
authors: ["Alex Groce", "Iftekhar Ahmed", "Carlos Jensen", "Paul E. McKenney", "Josie Holmes"]
topics: ["Testing", "Software Evolution"]
link: "http://somewhere.com"
---

### Abstract
Formal verification has advanced to the point that developers can verify the correctness of small, 
critical modules.Unfortunately, despite considerable efforts, determining if a “verification” 
verifies what the author intends is still difficult. Previous approaches are difficult to understand 
and often limited in applicability. Developers need verification coverage in terms of the software 
they are verifying, not model checking diagnostics. We propose a methodology to allow developers to 
determine (and correct) what it is that they have verified, and tools to support that methodology. 
Our basic approach is based on a novel variation of mutation analysis and the idea of verification 
driven by falsification.We use theCBMCmodel checker to showthat this approach is applicable not only 
to simple data structures and sorting routines, and verification of a routine in Mozilla’s JavaScript 
engine, but to understanding an ongoing effort to verify the Linux kernel read-copy-updatemechanism. 
Moreover, we show that despite the probabilistic nature of random testing and the tendency to 
incompleteness of testing as opposed to verification, the same techniques, with suitable modifications, 
apply to automated test generation as well as to formal verification. In essence, it is the number of 
surviving mutants that drives the scalability of our methods, not the underlying method for detecting 
faults in a program. From the point of view of a Popperian analysis where an unkilled mutant is a 
weakness (in terms of its falsifiability) in a “scientific theory” of program behavior, it is only 
the number of weaknesses to be examined by a user that is important.