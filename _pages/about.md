---
permalink: /
title: "About Me -- AI Researcher & Board Rider"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

AI/ML Research Engineer
======

**Multimodal AI · Computer Vision · Generative AI · On-Device Intelligence**

AI/ML Research Engineer with a Ph.D. and more than five years of experience in multimodal AI, computer vision, image and video processing, efficient deep learning, and edge deployment. I develop AI systems across data preparation, model adaptation, training, evaluation, prototyping, and real-time inference.

My work combines research depth with practical software engineering: from vision-language models and spatio-temporal reasoning to RAG applications and optimized deployment on iPhone and NVIDIA Jetson. My research has appeared at ICLR, CVPR Findings, IEEE TCSVT, and IEEE ICIP, and I am a co-inventor on a U.S. patent.

**Location:** New Taipei, Taiwan  
**Work authorization:** Authorized to work in Taiwan under a long-term open work permit.

Selected Impact
======

- Deployed a **31M-parameter multimodal model at 30-60 FPS** on iPhone and NVIDIA Jetson Orin Nano.
- Reduced trainable parameters by **85%** using parameter-efficient vision-language adapters.
- Built reproducible data-processing, training, and evaluation pipelines for more than **2.5 million video frames**.
- Achieved a **5% ROC-AUC improvement** through temporal-shift adaptation for video understanding.
- Achieved **99% verification reliability** in a patented real-time audio-visual biometric system.
- Produced **four peer-reviewed first-author papers** and co-invented a **U.S. patent**.
- Mentored more than **five graduate students** and supported courses with over **40 students per class**.

Work Experience
======

### Research Assistant — [Taiwan Tech (NTUST)](https://www.ece.ntust.edu.tw/)

*Taipei, Taiwan · Sep. 2020 - Feb. 2026*

