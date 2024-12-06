---
title: "VEL: A Formally Verified Reasoner for EL++ Description Logic."
collection: publications
category: conferences
permalink: /publication/vel-iswc
date: 2024-11-12
venue: 'ISWC 2024 Poster Track'
paperurl: 'https://ceur-ws.org/Vol-3828/paper22.pdf'
---

Over the past two decades, the Web Ontology Language (OWL) has been instrumental in advancing
the development of ontologies and knowledge graphs, providing a structured framework that enhances
the semantic integration of data. However, the reliability of deductive reasoning within these systems
remains challenging, as evidenced by inconsistencies among popular reasoners in competitions. This
evidence underscores the limitations of current testing-based methodologies, particularly in high-stakes
domains such as healthcare. To mitigate these issues, in this study, we have developed VEL, a formally
verified ℰℒ++ reasoner equipped with machine-checkable correctness proofs that ensure the validity of
outputs across all possible inputs. This formalization, based on the algorithm of Baader et al.[1], has
been transformed into executable OCaml code using the Coq proof assistant’s extraction capabilities.
In addition to producing a correct implementation, our work uncovered two errors in the published
completeness proof that required a modification to the original algorithm.
