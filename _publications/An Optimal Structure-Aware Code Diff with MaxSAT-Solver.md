---
title: "An Optimal Structure-Aware Code Difference Framework with MaxSAT-Solver"
collection: publications
permalink: /publication/2023-10-27-An_Optimal_Structure-Aware_Code_Difference_Framework_with_MaxSAT-Solver
excerpt: 'The Abstract Syntax Tree (AST) serves as a pivotal representation of program codes, offering a structured and hierarchical view of the program’s syntax. When developers modify code, the underlying AST also evolves to reflect these changes. Tree-diff algorithms, such as truediff and Gumtreediff, are developed to compare different versions of the AST and identify the modifications made between them. However, these heuristics are based on certain vertex matching methods that do not ensure optimality and preciseness. In this study, I propose a novel tree-diff approach that utilizes a MaxSAT (Maximum satisfiability) solver to address this issue. By encoding potential vertex matches and edges with associated costs as a tree-diff SAT problem, the MaxSAT solver effectively minimizes the edit distance and reveals the optimal vertex matching plan.'
date: 2023-10-27
venue: 'Splash 2023 Student Research Competition'
paperurl:
citation: 'Ye, Haolin. "An Optimal Structure-Aware Code Difference Framework with MaxSAT-Solver." Companion Proceedings of the 2023 ACM SIGPLAN International Conference on Systems, Programming, Languages, and Applications: Software for Humanity. 2023.'
---
The Abstract Syntax Tree (AST) serves as a pivotal representation of program codes, offering a structured and hierarchical view of the program’s syntax. When developers modify code, the underlying AST also evolves to reflect these changes. Tree-diff algorithms, such as truediff and Gumtreediff, are developed to compare different versions of the AST and identify the modifications made between them. However, these heuristics are based on certain vertex matching methods that do not ensure optimality and preciseness. In this study, I propose a novel tree-diff approach that utilizes a MaxSAT (Maximum satisfiability) solver to address this issue. By encoding potential vertex matches and edges with associated costs as a tree-diff SAT problem, the MaxSAT solver effectively minimizes the edit distance and reveals the optimal vertex matching plan.

[Download paper here](https://dl.acm.org/doi/pdf/10.1145/3618305.3623601)