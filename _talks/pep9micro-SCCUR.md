---
title: "Pep9Micro: Designing a Microcoded CPU"
collection: talks
type: "Talk"
permalink: /talks/pep9micro-SCCUR
venue: "Southern California Conferences for Undergraduate Research"
date: 2017-11-17
location: "Pasadena, CA"
---

Pep/9 is a 16-bit CISC computer with eight addressing modes used to teach assembly language programming and computer systems concepts. Students program with the applications Pep9 and Pep9CPU, which simulate the Pep/9 computer at two different levels of abstraction. Pep9 allows students to program in assembly language and execute their programs on the virtual machine simulator. At a lower level of abstraction, Pep9CPU allows students to program microcode fragments that implement individual assembly language instructions. This poster describes the development of a third virtual machine, Pep9Micro, that extends the capabilities of Pep9 and Pep9CPU by designing a microcode implementation of the complete Pep/9 instruction set. It provides the assembler from Pep9 and the CPU simulator of Pep9CPU so that complete assembly language programs can be executed at the microcode level spanning two levels of abstraction. Pep9Micro extends the Pep9CPU microcode language with conditional microcode branch instructions and the design of a microcode store. Pep9, Pep9CPU, and Pep9Micro are support software for the text Computer Systems by J. Stanley Warford, and are available on GitHub as open source projects.

Poster from presentation available [here](/files/pep9micro-scurr.pdf).