---
title: Optimal Clustering with Bandit Feedback
description: Vincent Y. F. Tan
date: 2022-05-24
publishdate: 2022-05-05
slug: optimal-clustering
image: optimalClustering.png
categories:
    - NUS
---

### Logistics
<p>
    <strong> Time:</strong> 2:00-3:00 PM; 5/24/2022<br>
    <a href="https://stanford.zoom.us/meeting/register/tJwvf-qhqD8qG9wlCniUWI1YaILdFqRhU4Xn" target="_blank" rel="noopener noreferrer">Zoom Link</a><br>
</p>

### Presenter
<p>
    Vincent Y. F. Tan<br>
    Associate Professor and Dean's Chair<br>
    Deparrtment of Electrical and Computer Engineering<br>
    Department of Mathematics<br>
    National University of Singapore<br>
</p>

### Abstract
<p>
    This paper considers the problem of online clustering with bandit feedback. A set of arms (or items) can be partitioned into various groups that are unknown. Within each group, the observations associated to each of the arms follow the same distribution with the same mean vector. At each time step, the agent queries or pulls an arm and obtains an independent observation from the distribution it is associated to. Subsequent pulls depend on previous ones as well as the previously obtained samples. The agent's task is to uncover the underlying partition of the arms with the least number of arm pulls and with a probability of error not exceeding a prescribed constant δ. The problem proposed finds numerous applications from clustering of variants of viruses to online market segmentation. We present an instance-dependent information-theoretic lower bound on the expected sample complexity for this task, and design a computationally efficient and asymptotically optimal algorithm, namely Bandit Online Clustering (BOC). The algorithm includes a novel stopping rule for adaptive sequential testing that circumvents the need to exactly solve any NP-hard weighted clustering problem as its subroutines. We show through extensive simulations on synthetic and real-world datasets that BOC's performance matches the lower bound asymptotically, and significantly outperforms a non-adaptive baseline algorithm.
</p>

### Reference
<p>
    <a href="url" target="_blank" rel="noopener noreferrer">https://arxiv.org/abs/2202.04294</a>
<p>

### Bio
<p>
    Vincent Y. F. Tan received the B.A. and M.Eng. degrees in electrical and information science from Cambridge University in 2005, and the Ph.D. degree in electrical engineering and computer science (EECS) from the Massachusetts Institute of Technology (MIT) in 2011. He is currently a Dean’s Chair Associate Professor with the Department of Electrical and Computer Engineering and the Department of Mathematics, National University of Singapore (NUS). His research interests include information theory, machine learning, and statistical signal processing.
</p>

### Recording
<p>
    <a href="https://www.youtube.com/watch?v=2ALpGsAE2JE" target="_blank" rel="noopener noreferrer">Lecture Recording</a><br>
</p>