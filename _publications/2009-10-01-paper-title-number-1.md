---
title: "Exploring Branch Predictors for Constructing Transient Execution Trojans"
collection: publications
permalink: /publication/2020-04-19-Transient
excerpt: ''
date: 2020-04-19
venue: 'ASPLOS'
paperurl: 'http://www.cs.wm.edu/~dmitry/assets/files/zhang2020exploring.pdf'
citation: 'Download at: https://dl.acm.org/doi/10.1145/3373376.3378526'
---
Transient execution is one of the most critical features used in CPUs to achieve high performance. Recent Spectre attacks demonstrated how this feature can be manipulated to force applications to reveal sensitive data. The industry quickly responded with a series of software and hardware mitigations among which microcode patches are the most prevalent and trusted. In this paper, we argue that currently deployed protections still leave room for constructing attacks. We do so by presenting transient trojans, software modules that conceal their malicious activity within transient execution mode. They appear completely benign, pass static and dynamic analysis checks, but reveal sensitive data when triggered. To construct these trojans, we perform a detailed analysis of the attack surface currently present in today's systems with respect to the recommended mitigation techniques. We reverse engineer branch predictors in several recent x86_64 processors which allows us to uncover previously unknown exploitation techniques. Using these techniques, we construct three types of transient trojans and demonstrate their stealthiness and practicality.

[Download paper here](http://www.cs.wm.edu/~dmitry/assets/files/zhang2020exploring.pdf)

Recommended citation: "@inproceedings{10.1145/3373376.3378526,
author = {Zhang, Tao and **Koltermann, Kenneth** and Evtyushkin, Dmitry},
title = {Exploring Branch Predictors for Constructing Transient Execution Trojans},
year = {2020},
isbn = {9781450371025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3373376.3378526},
doi = {10.1145/3373376.3378526},
abstract = {Transient execution is one of the most critical features used in CPUs to achieve high performance. Recent Spectre attacks demonstrated how this feature can be manipulated to force applications to reveal sensitive data. The industry quickly responded with a series of software and hardware mitigations among which microcode patches are the most prevalent and trusted. In this paper, we argue that currently deployed protections still leave room for constructing attacks. We do so by presenting transient trojans, software modules that conceal their malicious activity within transient execution mode. They appear completely benign, pass static and dynamic analysis checks, but reveal sensitive data when triggered. To construct these trojans, we perform a detailed analysis of the attack surface currently present in today's systems with respect to the recommended mitigation techniques. We reverse engineer branch predictors in several recent x86_64 processors which allows us to uncover previously unknown exploitation techniques. Using these techniques, we construct three types of transient trojans and demonstrate their stealthiness and practicality.},
booktitle = {Proceedings of the Twenty-Fifth International Conference on Architectural Support for Programming Languages and Operating Systems},
pages = {667–682},
numpages = {16},
keywords = {side channel, branch predictor, trojan, reverse-engineering, spectre attack, microarchitecture security, covert channel},
location = {Lausanne, Switzerland},
series = {ASPLOS '20}
}"
