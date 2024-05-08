---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}
## [![pdf-image](https://myshlee417.github.io/files/pdf_icon.png){: width="25em" height="25em"}Download](http://myshlee417.github.io/files/CV_Sunho_Lee.pdf)


Research Interests
======
**I am interested in a secure and efficient architecture of hardware accelerators (such as GPU and NPU).**

My research objective is to design high-performance accelerators with security guarantees.
To achieve this goal, my recent studies focus on 1) *hardware security* and 2) *performance improvement* of hardware accelerators.

***Hardware Security of Accelerators*** **:**
As accelerators are widely used in mission-critical tasks, the importance of security gets larger.
Although I extended Trusted Execution Environment to GPU and NPU in previous works, countless security weaknesses still remain.
Therefore, I aim to increase the security level to resist unintended operations.

***Performance Improvement of Accelerators*** **:**
Since machine learning requires speedy processing, the performance improvement of accelerators is crucial.
Hence, I consider both hardware and software to enhance parallelism or cut down unnecessary procedures.
In a recent publication, I proposed the fine-grained scheduling algorithm in GPU by leveraging Multi-Process Service.
I set the further reduction of the execution time as a future research direction.

From these two sub-goals, I target combining a trusted system with a high-performance accelerator design.
It is expected to protect users from accidents (caused by attackers or extreme environments) within a reasonable latency.

Education
======
**KAIST**, Daejeon, Republic of Korea, *Mar 2021 - present*  
&nbsp;&nbsp;Ph.D. Student, School of Computing  
&nbsp;&nbsp;Advisor: Jaehyuk Huh

**KAIST**, Daejeon, Republic of Korea, *Mar 2019 - Feb 2021*  
&nbsp;&nbsp;Master of Science, School of Computing  
&nbsp;&nbsp;Advisor: Jaehyuk Huh  
&nbsp;&nbsp;Thesis: Hardware Security Techniques for Trusted Machine Learning Accelerators

**Yonsei University**, Seoul, Republic of Korea, *Mar 2015 - Feb 2019*  
&nbsp;&nbsp;Bachelor of Science, Computer Science

Publications
======
* Seonjin Na, Jungwoo Kim, **Sunho Lee**, and Jaehyuk Huh, &quot;Supporting Secure Multi-GPU Computing with Dynamic and Batched Metadata Management&quot;, *the 30th IEEE International Symposium on High-Performance Computer Architecture (* ***HPCA*** *)*, March 2024
* Jungwoo Kim, Seonjin Na, Sanghyeon Lee, **Sunho Lee**, and Jaehyuk Huh, &quot;Improving Data Reuse in NPU On-chip Memory with Interleaved Gradient Order for DNN Training&quot;, *the 56th IEEE/ACM International Symposium on Microarchitecture (* ***MICRO*** *)*, October 2023
* \*Soojin Hwang, \***Sunho Lee**, Jungwoo Kim, Hongbeen Kim, Jaehyuk Huh, &quot;mNPUsim: Evaluating the Effect of Sharing Resources with Multi-Core NPUs&quot;, *the 2023 IEEE International Symposium on Workload Characterization (* ***IISWC*** *)*, October 2023 (\* co-first authors)
* Seungho Lee, **Sunho Lee**, Jaehyuk Huh, and Sejin Kwon, &quot;Proposal of Aerospace-informatics by Design of Ramjet Inlet Using Machine Learning&quot;, *the 2023 Aerospace Europe Conference (* ***AEC*** *) joint event between the 10th European Conference for Aerospace Sciences (* ***EUCASS*** *) and the 9th Council of European Aerospace Societies (* ***CEAS*** *)*, July 2023
* **Sunho Lee**, Seonjin Na, Jungwoo Kim, Jongse Park, and Jaehyuk Huh, &quot;Tunable Memory Protection for Secure Neural Processing Units&quot;, *the 40th IEEE International Conference on Computer Design (* ***ICCD*** *)*, October 2022
* Seungbeom Choi, **Sunho Lee**, Yeonjae Kim, Jongse Park, Youngjin Kwon, and Jaehyuk Huh, &quot;Serving Heterogeneous Machine Learning Models on Multi-GPU Servers with Spatio-Temporal Sharing&quot;, *the 2022 USENIX Annual Technical Conference (* ***USENIX ATC*** *)*, July 2022
* **Sunho Lee**, Jungwoo Kim, Seonjin Na, Jongse Park, and Jaehyuk Huh, &quot;TNPU: Supporting Trusted Execution with Tree-less Integrity Protection for Neural Processing Unit&quot;, *the 28th IEEE International Symposium on High-Performance Computer Architecture (* ***HPCA*** *)*, Feburary 2022
* Seonjin Na, **Sunho Lee**, Yeonjae Kim, Jongse Park, and Jaehyuk Huh, &quot;Common Counters: Compressed Encryption Counters for Secure GPU Memory&quot;, *the 27th IEEE International Symposium on High-Performance Computer Architecture (* ***HPCA*** *)*, Feburary 2021

