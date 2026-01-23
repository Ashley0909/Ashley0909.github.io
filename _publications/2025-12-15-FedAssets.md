---
title: "Transforming Threats to Assets: Utilizing Backdoor Attack Models in Federated Learning"
collection: publications
status: published
permalink: /publication/fedassets
excerpt: "This paper defends backdoor malicious FL clients and extract useful information from them to aid global model learning."
date: 2025-12-15
venue: "IEEE Transaction on Consumer Electronics"
paperurl: "https://ieeexplore.ieee.org/document/11313588"
citation: "Hoi-Ting, Au & He, Ligang & Mehr Nezhad, Mahshid & Maple, Carsten. (2025). Transforming Threats to Assets: Utilizing Backdoor Attack Models in Federated Learning. IEEE Transactions on Consumer Electronics. PP. 1-1. 10.1109/TCE.2025.3647772."
---
Federated Learning (FL) is recognized as a privacy-preserving machine learning technique suitable for distributed devices in consumer electronics. However, FL is still vulnerable to backdoor attacks, where malicious clients poison the global model to misclassify triggered inputs while performing normally on clean data. While existing defence techniques focus on eliminating malicious clients, this paper proposes a novel technique called FedAssets. In FedAssets, we uncover distinctive parameter patterns in malicious local models and introduce a clustering-based approach to differentiate between malicious and benign clients. Further, we develop a technique to extract useful information from malicious local models and integrate it effectively, together with benign models, into the global model. Extensive experiments demonstrate that FedAssets outperforms existing techniques, improving model accuracy on clean data up to 7% while achieving up to 35% accuracy in eliminating poisoned information in the global model.
