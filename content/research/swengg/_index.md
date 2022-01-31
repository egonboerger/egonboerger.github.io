---
title: "Software Engineering"
type: page
_build:
  list: never
---
In the research reported here, the ASM (Abstract State Machines) method has been used to develop a practically viable method for defining, in a rigorous but concise way, satisfactory ground models for software requirements. Such ground models can be refined in a controllable way to executable code. The operational and abstract character of ASMs

- makes the FAITHFULNESS OF THE GROUND MODEL with respect to the informally given requirements checkable for the application domain expert (falsifiable in the Popperian sense), namely by direct inspection. See the papers on the ASM **Ground Model Method**,  the modeling constituent of the Asm Method:
  - 2007: [Ground Models And Refinements](/Papers/Methodology/VstteFacJ06.pdf) Formal Aspects of Computing 19: 225-24
  - 2004: [Ground Models For Requirements Engineering](/Papers/SwEngg/GroundModMethod.pdf) Springer LNCS 2772,  146-161
  - 1995: [Why Asm Ground Models](/Papers/Methodology/WhyAsm95.pdf)
  - 1999: [Pragmatics Of ASM Ground Models](/Papers/Methodology/HighLevelDesign99.PDF)
  - 1994: [Logic Programming Ground Models](/Papers/LogicPgg/surveyifip.pdf)

- provides the possibility to make the ground model into an EXECUTABLE MODEL which can be used for high-level validation and experimentation. For an open source execution environment see CoreAsm.

- supports, by stepwise refinements, LINKing the high-level definition in a transparent way TO its IMPLEMENTATION, where each refinement step reflects design decisions one wants do be documented for future reference (extensions, modifications, maintenance). See the ASM [Refinement Method](/Papers/Methodology/RefineFACS.pdf) paper, an introduction into the refinement constituent of the Asm Method.

- simplifies the system analysis, necessary for the justification of the design correctness, by offering a RIGOROUS framework for the ANALYSIS OF RUN TIME PROPERTIES at the appropriate level of abstraction. This makes the ASM method suitable in connection with the [VerifiedSoftware Challenge](/Papers/Methodology/VstteFacJ06.pdf).


For a systematic exposition of the ASM systems engineering method in its full generality see the [AsmBook](/asmbook).

The following papers pioneered some characteristic and industrial applications of the method to build, analyze and refine ground models for control systems and web services.


## Papers

- Workflows, Web Services, Business Processes, Interaction Patterns: An ASM-Based Approach. [Survey](/Papers/Bpmn/BpmnAbz08.pdf). Final version in Proc. ABZ 2008 - International Conference on ASM, B and Z. Springer LNCS 5238.

- **Web Services Mediator** model (also known as [Virtual Provider](/Papers/SwEngg/VPManchester.pdf) ground model). Final version in Proc. ICFEM’05, Springer LNCS 3785, 2005, pp. 81-95. A refinement to a high-level model for [Semantic Web Service Discovery](/Papers/SwEngg/VP_IJBPIM.pdf) appeared in International Journal of Business Process Integration and Management (IJBPIM) Vol.4, Issue 1, December 2006. ISSN (Online): 1741-8771, ISSN (Print): 1741-8763

- **Service Interaction Patterns** ([Draft](/Papers/SwEngg/InteractionPattern.pdf) Final version in Proc. ICFEM’05, Springer LNCS 3785 (2005),  pp. 5-35, ISSN 0302-9743. )

- **Production Cell** case study, proposed for a competition and comparison of formal methods for software development by C. Lewerentz and T. Lindner in Springer LNCS 891. From a user inspectable ASM [ground model](http://www.jucs.org/jucs_3_5/integrating_asm), going through an intermediate refined ASM model, Luca Mearelli has derived [C++ code](http://jucs.org/jucs_3_5/integrating_asm/Boerger_E.pdf) which has been extensively and successfully validated controlling the simulator made available for the competition by FZI Karlsruhe. The required safety and liveness properties, which we prove by standard mathematical arguments to hold in the ASM ground model, have been successfully [model checked](http://www.jucs.org/jucs_3_5/model_checking) by Kirsten Winter (see abstract). See also Chapter 5.1 of [AsmBook](/asmbook).

- **Steam Boiler** case study, proposed for an international competition to a [Dagstuhl seminar on formal program specification and development methods](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=9523). The informal problem formulation by Jean-Raymond Abrial, an executable steam boiler simulator developed by Anne Loetzbeyer, and 23 problem solutions, using different methods, are contained in the CD accompanying Springer [LLNCS 1165](https://link.springer.com/book/10.1007/BFb0027227) Formal Methods for Industrial Applications, now available through the ABZ website.  

  Using ASMs (see abstract), starting from a user inspectable ground model which formalizes the informally expressed requirements, and going through intermediate refined models which reflect further design decisions, [C++](/Papers/boerger/steamcode.ps)??? code has been developed and validated by Igor Durdanovic (and is available for further testing or experimentation on the CD ROM accompanying the Springer LLNCS vol. 1165 and available at the ABZ website)
 
- **Light Control** case study,  proposed for a comparison of requirements engineering methods to a [Dagstuhl seminar on Requirements Capture/Documentation/Validation](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=99241), organized by Egon Boerger (Universita di Pisa), Dave Parnas (McMaster University, CAN), Baerbel Hoerger (Daimler-Chrysler, Ulm), and Dieter Rombach (Universitaet Kaiserslautern) from June 14-18, 1999. Some problem solutions have been selected for publication in a [special issue of the Journal of Universal Computer Science](http://www.jucs.org/jucs_6_7). This includes an [ASM ground model](/Papers/SwEngg/LightControl.pdf), which has been made executable in [AsmGofer](http://www.tydo.de/AsmGofer) by [J. Schmid](http://www.tydo.de/). See also Chapter 6.2 of  [AsmBook](/asmbook).

- **Falko**, the first industrial reengineering application of the Ground Model Method.  See the [Falko experience report](/Papers/SwEngg/Falko.pdf). For a later similar reengineering application of the ASM Ground Model Method at Microsoft Research see the [debugger experience report](/Papers/SwEngg/Debugger.pdf).