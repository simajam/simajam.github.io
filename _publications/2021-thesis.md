---
title: "CDCL SAT Solver Heuristics: Clause Management, Instance Structure, and Decisions"
collection: publications
category: thesis
permalink: /publications/2021-thesis
excerpt: 'Sima Jamali'
date: 2021-01-01
venue: 'Simon Fraser University'
paperurl: 'https://summit.sfu.ca/_flysystem/fedora/2022-08/input_data/21687/etd21616.pdf'
---

The Boolean satisfiability problem or SAT is the problem of deciding if a Boolean formula
has a satisfying assignment. It was the first problem shown to be NP-complete, and remains
one of the most well-known and studied NP-complete problems. We do not expect to find
a polynomial time algorithm that solves all SAT problems, as this would imply equivalence
of the complexity classes P and NP, which seems unlikely. However, there are algorithms
and heuristics to solve SAT problems that are often effective in practice. A SAT solver is
a program that takes as input a Boolean formula and tries to find a satisfying assignment
for it. The most-used algorithm in SAT solvers intended for solving real-world problems
is known as Conflict Driven Clause Learning, abbreviated CDCL. Due to its broad usage,
improving the performance of these solvers can have a large impact on other fields that use
SAT solvers and also make SAT solving a useful tool for more applications.

The practical performance of CDCL SAT solvers depends critically on a small number of
key heuristic mechanisms, and work on these heuristics over the past 20 years have improved
CDCL solver performance significantly. This dissertation contributes to our understanding
of two of the key heuristic mechanisms, known as the decision heuristic and the clause
database management scheme. There are two main foci, which are closely related. First
we focus on developing light weighted methods to use measures of instance structure in
solver heuristics. The structure of instances arising from real-world problems seems to be
one of the main features that makes them special but there is little work exploiting structural properties within CDCL solvers. We introduce a new structural measure for SAT
instances, called Centrality, and show that this measure can be used in both decision and
clause management heuristics to improve solver performance. Second, we study different
components of clause database management schemes in order to understand and improve
them. We categorize clauses as permanent and temporary, show that the permanent set is
key to solver performance and propose modifications to the criteria for permanent clauses
to improve performance. In recent years, clause database management strategies used in
high-performance solvers have become complex, making their study and refinement difficult.
We introduce a new clause reduction scheme, called online deletion, which is simple
to implement and results in comparable performance.