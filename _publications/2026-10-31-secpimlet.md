---
title: "SecPIMlet: Confidential Computing for Spatio-temporally Shared Processing-in-Memory"
collection: publications
permalink: /publication/2026-10-31-secpimlet
date: 2026-10-31
venue: 'MICRO'
award: 'Best Paper Nominee'
excerpt_separator: "<!--more-->"
paperurl: 'http://myshlee417.github.io/files/secpimlet_micro_2026.pdf'
slideurl: 'http://myshlee417.github.io/files/secpimlet_slide_micro_2026.pdf'
citation: 'Sunho Lee, Minwoo Noh, Jeongwon Choi, Kwanghoon Choi, Igjae Kim, Chang Hyun Park, and Jaehyuk Huh, &quot;SecPIMlet: Confidential Computing for Spatio-temporally Shared Processing-in-Memory&quot;, the 59th International Symposium on Microarchitecture (MICRO), October 2026'
---
**Sunho Lee**, Minwoo Noh, Jeongwon Choi, Kwanghoon Choi, Igjae Kim, Chang Hyun Park, and Jaehyuk Huh, &quot;SecPIMlet: Confidential Computing for Spatio-temporally Shared Processing-in-Memory&quot;, *the 59th International Symposium on Microarchitecture (* ***MICRO*** *)*, October 2026 <!--more--> <span class="award-note">★ Best Paper Nominee</span>

[Paper](http://myshlee417.github.io/files/secpimlet_micro_2026.pdf)
[Slide](http://myshlee417.github.io/files/secpimlet_slide_micro_2026.pdf)

As memory-intensive applications, particularly language models, continue to grow, processing-in-memory (PIM) has emerged as a promising architecture to alleviate memory bandwidth limitations. We find that PIM systems need to support both spatio and temporal sharing between domains to extract the maximal performance. However, current PIM systems lack the necessary protection to securely support such sharing. To address these issues, we introduce *SecPIMlet*, a trusted multi-domain PIM that enables efficient spatio-temporal sharing. For fast and confidential spatio-temporal sharing, *SecPIMlet* protects both PIM-resident data and execution contexts, while also securing in-transit data between the CPU and PIM. Our evaluation shows that *SecPIMlet* achieves at least 175.4% higher throughput than state-of-the-art approaches that support only spatial or temporal sharing, while providing stronger security protection.
