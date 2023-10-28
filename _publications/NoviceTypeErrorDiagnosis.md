---
title: "Novice Type Error Diagnosis with Natural Language Models"
collection: publications
permalink: /publication/2022-11-25-Novice-Type-Error-Diagnosis-with-Natural-Language-Models
excerpt: ''
date: 2022-11-25
venue: 'APLAS 2022'
paperurl:
citation: 'Geng, C., Ye, H., Li, Y., Han, T., Pientka, B., & Si, X. (2022, November). Novice Type Error Diagnosis with Natural Language Models. In Asian Symposium on Programming Languages and Systems (pp. 196-214). Cham: Springer Nature Switzerland.'
---
<!-- This [paper](https://link.springer.com/chapter/10.1007/978-3-031-21037-2_10) proposes a variant of [BERT](https://arxiv.org/abs/1810.04805) and is fine-tuned to
capture type errors in OCaml programs. With this fine-tuning method, one can
easily obtain similar models tackling other programming languages -->
Strong static type systems help programmers eliminate many errors without much burden of supplying type annotations. However, this flexibility makes it highly non-trivial to diagnose ill-typed programs, especially for novice programmers. Compared to classic constraint solving and optimization-based approaches, the data-driven approach has shown great promise in identifying the root causes of type errors with higher accuracy. Instead of relying on hand-engineered features, this work explores natural language models for type error localization, which can be trained in an end-to-end fashion without requiring any features. We demonstrate that, for novice type error diagnosis, the language model-based approach significantly outperforms the previous state-of-the-art data-driven approach. Specifically, our model could predict type errors correctly 62% of the time, outperforming the state-of-the-art Nate’s data-driven model by 11%, in a more rigorous accuracy metric. Furthermore, we also apply structural probes to explain the performance difference between different
language models.
[Download paper here](https://arxiv.org/pdf/2210.03682.pdf)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->