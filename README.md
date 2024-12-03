# Josh Berdine

I work for SkipLabs, an early-stage startup company concentrated on reactive programming.

Previously I worked for Meta/Facebook and Microsoft Research, focusing on static analysis and verification of software.


## Software

- [Smallfoot](http://www0.cs.ucl.ac.uk/staff/p.ohearn/smallfoot/): An automatic concurrent separation logic specification checking tool. Smallfoot was written in the early days of separation logic as a research field, and was the beginning of automating separation logic and separation logic theorem provers.

- [SLAyer](https://github.com/microsoft/SLAyer): An automatic formal verification tool that uses separation logic to verify memory safety of C programs. SLAyer extended the techniques in Smallfoot to an automatic static analysis inferring invariants strong enough to prove memory safety properties, as well as to operate on production C code, and have sufficient precision and scalability to prove kernel drivers.

- [Infer](https://github.com/facebook/infer): A tool to detect bugs in Java and C/C++/Objective-C code before it ships. Infer grew out of a line of development following Smallfoot and parallel to SLAyer, most crucially adding a bottom-up analysis capability using biabduction, and has continued to evolve since. My contributions were primarily related to supporting C++.

- [SLEdge](https://github.com/facebook/infer/tree/12bcd738abd6d7ab08cf6c06664e5389eebcf15f/sledge): A static analysis system that refutes memory safety properties of LLVM bitcode. SLEdge was developed, and targets (post-optimization) LLVM bitcode, due to the need for significantly higher fidelity treatment of C++ code. SLEdge analyzes code using symbolic execution in separation logic, and handles control flow using techniques that are a hybrid of what one might expect from abstract interpretation and bounded model checking.

- [ocamlformat](https://github.com/ocaml-ppx/ocamlformat): Automatic formatter for OCaml code. I'm the original author of ocamlformat, which has been taken over by the community.


## Scientific Publications

&emsp;&emsp;
[DBLP](https://dblp.org/pid/61/1623.html)
&emsp;&emsp;
[Google Scholar](https://scholar.google.com/scholar?q=Josh+Berdine)

- **A General Approach to Under-Approximate Reasoning About Concurrent Programs** with Azalea Raad, Julien Vanegue, and Peter W. O'Hearn. CONCUR 2023. ([pdf](pub/2023_concur.pdf))

- **Finding Real Bugs in Big Programs with Incorrectness Logic** with Quang Loc Le, Azalea Raad, Jules Villard, Derek Dreyer, and Peter W. O'Hearn. OOPSLA 2022. ([pdf](pub/2022_oopsla.pdf))

- **Concurrent Incorrectness Separation Logic** with Azalea Raad, Derek Dreyer, and Peter W. O'Hearn. POPL 2022. ([pdf](pub/2022_popl.pdf))

- **Local Reasoning About the Presence of Bugs: Incorrectness Separation Logic** with Azalea Raad, Hoang-Hai Dang, Derek Dreyer, Peter W. O'Hearn, and Jules Villard. CAV 2020. ([pdf](pub/2020_cav.pdf))

- **A Forward Analysis for Recurrent Sets** with Alexey Bakhirkin and Nir Piterman. SAS 2015. ([pdf](pub/2015_sas.pdf))

- **Spatial Interpolants** with Aws Albarghouthi, Byron Cook, and Zachary Kincaid. ESOP 2015. ([pdf](pub/2015_esop_ext.pdf))

- **Backward Analysis via over-Approximate Abstraction and under-Approximate Subtraction** with Alexey Bakhirkin and Nir Piterman. SAS 2014. ([pdf](pub/2014_sas_ext.pdf))

- **Computing All Implied Equalities via SMT-Based Partition Refinement** with Nikolaj S. Bjørner. IJCAR 2014. ([pdf](pub/2014_ijcar.pdf))

- **Resourceful Reachability as HORN-LA** with Nikolaj S. Bjørner, Samin Ishtiaq, Jael E. Kriener, and Christoph M. Wintersteiger. LPAR 2013. ([pdf](pub/2013_lpar.pdf))

- **Diagnosing Abstraction Failure for Separation Logic-Based Analyses** with Arlen Cox, Samin Ishtiaq, and Christoph M. Wintersteiger. CAV 2012. ([pdf](pub/2012_cav_ext.pdf))

- **SLAyer: Memory Safety for Systems-Level Code** with Byron Cook and Samin Ishtiaq. CAV 2011. ([pdf](pub/2011_cav.pdf))

- **A Proposal for Weak-Memory Local Reasoning** with Ian Wehrman. LOLA 2011. ([pdf](pub/2011_lola.pdf))

- **Precision and the Conjunction Rule in Concurrent Separation Logic** with Alexey Gotsman and Byron Cook. MFPS 2011. ([pdf](pub/2011_mfps.pdf))

- **Structuring the Verification of Heap-Manipulating Programs** with Aleksandar Nanevski and Viktor Vafeiadis. POPL 2010. ([pdf](pub/2010_popl.pdf)) ([coq](pub/2010_popl_coq.tgz))

- **Scalable Shape Analysis for Systems Code** with Hongseok Yang, Oukseh Lee, Cristiano Calcagno, Byron Cook, Dino Distefano, and Peter W. O'Hearn. CAV 2008. ([pdf](pub/2008_cav_1.pdf))

- **Thread Quantification for Concurrent Shape Analysis** with Tal Lev-Ami, Roman Manevich, G. Ramalingam, and Mooly Sagiv. CAV 2008. ([pdf](pub/2008_cav_2.pdf))

- **Heap Decomposition for Concurrent Shape Analysis** with Roman Manevich, Tal Lev-Ami, Mooly Sagiv, and Ganesan Ramalingam. SAS 2008. ([pdf](pub/2008_sas_ext.pdf))

- **Local Reasoning for Storable Locks and Threads** with Alexey Gotsman, Byron Cook, Noam Rinetzky, and Mooly Sagiv. APLAS 2007. ([pdf](pub/2007_aplas_ext.pdf))

- **Arithmetic Strengthening for Shape Analysis** with Stephen Magill, Edmund M. Clarke, and Byron Cook. SAS 2007. ([pdf](pub/2007_sas.pdf))

- **Shape Analysis for Composite Data Structures** with Cristiano Calcagno, Byron Cook, Dino Distefano, Peter W. O'Hearn, Thomas Wies, and Hongseok Yang. CAV 2007. ([pdf](pub/2007_cav.pdf))

- **Thread-Modular Shape Analysis** with Alexey Gotsman, Byron Cook, and Mooly Sagiv. PLDI 2007. ([pdf](pub/2007_pldi.pdf))

- **Shape Analysis by Graph Decomposition** with Roman Manevich, Byron Cook, G. Ramalingam, and Mooly Sagiv. TACAS 2007. ([pdf](pub/2007_tacas.pdf))

- **Variance Analyses From Invariance Analyses** with Aziem Chawdhary, Byron Cook, Dino Distefano, and Peter W. O'Hearn. POPL 2007. ([pdf](pub/2007_popl.pdf))

- **Interprocedural Shape Analysis with Separated Heap Abstractions** with Alexey Gotsman and Byron Cook. SAS 2006. ([pdf](pub/2006_sas.pdf))

- **Automatic Termination Proofs for Programs with Shape-Shifting Heaps** with Byron Cook, Dino Distefano, and Peter W. O'Hearn. CAV 2006. ([pdf](pub/2006_cav.pdf))

- **Strong Update, Disposal, and Encapsulation in Bunched Typing** with Peter W. O'Hearn. MFPS 2006. ([pdf](pub/2006_mfps.pdf))

- **Smallfoot: Modular Automatic Assertion Checking with Separation Logic** with Cristiano Calcagno and Peter W. O'Hearn. FMCO 2005. ([pdf](pub/2005_fmco.pdf))

- **Verification Condition Generation and Variable Conditions in Smallfoot** with Cristiano Calcagno and Peter W. O'Hearn. Draft 2005. Introduction updated 2012. ([pdf](pub/2005_draft.pdf))

- **Symbolic Execution with Separation Logic** with Cristiano Calcagno and Peter W. O'Hearn. APLAS 2005. ([pdf](pub/2005_aplas_ext.pdf))

- **A Decidable Fragment of Separation Logic** with Cristiano Calcagno and Peter W. O'Hearn. FSTTCS 2004. ([pdf](pub/2004_fsttcs.pdf))

- **Linear and Affine Typing of Continuation-Passing Style**. PhD thesis, Queen Mary, University of London 2004. ([pdf](pub/2004_phd.pdf))

- **Extracting the Range of CPS from Affine Typing: Extended Abstract** with Peter W. O'Hearn and Hayo Thielecke. LL 2002. ([pdf](pub/2002_ll.pdf))

- **Linear Continuation-Passing** with Peter W. O'Hearn, Uday S. Reddy, and Hayo Thielecke. HOSC 2002. ([pdf](pub/2002_hosc.pdf))

- **Linearly Used Continuations** with Peter W. O'Hearn, Uday S. Reddy, and Hayo Thielecke. CW 2001. ([pdf](pub/2001_cw.pdf))
