---
title: "Architecture Design and Analysis"
type: page
_build:
  list: never
---
In the research reported here,  the ASM (Abstract State Machines) method has been used to develop a practically viable method for defining, in a rigorous but concise way, models for various instruction set architectures and virtual machines.The operational and abstract character of ASMs
- makes the faithfulness of the definitions with respect to the design intentions checkable by direct inspection,
- supports, by stepwise refinements, linking the high-level definition in a transparent and well documented (possibly proven to be correct) way to its implementation.

For a systematic exposition of the ASM systems engineering method in its full generality see the [AsmBook](/AsmBook). The ASM method provides in particular a framework for the design and the mathematical analysis of architectures. The following papers have pioneered the method through some characteristic examples.

- [Java and the JavaVirtual Machine: Definition, Verification, Validation](/jbook)  
  Book by R. Stärk, J. Schmid, E. Börger, Springer-Verlag, 2001

- RISC [DLX](/Papers/Architecture/DlxZum.pdf) Architecture: Springer LNCS 1212 (1997) 151-187 or [AsmBook](/asmbook) Ch.3.3

- [Transputer]() Instruction Set Architecture: The Computer Journal 39 (1) 52-92, 1996.  
  The ground model for the underlying programming language appears in [OCCAM](/Papers/Architecture/Occam.pdf)

- Parallel Processor APE100: Ground model [APESE](/Papers/Architecture/ApeIfip.pdf) and its [verified composition](/Papers/Architecture/ApeIceccs.pdf) (IEEE Proc. ICECCS'95, 145-148). Full Technical Report version [Ape100TR](/Papers/Architecture/ApeAarhus.pdf)

- Parallel Virtual Machine: shortversion [Ifip94](/Papers/Architecture/PVMifip.pdf), full Technical Report version [PVM](/Papers/Architecture/PVM.pdf)

- Hardware Design Language VHDL: [VHDL93Semantics](/Papers/Architecture/VHDL94.pdf) and [VHDL93Interpreter](/Papers/Architecture/VHDL95.pdf)