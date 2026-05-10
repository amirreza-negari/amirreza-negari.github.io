+++
title = "Example"
date = "2026-05-08T00:00:00-04:00"
draft = false
description = "A small template note showing equations, sections, and references."
tags = ["example", "template"]
math = true
+++

This is a short example note. I would use this format for a small calculation, a useful
physics idea, or a thought that is not yet a full paper.

## Setup

Suppose a quantum state \(\rho_{ABC}\) is defined on three regions. A useful quantity is
the conditional mutual information

\[
I(A:C|B)_\rho = S(AB)_\rho + S(BC)_\rho - S(B)_\rho - S(ABC)_\rho .
\]

It measures how much correlation remains between \(A\) and \(C\) once the region \(B\)
is known.

## Simple observation

If \(I(A:C|B)_\rho = 0\), then the state has a quantum Markov structure. Informally,
all correlations between the two outer regions can be mediated through the middle
region. One way to remember this is:

\[
A \longleftrightarrow B \longleftrightarrow C .
\]

This is the kind of small fact that can be useful to keep in a note.

## How I might use this template

- Write the main idea in the first paragraph.
- Put the important equation near the top.
- Add a short derivation or explanation.
- End with references or links.

## References

- Hayden, Jozsa, Petz, and Winter, *Structure of states which satisfy strong subadditivity of quantum entropy with equality*.
- Fawzi and Renner, *Quantum conditional mutual information and approximate Markov chains*.
