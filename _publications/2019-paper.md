---
title: "Simplifying CDCL Clause Database Reduction"
collection: publications
category: manuscripts
permalink: /publications/2019-paper
excerpt: 'Sima Jamali and David Mitchell'
date: 2019-01-01
venue: 'The International Conference on Theory and Applications of Satisfiability Testing (SAT)'
paperurl: 'http://simajam.github.io/files/sat19.pdf'
---

CDCL SAT solvers generate many \learned" clauses, so effective clause database reduction strategies are important to performance.
Over time reduction strategies have become complex, increasing the difficulty of evaluating particular factors or introducing new refinements. At the same time, it has been unclear if the complexity is necessary. We introduce a simple online clause reduction scheme, which involves no sorting. We instantiate this scheme with simple mechanisms for taking into account clause activity and LBD within the winning solver from the 2018 SAT Solver Competition, obtaining performance comparable to the original. We also present empirical data on the e effects of simple measures of clause age, activity, and LBD on performance.
