---
title: "Probability from Possibility: Probabilistic Confidentiality for Storage Systems Under Nondeterminism"
collection: publications
category: conferences
permalink: /publication/confrm
date: 2024-07-08
venue: 'CSF 2024'
paperurl: 'https://ieeexplore.ieee.org/document/10664216'
---

Nondeterminism, such as system crashes, poses an important challenge to the security of storage systems by making leakages possible through secret-dependent result probabilities. This paper proposes a new possibilistic confidentiality specification prohibiting such probabilistic leakages. Our specification is preserved under simulation to enable modularity and is sequentially compositional. We implemented our specification in a framework that contains structures to implement storage systems and prove their confidentiality in a modular fashion. On top of our framework, we implemented the first crash-safe file system with a termination-insensitive version of our specification and machine-checkable confidentiality proofs. Our evaluation shows that proving confidentiality incurs 9.2x proof overhead per line of implementation code. Both our framework and file system are implemented in Coq and extracted to Haskell to obtain an executable artifact.
