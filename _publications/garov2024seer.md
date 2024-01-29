---
ref: garov2024seer
title: "Hiding in Plain Sight: Disguising Data Stealing Attacks in Federated Learning"
authors: Kostadin Garov, Dimitar I. Dimitrov, Nikola Jovanović, Martin Vechev
year: 2024
month: 05
venue: ICLR
projects: safeai
bibtex: '@inproceedings{
			garov2024seer,  
			title={Hiding in Plain Sight: Disguising Data Stealing Attacks in Federated Learning},  
			author={Kostadin Garov and Dimitar I. Dimitrov and Nikola Jovanović and Martin Vechev},  
			booktitle={International Conference on Learning Representations},  
			year={2024}
		}'
paper: https://openreview.net/forum?id=krx55l2A6G
---

Malicious server (MS) attacks have enabled the scaling of data stealing in federated learning to large batch sizes and secure aggregation, settings previously considered private. However, many concerns regarding client-side detectability of MS attacks were raised, questioning their practicality once they are publicly known. In this work, for the first time, we thoroughly study the problem of client-side detectability. We demonstrate that most prior MS attacks, which fundamentally rely on one of two key principles, are detectable by principled client-side checks. Further, we formulate desiderata for practical MS attacks, and propose SEER, a novel attack framework that satisfies all desiderata, while stealing user data from gradients of realistic networks, even for large batch sizes (up to 512 in our experiments) and under secure aggregation. The key insight of SEER is the use of a secret decoder, which is jointly trained with the shared model. Our work represents a promising first step towards more principled treatment of MS attacks, paving the way for realistic data stealing that can compromise user privacy in real-world deployments.