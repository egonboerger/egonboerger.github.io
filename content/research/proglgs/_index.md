---
title: "Programming Languages: Semantics and Implementation"
type: page
_build:
  list: never
---
In the research reported here, the ASM (Abstract State Machines) method has been used to develop a method for defining and analysing, in a rigorous but concise, complete but programmer friendly way, the dynamic semantics of real-life programming languages and of their implementation on virtual or real machines. The covered programming paradigms include

- oo programming languages: [JAVA](/jbook) , [C#](/Papers/CSharp/CSharpSemant.pdf) (TCS 336,2005), [CommonJC#Lg](/Papers/CSharp/JavaCsharp.pdf) (LNCS 3188, 2004)
- imperative programming languages ([OCCAM](/Papers/Architecture/Occam.pdf) and its verified [Transputer Compilation](/Papers/Architecture/Transputer.pdf))
- logic programming languages ([ISO-PROLOG](/Papers/LogicPgg/prolog.pdf) and its verified [WAM Compilation](/Papers/LogicPgg/wamFeb94.pdf))

 

The operational and abstract character of ASMs

- makes the FAITHFULNESS of the definitions with respect to the design intentions checkable by direct inspection (falsifiable in the Popperian sense),
- supports, by stepwise refinements, LINKing the high-level definition in a transparent way TO its IMPLEMENTATION, where each refinement step reflects design decisions one wants to be documented for future reference (extensions, modifications, maintenance)
- provides a convenient basis for turning the definitions into EXECUTABLE MODELS which can be used for validation and experiments,
- simplifies the (mathematical or machine checked) justification of the correctness of the design offering a RIGOROUS framework for the ANALYSIS OF RUN TIME PROPERTIES at the appropriate level of abstraction


For a systematic exposition of the ASM systems engineering method in its full generality see the [AsmBook](/AsmBook). For machine supported programming language design the method provides a framework which permits the mathematical analysis (verification and validation) of both program behaviour and of language implementations. In particular proven to be correct and machine checked language compilation schemes have been obtained from Java to JVM code, from Occam to Transputer code, from Prolog to WAM code in the references given above.

A survey for 1989-2013is available from [Journal of Logic and Computation](http://logcom.oxfordjournals.org/cgi/reprint/exu077?ijkey=6wNaMzGREbzuGDe&keytype=ref) (2014) elaborated from an [invited lecture](/Talks/Cambridge13Talk.pdf) at the MS Research Workshop on Scalabe Language Specification (Cambridge 2013).

## Book 
### [Java and the JavaVirtual Machine: Definition, Verification, Validation](/jbook)  
(by R. Stärk, J. Schmid, E. Börger,  Springer-Verlag, 2001)

This book provides a structured and high-level description, together with a mathematical and an experimental analysis, of Java and of the Java Virtual Machine (JVM), including the standard compilation of Java programs to JVM code and the security critical bytecode verifier component of the JVM. The following fundamental property of JVM verification and execution of compiled Java programs is analysed and proved:

> Under explicitly stated conditions, any well-formed and well-typed Java program, when correctly compiled, passes the verifier and is executed on  the JVM. It executes without violating any run-time checks, and is correct with respect to the expected behavior as defined by the Java machine.

The description is structured into modules, and its abstract character implies that it is truly platform and programming language independent. It comes with a natural refinement to executable machines on which code can be tested. The method we develop for this purpose can be applied to other virtual machines and to other programming languages as well.

The method developed in this book has been reused in 2003 to model and analyse the static and dynamic semantics of C# ([Draft](/Papers/CSharp/CSharpSemant.pdf), Final version in TCS 336, 2005), including an analysis of the .NET exception handling mechanism ([Draft](/Papers/CSharp/ExcCLRPilsen05.pdf), Final version in [JOT 3.5](http://www.jot.fm/issues/issue_2006_04/article1) (2006) 5-34)

## Papers
- [Semantics of C#](/Papers/CSharp/CSharpSemant.pdf) (Draft, Final version in TCS 336, 2005)
- [Modeling the .NET CLR Exception Handling Mechanism for a Mathematical Analysis](http://www.jot.fm/issues/issue_2006_04/article1)  JOT 3.5 (2006) 5-34
- [OCCAM](/Papers/Architecture/Occam.pdf) and its verified compilation to [TRANSPUTER](/Papers/Architecture/Transputer.pdf) code
- [ISO-PROLOG and its verified compilation to Warren Abstract Machine code](/prologwam.html)
- Refinement of Prolog/WAM design and verification by introducing
    - abstract types [PROTOS-L](/Papers/LogicPgg/pam1.pdf) (see [abstract](http://www.fernuni-hagen.de/wbs/research/papers/res/BeierleBoerger96_Journal_FAC.abstract.html))
    - polymorphic order-sorted types [PROTOS-L/PAM](/Papers/LogicPgg/pam2.pdf) (see [abstract](http://www.fernuni-hagen.de/wbs/research/papers/res/BeierleBoerger96_Journal_FAC_PartII.abstract.html))
    - constraints [CLP(R)/CLAM](/Papers/LogicPgg/clam.pdf)

- Refining logic programming by introducing:
    - Constraints: Prolog III, see Springer LNCS 533 (1991) 67-79
    - Pruning: [Goedel](/Papers/LogicPgg/goedel.pdf)
    - Functional Programming features:  
        - [Babel](/Papers/LogicPgg/babelifip.pdf)
        - [FullVersionTR](/Papers/LogicPgg/babeltr.pdf)  
    - Parallel execution:  [Parlog](/Papers/LogicPgg/parlog.pdf)

 - Early ASM models of Java and of the Java Virtual Machine (which have been corrected, completed and streamlined in the [book](/jbook) mentioned above and therefore by now are of historical interest only)  
    appeared in:
    - Springer LNCS 1523 (1999) 353 - 404: early (1997) ASM interpreter for Java
    - Springer LNCS 1450 (1998) 17- 35: compilation scheme Java2JVM with correctness proof outline 
    - Springer Book (2000) `Architecture Design and Validation Methods': early ASM interpreter for JVM
    - Software--Concepts and Tools 19 (4) 175-178, 2000: Initialization problems in Java/JVM  
    - IEEE Transactions of Software Engineering 26 (10) 2000: correctness proof for Java/JVM exception handling

- More material up to the year 2000 can be obtained at the Website for Abstract State Machines.