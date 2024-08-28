---
title: "An Experimental Study of Permanently Stored Learned Clauses"
collection: publications
category: manuscripts
permalink: /publications/2021-paper
excerpt: 'Sima Jamali and David Mitchell'
date: 2021-01-01
venue: 'Pragmatics of SAT'
paperurl: 'http://simajam.github.io/files/sat21.pdf'
---

Abstract. Modern CDCL SAT solvers learn clauses rapidly, and an important heuristic is the clause deletion scheme. Most current solvers have two (or more) stores of clauses. One has “valuable” clauses which are never deleted. Most learned clauses are added to the other, with an aggressive
deletion strategy to restrict its size. Recent solvers in the MapleSAT family, have comparatively complex deletion schemes, and perform well. Many solvers store only binary clauses permanently, but MapleLCMDistChronoBT stores clauses with small LBD permanently. We report an experimental study of the permanent clause store in MapleLCMDistChronoBT. We observe that this store can get quite large, but several methods for limiting its size reduced performance. We also show that alternate size and LBD-based criteria improve performance, while still having large permanent stores. In particular, saving clauses up to size 8, and adding small numbers of high-centrality clauses, both improved performance, with the best improvement using both methods.
