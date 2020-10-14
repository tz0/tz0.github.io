---
title: "Exploring Branch Predictors for Constructing Transient Execution Trojans"
# collection: publications
permalink: /publication/2020-03-18-TransXTrojan
excerpt: ''
date: 2020-03-18
venue: 'ASPLOS 20'
paperurl: 'https://doi.org/10.1145/3373376.3378526'
citation: 'T Zhang, K Koltermann, D Evtyushkin. Exploring Branch Predictors for Constructing Transient Execution Trojans. ASPLOS, 2020.'
---
Transient execution is one of the most critical features used in CPUs to achieve high performance. Recent Spectre attacks demonstrated how this feature can be manipulated to force applications to reveal sensitive data. The industry quickly responded with a series of software and hardware mitigations among which microcode patches are the most prevalent and trusted. In this paper, we argue that currently deployed protections still leave room for constructing attacks. We do so by presenting transient trojans, software modules that conceal their malicious activity within transient execution mode. They appear completely benign, pass static and dynamic analysis checks, but reveal sensitive data when triggered. To construct these trojans, we perform a detailed analysis of the attack surface currently present in today's systems with respect to the recommended mitigation techniques. We reverse engineer branch predictors in several recent x86_64 processors which allows us to uncover previously unknown exploitation techniques. Using these techniques, we construct three types of transient trojans and demonstrate their stealthiness and practicality.

<!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->

Recommended citation:
<pre><code>
@inproceedings{Zhang2020TransXTrojan,
author = {Zhang, Tao and Koltermann, Kenneth and Evtyushkin, Dmitry},
title = {Exploring Branch Predictors for Constructing Transient Execution Trojans},
year = {2020},
booktitle = {Proceedings of the Twenty-Fifth International Conference on Architectural Support for Programming Languages and Operating Systems},
pages = {667–682},
location = {Lausanne, Switzerland},
series = {ASPLOS '20}
}
</code></pre>