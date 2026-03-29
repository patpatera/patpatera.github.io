---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Ph.D. in Computer Vision & Deep Learning</b> - <a href="https://www.ece.ntust.edu.tw/">Taiwan Tech (NTUST), ECE Department </a></span> <span style="flex: 0 0 auto"><i>Oct. 2020 - Feb. 2026</i></span></p> 
    <p><i>Reaseach Topic:</i> Efficient Spatio-Temporal Deep Learning for Real-Time Video-Based Accident Anticipation and Understanding on Edge Devices</p>
    <p><i>Advisors:</i> <a href="https://www.et.ntust.edu.tw/et/faculty.php?user=ytchen">prof. Yie-Tarng Chen</a> and <a href="https://www.et.ntust.edu.tw/et/faculty.php?user=whf">Wen-Hsien Fang</a> </p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>M.Sc. in Software Engineering</b> - <a href="https://www.kiv.zcu.cz/en/">University of West Bohemia (UWB), CSE Department</a></span> <span style="flex: 0 0 auto"><i>Sept. 2017 - Jun. 2020</i></span></p> 
  <p><i>Thesis:</i> Information Extraction from Heterogeneous Image-based Documents using Templates</p>
  <p><i>Advisor:</i> <a href="https://www.zcu.cz/en/Employees/person.html?personId=18388">asst. prof. Kamil Ekštein, M.Sc., Ph.D.</a></p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Master’s Exchange Programme</b> - <a href="https://www.csie.ntust.edu.tw/">Taiwan Tech (NTUST), CSIE Department </a></span> <span style="flex: 0 0 auto"><i>Sept. 2018 - Feb. 2019</i></span></p>
  <p><i>Courses:</i> Intelligent Video Surveillance Systems, Intelligent Control System, Basic Oral Chinese</p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>B.Sc. in Software Engineering</b> - <a href="https://www.kiv.zcu.cz/en/">University of West Bohemia (UWB), CSE Department</a></span> <span style="flex: 0 0 auto"><i>Sept. 2014 - Jun. 2017</i></span></p> 

Work Experience
======
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Research Assistant</b> - <a href="https://www.ece.ntust.edu.tw/">Taiwan Tech (NTUST)</a></span> <span style="flex: 0 0 auto"><i>Oct. 2020 - Jan. 2026</i></span></p>
  <p><i>Reaseach Areas:</i>  Multi-modal (text-visual) models, spatio-temporal modelling, image-to-video adaptation, parameter-efficient training, domain adaptation, real-time deployment (NVIDIA Jetson Nano), and self-supervised learning.</p>
  <p><i>Technologies:</i> PyTorch, Python, C/C++, CUDA, TensorRT, VLM, ViTs, LLMs, GNNs.</p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Teaching Assistant</b> - <a href="https://www.ece.ntust.edu.tw/">Taiwan Tech (NTUST)</a></span> <span style="flex: 0 0 auto"><i>Feb. 2021 - Jan. 2026</i></span></p>
  <p><i>Courses:</i> Intelligent Video Surveillance Systems, Database, Large Language Models and Applications.</p>
  <p><i>Mentoring:</i> Master’s student at our lab (research and code review).</p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Junior Researcher</b> - <a href="https://www.ntis.zcu.cz/en/index.html">NTIS Research Centre</a></span> <span style="flex: 0 0 auto"><i>Sept. 2019 - Sept. 2020</i></span></p>
  <p><i>Patented Innovation:</i> Co-invented a multi-modal biometric approach (US Patent 2025/0184148) for person identification based on short audio-visual recordings.</p>
  <p><i>Full-Stack Architecture:</i> Integrated a C++ backend (OpenCV/DLib with CNNs) and a Node.js server to bridge AI-generated hashes as a simple QR code to a web UI for real-time person authorization.</p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Research & Software Engineer</b> -- <a href="https://www.palaxo.com/">Palaxo International Ltd.</a></span> <span style="flex: 0 0 auto"><i>Sept. 2017 - Sept. 2020</i></span></p>
  <p>Researched and developed an image analysis system for paperless documents to allow text recognition and automatically anonymize sensitive data (using Tesseract-OCR / OpenCV / DLib / C++).</p>
* <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><b>Software Engineer</b> - <a href="https://en.wikipedia.org/wiki/Kerio_Technologies">Kerio Technologies, Inc.</a></span> <span style="flex: 0 0 auto"><i>Jun. 2016 - Jun. 2017</i></span></p>
  <p>Implementing manageable router with security (firewall) and optimization using own kernel in C/C++.</p>
  
Skills
======
* <b>Technical skills: </b>PyTorch, C/C++, CUDA, Python, TensorRT, ONNX, NVidia Jetson, Vision Transformers, VLM, Large Language Models, Graph Neural Networks, Linux, OpenCV, Git, LaTeX.
* <b>Soft skills: </b>Problem solving, time management, critical thinking, independence, communication, responsibility.
* <b>Development skills: </b>Software design and architectures, agile development, team working, leadership.
* <b>Communication skills: </b>Czech (native), English (fluent), Slovakia (fluent), Traditional Chinese (basic).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Honors & Awards
======
1. <a href="https://www.itspy.cz/en/thesis/extrakce-udaju-z-heterogennich-dokumentu-pomoci-sablon/">IT SPY 2020</a> -- Recognized as one of the best Master's theses in Central Europe submitted in 2020.
2. M.Sc. Diploma with Honors.
3. Recipient of the Taiwan Ministry of Education Scholarship (2020–2024).
4. EMI (English as a Medium of Instruction) Teaching Certificate.
  
