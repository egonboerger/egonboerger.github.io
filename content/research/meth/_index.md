---
title: "Methodological Work"
type: page
_build:
  list: never
---
The research reported here is of methodological nature. It presents contributions to the development of the Abstract State Machines method for system design and analysis, explains why the method works also under industrial constraints and compares it to other well known approaches in the field. For a systematic monograph-and-textbook-style presentation of the method, which covers also the papers referenced below, see the [AsmBook](/asmbook).

## **Development** of the ASM method
- ASM [Ground Model Method](/Papers/SwEngg/GroundModMethod.pdf), an introduction into the modeling constituent of the Asm Method.
- ASM [Refinement Method](/Papers/Methodology/RefineFACS.pdf), an introduction into the refinement constituent of the Asm Method.
- **AsmDefinition**: definition of the computational constituent of the Asm Method.  An informal definition and a formalized one appear in Chapter 2 of [Jbook](/jbook) with updated versions in Chapter 2.2 (Working Definition) and Chapter 2.4 (Detailed Definition: Mathematical Foundation) of the [AsmBook](/asmbook).

## ASM Models for **Fundamental Computational Concepts**
- **A definition of concurrency for ASMs with a Concurrent ASM Thesis**  
  ([paper](/Papers/Methodology/ConcurAsm.pdf) with K.-D.Schewe in Acta Informatica 2015)
- **Composition and Submachine Concepts for Sequential ASMs**  
  (A definition of turbo ASMs, integrating composition and structuring concepts which reflect frequently used refinements of ASMs, in particular SEQ, ITERATE and parameterized (recursive) SUBMACHINEs.) [Abstract](/Papers/Methodology/ComposingASMsabstract.txt). See also Chapter 4.1 of [AsmBook](/asmbook).
- **A model for Recursion in ASMs**  
  (Using turbo ASMs to naturally integrate functional programming techniques into ASMs, illustrated by modelling standard forms of recursion.) [Draft](/Papers/Methodology/RecursorASMs.pdf), appeared in the Proc. of ASM 2003. See also Chapter 4.1.2 of [AsmBook](/asmbook).
- **Abstract State Processes**  
  (An integration of process-algebraic composition and structuring concepts into ASMs, in particular interleaving and selected synchrony.) Invited lecture to ASM 2003, [Draft](/Papers/Methodology/ASP.pdf), appeared in the Proc. Springer LNCS 2589. See also Chapter 4.2 of [AsmBook](/asmbook).
- **A Comparative Study of Computation and Specification Models**  
  Invited lecture to the Action Semantics Workshop at FLOC’02 in Copenhague, [Draft](/Papers/Methodology/Comparison.pdf), appeared in the Proc. BRICS Series NS-02-08, Aarhus 2002. See also a [revised version](/Papers/Methodology/UnivCompMod.pdf) appeared in APAL 2003 and see Chapter 7.1 of [AsmBook](/asmbook).

## **Industrial Applications** of the ASM Method
- Two **industrial experience reports** on software engineering applications of the ASM method under industrial constraints (See also Chapter 9.4 (Making ASMs fit for their Industrial Deployment) of [AsmBook](/asmbook))
    - Report on a Practical Application of ASMs in Software Design ([Falko](/Papers/SwEngg/Falko.pdf) project at Siemens Corporate Research, Munich.)
    - Using Abstract State Machines at Microsoft: [A Case Study](/Papers/SwEngg/Debugger.pdf)
- [ASM Case Study Book](/jbook) (also called Jbook) exhibits ground modeling, refinement, validation and verification of Java and its JVM  implementation
- [Workflow and interaction patterns, business processes, web services](/Workflow.html)

## **Surveys** of the ASM Method
- **Why Use Evolving Algebras for Hardware and Software Engineering** 
  (A non-technical 1995 paper explaining the epistemological reasons  why use ASMs as specification and high-level design language). See also Chapter 9.2 (Recognizing the practical relevance of ASMs) of [AsmBook](/asmbook).
- **High Level System Design and Analysis using Abstract State Machines**  
  (A non-technical introduction explaining the ASM method, surveying its major applications prior to 1999, and comparing it to other major modelling approaches in the literature). See the Introduction and Chapter 1 of [AsmBook](/asmbook).
- **Illustrating to the Practitioner the Power of ASMs for Modelling and Analysing Real-life Systems**  
  A short [Survey](/Papers/Methodology/Modeling.pdf) (taken from Springer LNI Series Vol.P-45 (2004) 235-239) of large-scale and industrial applications of  ASMs. A more detailed survey (as of 2003) is found in Chapter 9 of the[AsmBook](/asmbook).
- [**Using the ASM Method for Hoare’s Verified Software Challenge**](/Papers/Methodology/VstteFacJ06.pdf)
- **Abstract State Machines at the Cusp of the Millenium**  
  (A historical perspective of the ASM method, with a list of challenging future problems. [Draft](/Papers/Methodology/asm2000intro.pdf). See also Chapter 9 (History and Survey of ASM Research) and the list of problems on pg. 429 of [AsmBook](/asmbook).
- **Historical Survey**  
  detailed description of the industrial and academic achievements of the method with an annotated bibliography of over 300 items, covering the period 1984-2001. Title:“The Origins and the Development of the ASM Method for High Level System Design and Analysis”  freely available at [JUCS 8 (1) 2002](http://www.jucs.org/jucs_8_1). Locally a [Draft](/Papers/Methodology/AsmHist02.pdf) version is available. Updated December 2002 version (with 440 items)  in Ch. 9 (History and Survey of ASM Research) of[AsmBook](/asmbook) .

## **Introductions** to the ASM Method
- [**Goals**](/AsmBook/IntroAsmBook.PDF) of the method: describes the goals of the method and its scientific and practical role as a discipline for the engineering of certifiably reliable systems (Introduction to the[AsmBook](/asmbook)) 
- [**Introduction**](/Papers/Methodology/BcsFacs07.pdf) describes the three constituents of the method: machine concept,  ground model concept,  refinement concept (from a talk to BCS/London)    
- **Tutorial Introduction** [From FSM to ASM](/Papers/Methodology/Tutorial05.pdf)  
  final version in Springer LNAI 3717, pp. 264-283, 2005
- **ASM Method: A Quick for Students**. 4 [lectures](http://se.inf.ethz.ch/teaching/ws2004/0239/slides/AsmMethZh04.PDF) delivered at ETH Zuerich, Dec 2004  
- **Discrete Systems Modeling** (explaining the role of ASMs for modeling systems. [Draft Word document](/Papers/Methodology/ModelingDiscreteSystems01.doc), final version in Encyclopedia of Physical Sciences and Technology, Academic Press, 2001). See also Chapter 9 (History and Survey of ASM Research) of [AsmBook](/asmbook).


For more  material, up to date until the year 2000, see the ASM website.


