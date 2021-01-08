---
title: "Pep9Milli: Verification of CISC Processors using Software Verification Tools"
collection: papers
permalink: /papers/pep9milli
excerpt: 'This paper introduces a process for using open-source software verification tools to verify the correctness of CISC microprocessors.'
date: 2020-02-28
venue: 'N/A'
paperurl: 'http://matthew-mcraven.github.io/files/pep9millitex.pdf'
citation: 'McRaven, Matthew. (2020). &quot;Pep9Milli: Verification of CISC Processors using Software Verification Tools.&quot;'
---

This paper is a WIP, but will hopefully be helpful to others.

This paper introduces a process for using open-source software verification tools to verify the correctness of CISC microprocessors. The three-part process introduces a new language (millicode) at a higher level than microcode. Millicode is compiled to a high-level language (i.e., C) as well as microcode. Software verification tools verify that the high- level language representation meets the processors’s RTL. The process is demonstrated by verifying an existing CISC processor, Pep/9. A partial millicode implementation of Pep/9’s RTL is created and verified using Klee.

[Download paper here](http://matthew-mcraven.github.io/files/pep9millitex.pdf)