- Led a five-year research program in computer vision, vision-language adaptation, spatio-temporal reasoning, video understanding, knowledge distillation, model evaluation, and edge AI deployment.
- Proposed **Temporally Shifted Distillation**, allowing lightweight video models to learn predictive temporal representations from a frozen image-based teacher.
- Designed recurrent and linear-attention architectures for efficient long-range temporal reasoning.
- Developed parameter-efficient spatio-temporal adapters with **85% fewer trainable parameters** than full fine-tuning while preserving multimodal alignment.
- Built reproducible processing, training, evaluation, and ablation pipelines for more than **2.5 million video frames** with natural-language descriptions.
- Evaluated model quality and deployment readiness using ROC-AUC, mAP, accuracy, latency, model size, and FPS.
- Built end-to-end camera-perception prototypes and optimized inference through ONNX, TensorRT, CUDA, and CoreML.
- Deployed models on NVIDIA Jetson Orin Nano and iPhone at **30-60 FPS**.
- Developed autonomous-vehicle perception systems with [ITRI](https://www.itri.org.tw/) and [Delta Electronics](https://www.deltaww.com/en-US/company/innovation).
- Mentored more than five graduate students in research planning, implementation, experimental design, evaluation, and code review.

### Teaching Assistant — [Taiwan Tech (NTUST)](https://www.ece.ntust.edu.tw/)

*Taipei, Taiwan · Feb. 2021 - Jan. 2026*

- Supported courses in **Large Language Models and Applications**, **Intelligent Video Surveillance Systems**, and **Databases**.
- Guided classes of more than 40 students through practical AI and software-engineering assignments.
- Assisted students with model implementation, experiment design, debugging, and technical communication.

### Research Engineer — [NTIS Research Centre](https://www.ntis.zcu.cz/en/index.html)

*Czech Republic · Jan. 2019 - Oct. 2020*

- Co-invented a patented real-time audio-visual biometric system that achieved **99% verification reliability**.
- Developed modular C++/OpenCV/dlib pipelines for face detection, feature extraction, biometric representation, and multimodal matching.
- Designed software components and APIs connecting the C++ computer-vision backend to a Node.js authentication service.
- Generated QR-encoded identity hashes for real-time person identification, authentication, and verification.
- Contributed to the resulting [U.S. patent](https://patents.google.com/patent/US20250184148A1/en).

### R&D Software Engineer — [Palaxo International Ltd.](https://www.palaxo.com/)

*Czech Republic · Sep. 2017 - Sep. 2020*

- Architected a production-oriented C++ and OpenCV image-processing framework for an enterprise document-workflow platform.
- Developed automated OCR-based text extraction for heterogeneous image-based documents.
- Implemented dynamic masking and anonymization of sensitive information.
- Integrated computer-vision modules into production workflows managing more than **10,000 documents** across Europe and the GCC.

### Software Engineer — Kerio Technologies, Inc.

*Czech Republic · Jun. 2016 - May 2017*

- Implemented geolocation-based security features in C++ for a proprietary embedded router platform.
- Contributed to device-level access protection, debugging, and embedded networking software.

Selected Projects
======

### [Real-Time Traffic Hazard Reasoning on Edge Devices](https://patpatera.github.io/HERMES-Realtime-Traffic-Hazard-Anticipation/)

*Multimodal AI · Computer Vision · Edge Deployment · 2025-2026*

- Developed a **31M-parameter multi-task model** for traffic-hazard anticipation, localization, and live risk scoring from dashcam video.
- Deployed the model through CoreML on iPhone and ONNX/TensorRT/CUDA on NVIDIA Jetson Orin Nano.
- Achieved **30-60 FPS** frame-by-frame inference on edge hardware.
- Built an iOS safety dashboard with live risk visualization, hazard localization, and sound and vibration alerts.
- Validated the complete system through on-road testing in Taipei.

### [Generative AI Research Assistant with RAG](https://github.com/patpatera/agentic-research-assistant)

*Generative AI · Semantic Search · Local Inference · 2025*

- Built a LangChain-based workflow for scientific-paper discovery, downloading, indexing, retrieval, and grounded question answering.
- Indexed full-text papers in ChromaDB using Hugging Face embeddings for semantic passage retrieval.
- Served Gemma and Qwen models locally through Ollama.
- Developed a FastAPI backend and Streamlit interface for locally hosted document search and interactive research assistance.

### [Parameter-Efficient Vision-Language Model Adaptation](https://github.com/patpatera/MASTTA)

*Vision-Language Models · Video Understanding · 2023-2025*

- Designed adapter-based spatial, temporal, and textual modules for adapting pretrained image-language models to video.
- Reduced trainable parameters by **85%** compared with full fine-tuning.
- Preserved vision-language alignment while adding spatio-temporal reasoning capabilities.
- Improved accident-anticipation accuracy and earliness across real-world dashcam datasets.

### [Cross-Domain Semantic Segmentation](https://github.com/patpatera/domain-adaptation)

*Autonomous Perception · Domain Adaptation · 2021-2022*

- Developed a generator-discriminator domain-adaptation method for autonomous-vehicle perception.
- Achieved the best mIoU across four Cityscapes-to-Cross-City targets, with relative improvements of up to **20%**.
- Packaged the training and evaluation environment with Docker for reproducible deployment.
- Completed the project in collaboration with ITRI.

### [Facial Biometric Descriptors for Multimodal Authentication](https://patents.google.com/patent/US20250184148A1/en)

*Computer Vision · Biometrics · C++ · 2019-2020*

- Co-developed a patented CNN-based biometric verification system.
- Combined facial and voice representations into multimodal identity fingerprints.
- Implemented C++ computer-vision components and a Node.js verification backend.
- Encoded identity hashes as QR codes for document signing and real-time authorization.

Technical Skills
======

- **Programming and software engineering:** Python, PyTorch, C/C++, OpenCV, Linux, Git, CI/CD, Docker, Slurm, FastAPI, Streamlit, Node.js, REST APIs.
- **Computer vision:** Image processing, image recognition, camera-based perception, video understanding, semantic segmentation, domain adaptation, anomaly detection, accident anticipation, hazard localization.
- **Models and architectures:** Vision Transformers, CNNs, CLIP, MobileCLIP, V-JEPA, vision-language models, recurrent attention, linear attention, spatio-temporal modeling, hybrid architectures.
- **Model development:** Parameter-efficient fine-tuning, knowledge distillation, self-supervised learning, contrastive learning, foundation-model adaptation, training pipelines, evaluation pipelines, ablation studies, and model selection.
- **Generative and agentic AI:** RAG, semantic search, LangChain, LangGraph, Hugging Face, ChromaDB, FAISS, Ollama, MCP, Gemma, and Qwen.
- **Deployment and optimization:** ONNX, TensorRT, CUDA, CoreML, FP16, BF16, NVIDIA Jetson, iOS, GPU inference, distributed training, and real-time optimization.

Education
======

### Ph.D. in Electrical and Computer Engineering — [Taiwan Tech (NTUST)](https://www.ece.ntust.edu.tw/)

*Taipei, Taiwan · Sep. 2020 - Feb. 2026 · GPA: 4.3/4.3*

**Research area:** Computer Vision and Deep Learning  
**Dissertation:** *Efficient Spatio-Temporal Deep Learning for Real-Time Video-Based Accident Anticipation on Edge Devices*  
**Advisors:** [Prof. Yie-Tarng Chen](https://www.et.ntust.edu.tw/et/faculty.php?user=ytchen) and [Prof. Wen-Hsien Fang](https://www.et.ntust.edu.tw/et/faculty.php?user=whf)

### M.Sc. in Software Engineering — [University of West Bohemia](https://www.kiv.zcu.cz/en/)

*Czech Republic · Sep. 2017 - Jun. 2020*

**Thesis:** *Information Extraction from Heterogeneous Image-Based Documents Using Templates*  
**Result:** Graduated with honours.

### Master's Exchange Programme — [Taiwan Tech (NTUST)](https://www.csie.ntust.edu.tw/)

*Taipei, Taiwan · Sep. 2018 - Feb. 2019*

**Selected coursework:** Intelligent Video Surveillance Systems, Intelligent Control Systems, and Basic Oral Chinese.

### B.Sc. in Software Engineering — [University of West Bohemia](https://www.kiv.zcu.cz/en/)

*Czech Republic · Sep. 2014 - Jun. 2017*


Teaching
======

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Service, Awards, and Languages
======

### Professional Service

- Reviewer, NeurIPS 2026.

### Awards

- [IT SPY 2020](https://www.itspy.cz/en/thesis/extrakce-udaju-z-heterogennich-dokumentu-pomoci-sablon/) — top-tier ranking among more than 1,400 master's theses submitted across 14 Central European universities.
- M.Sc. Diploma with Honours.
- Taiwan Ministry of Education Scholarship, 2020-2024.
- English as a Medium of Instruction Teaching Certificate.

### Languages

- Czech — native.
- English — fluent.
- Slovak — fluent.
- Mandarin Chinese — basic.
