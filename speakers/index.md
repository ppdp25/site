---
layout: page
title: Invited speakers
toc: false
show_sidebar: false
hide_footer: true
---

## [Ugo Dal Lago](https://udallago.github.io/)
<img src="https://udallago.github.io/assets/img/picture.jpg" alt="Ugo Dal Lago" width="200"/>

Professor of Computer Science at the University of Bologna since November 2015. He is also affiliated with INRIA Sophia Antipolis.


### Counting Qubits and Gates: Resource Analysis in Quantum Programming Languages

Quantum computing has the potential to revolutionize subfields of computer
science such as cryptography and optimization by providing efficient solutions
to problems currently considered intractable classically speaking. However, as
is well known, today’s quantum hardware remains limited by noise, short
coherence times, and low qubit counts, making the realization of this potential
still a distant goal. In this context, estimating the resources required to
execute quantum programs, such as the number of qubits and quantum gates, is of
paramount importance. In this talk, we will provide an overview of the emerging
research area of quantum resource analysis, beginning with an introduction to
quantum computing and quantum programming languages, followed by a discussion
of several approaches to resource analysis of quantum programs, without aiming
for an exhaustive survey.


## [Robbert Krebbers](https://robbertkrebbers.nl/)

<img src="https://robbertkrebbers.nl/me.jpg" alt="Robbert Krebbers" width="200"/>

Associate professor (universitair hoofddocent, ius promovendi) and vice department head of the 
Department of Software Science of Institute for Computing and Information Sciences at Radboud University Nijmegen, The Netherlands.

### Mechanized Type Soundness for Substructural Types using Iris

Substructural type systems are a good fit to enforce strong safety properties
of higher-order, imperative and concurrent programs. Key examples are the Rust
type system (which enforces the absence of undefined behavior and data races)
and session types (which enforce correct usage of message-passing channels).
Formally proving that these type systems "do their job" (i.e., they enjoy the
"type soundness" property) is challenging. This challenge is exacerbated when
considering combinations of language features ("feature interaction") and
linking against "unsafe" libraries (which have to be verified manually), thus
providing the desire for a scalable approach with support for machine-checked
proofs.

In this talk I will give an introduction to the "logical approach" to type
soundness, which is well-suited to prove soundness of substructural type
systems. I will explain the theory of the logical approach in the context of a
very simple language, which I then gradually scale up to a session-typed
language. I will also demonstrate that the logical approach is well-suited for
the mechanization of challenging type systems in the Rocq prover using the Iris
framework for concurrent separation logic.