Patents
======
* **[Pending]** Jaehyuk Huh, Jungwoo Kim, Seonjin Na, Sanghyeon Lee, and **Sunho Lee**, &quot;Improving the Utilization of NPU On-chip Memory with Computation Rearrangement for DNN Training&quot;, *Korean Patent*
* **[Pending]** Jaehyuk Huh, Seonjin Na, Jungwoo Kim, and **Sunho Lee**, &quot;Dynamic One-time Pad Table Management for Secure Multi-GPU Communication&quot;, *Korean Patent*
* **[Pending]** Jaehyuk Huh, **Sunho Lee**, and Seonjin Na, &quot;Apparatus and Method for Providing Secure Execution Environment for NPU&quot;, *US Patent* (with Samsung Electronics)
* **[Pending]** Jaehyuk Huh, Seungbeom Choi, **Sunho Lee**, Yeonjae Kim, Youngjin Kwon, Jongse Park, &quot;Machine Learning Inference Time-spatial SW Scheduler Based on Multiple GPU&quot;, *Korean Patent*
* **[Pending]** Jaehyuk Huh, **Sunho Lee**, and Seonjin Na, &quot;Hardware-based Security Architecture for Trusted Neural Processing Unit&quot;, *Korean Patent* (with Samsung Electronics)
* **[10-2365263-0000]** Jaehyuk Huh, Seonjin Na, **Sunho Lee**, Yeonjae Kim, and Jongse Park, &quot;Efficient Encryption Method and Apparatus for Hardware-based Secure GPU Memory&quot;, *Korean Patent*

Research Experiences
======
**KAIST**, Daejeon, Republic of Korea, *Mar 2019 - present*  
*Ongoing Researches at CASYS (Computer Architecture and SYStem) Lab*  
Advisor: Jaehyuk Huh  
&nbsp;&nbsp;**Accelerator Hardware-based Security**  
&nbsp;&nbsp;&nbsp;&nbsp;- Memory protection optimization for GPU: Common counters for duplicate counters (Published in **HPCA 2021**)  
&nbsp;&nbsp;&nbsp;&nbsp;- Memory protection optimization for multi-GPU system (Published in **HPCA 2024**)  
&nbsp;&nbsp;&nbsp;&nbsp;- Trusted execution environment for NPU: Tensor-granularity counters (Published in **HPCA 2022**)  
&nbsp;&nbsp;&nbsp;&nbsp;- Memory protection optimization for NPU: Parital memory protection (Published in **ICCD 2022**)  
&nbsp;&nbsp;&nbsp;&nbsp;- Side-channel attack protection for NPU  
&nbsp;&nbsp;&nbsp;&nbsp;- Dynamic secure-granularity management for heterogeneous processors  
&nbsp;&nbsp;**Accelerator Performance**  
&nbsp;&nbsp;&nbsp;&nbsp;- Multi-tenancy support for a multi-GPU system: Time and spatial sharing (Published in **USENIX ATC 2022**)  
&nbsp;&nbsp;&nbsp;&nbsp;- Accurate multi-NPU simulation: Multi-NPU simulator attached with DRAMsim3 (Published in **IISWC 2023**)  
&nbsp;&nbsp;&nbsp;&nbsp;- On-chip memory management for training NPU: Access order rearrangement (Published in **MICRO 2023**)

**Yonsei University**, Seoul, Republic of Korea, *Sep 2017 - June 2018*  
*Undergraduate Research Intern at ELC (Embedded systems Languages and Compilers) Lab*  
Advisor: Bernd Burgstaller  
&nbsp;&nbsp;**Parallelism**  
&nbsp;&nbsp;&nbsp;&nbsp;- Accelerating big-data streaming engine: Multi-thread and shared-memory  
&nbsp;&nbsp;&nbsp;&nbsp;- Parallelization of SFA (Simultaneous Deterministic Finite Automata) construction: MPI and Huang's algorithm

Recognition
======
**KAIST**, Daejeon, Republic of Korea  
&nbsp;&nbsp;Outstanding Teaching Assistant Award - CS311 Computer Organization, *Spring 2022, Fall 2019*  
&nbsp;&nbsp;Outstanding Teaching Assistant Award - CS230 System Programming, *Fall 2023*

**Yonsei University**, Seoul, Republic of Korea  
&nbsp;&nbsp;Dean's List, *Spring 2018, Spring 2015*  
&nbsp;&nbsp;Undergraduate Capstone Project Award (Third Place) - Project Leader, *Spring 2018*  
&nbsp;&nbsp;&nbsp;&nbsp;Title: *Cloud SFA: Parallel Construction of Simultaneous Deterministic Finite Automata in Distributed System*

**Samsung Electronics**, Hwaseong, Republic of Korea  
&nbsp;&nbsp;Best Paper Award (Third Place), *Summer 2022*  
&nbsp;&nbsp;&nbsp;&nbsp;Title: *TNPU: Supporting Trusted Execution with Tree-less Integrity Protection for Neural Processing Unit*

Participation
======
**uArch** (in conjunction with **ISCA 2022**), New York City, United States of America  
*Student Panel*  
&nbsp;&nbsp;Life in Grad School, *June 2022*  

Skills
======
**Programming Languages:** C, C++, Python  
**NPU Simulators:** *mNPUsim*, SCALE-Sim, MAESTRO, Gemmini  
**GPU Programming:** CUDA, MPS  
**Multi-core CPU Programming:** MPI, OpenMP  
**Machine Learning Frameworks:** Pytorch, Tensorflow  

Teaching Experiences
======
**KAIST**, Daejeon, Republic of Korea  
*Teaching Assistant*  
&nbsp;&nbsp;CS230 System Programming, *Fall 2023, Fall 2021*  
&nbsp;&nbsp;CS311 Computer Organization, *Fall 2022, Spring 2022, Spring 2021, Fall 2019*  
&nbsp;&nbsp;CS211 Digital System and Lab, *Spring 2019*

**KAIST Education Center**, Daejeon, Republic of Korea  
*Mentor &#38; Lecturer*  
&nbsp;&nbsp;Seocho AI College, *Summer 2019, Summer 2021*  
&nbsp;&nbsp;Python for Beginners, *Summer 2022, Summer 2021*
