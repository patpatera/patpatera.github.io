---
title: "A Multi-modal Architecture with Spatio-Temporal-Text Adaptation for Video-based Traffic Accident Anticipation"
collection: publications
category: manuscripts
permalink: /publication/IEEE-TCSVT-25
excerpt: 'MASTTA is a parameter-efficient, multi-modal framework that improves traffic accident anticipation by fine-tuning CLIP-based adapters for visual and textual data. By utilizing novel Temporal and Spatial Adapters alongside a Text Adapter, the model captures complex spatio-temporal interactions and aligns them in a joint embedding space. This synergy allows for more accurate, long-range context modeling, outperforming state-of-the-art methods in both earliness and correctness on the DAD and CCD benchmarks.'
date: 2025-03-19
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10933925'
citation: 'P. Patera, Y. -T. Chen and W. -H. Fang, "A Multi-Modal Architecture With Spatio-Temporal-Text Adaptation for Video-Based Traffic Accident Anticipation," in IEEE Transactions on Circuits and Systems for Video Technology, vol. 35, no. 9, pp. 8989-9002, Sept. 2025, doi: 10.1109/TCSVT.2025.3552895.'
---

Early and precise accident anticipation is critical for preventing road traffic incidents in advanced traffic systems. This paper presents a Multi-modal Architecture with Spatio-Temporal-Text Adaptation (MASTTA), featuring a Visual Encoder and a Text Encoder within a streamlined end-to-end framework for traffic accident anticipation. Both encoders leverage the CLIP model, pre-trained on large-scale text-image pairs, to utilize visual and textual information effectively. MASTTA captures complex traffic patterns and relationships by fine-tuning only the adapters, reducing retraining demands. In the Visual Encoder, spatio-temporal adaptation is achieved through a novel Temporal Adapter, a novel Spatial Adapter, and an MLP Adapter. The Temporal Adapter enhances temporal consistency in accident-prone areas, while the Spatial Adapter captures spatio-temporal interactions among visual cues. The Text Encoder, equipped with a Text Adapter and an MLP Adapter, aligns latent textual and visual features in a joint embedding space, refining semantic representation. This synergy of text and visual adapters enables MASTTA to model complex spatial interactions across long-range temporal context, improving accident anticipation. We validate MASTTA on DAD and CCD datasets, demonstrating significant improvements in both the earliness and correctness compared to state-of-the-art methods.
