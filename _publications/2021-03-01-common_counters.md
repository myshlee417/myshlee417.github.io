---
title: "Common Counters: Compressed Encryption Counters for Secure GPU Memory"
collection: publications
permalink: /publication/2021-03-01-common_counters
date: 2021-03-01
venue: 'HPCA'
paperurl: 'http://myshlee417.github.io/files/common_counters_hpca_2021.pdf'
slideurl: 'http://myshlee417.github.io/files/common_counters_slide_hpca_2021.pdf'
citation: 'Seonjin Na, Sunho Lee, Yeonjae Kim, Jongse Park, and Jaehyuk Huh, &quot;Common Counters: Compressed Encryption Counters for Secure GPU Memory&quot;, the 27th IEEE International Symposium on High-Performance Computer Architecture (HPCA), March 2021'
---
Seonjin Na, **Sunho Lee**, Yeonjae Kim, Jongse Park, and Jaehyuk Huh, &quot;Common Counters: Compressed Encryption Counters for Secure GPU Memory&quot;, *the 27th IEEE International Symposium on High-Performance Computer Architecture (* ***HPCA*** *)*, March 2021

[Paper](http://myshlee417.github.io/files/common_counters_hpca_2021.pdf) [Slide](http://myshlee417.github.io/files/common_counters_slide_hpca_2021.pdf)

Hardware-based trusted execution has opened a promising new opportunity for enabling secure cloud computing. Nevertheless, the current trusted execution environments are limited to the traditional CPU-based computation, while more and more critical workloads such as machine learning require to use GPUs. For secure GPU computing, recent studies proposed to isolate critical GPU operations from the operating system by providing trusted execution environments for GPUs. However, a missing component in the prior GPU trusted execution studies is a hardware-based memory protection technique optimized for GPUs. Start-of-art memory protection techniques for CPUs use counter-mode encryption, where per-block counters are used as timestamps for generating one-time pads. The integrity of counters is protected by a counter tree. This study investigates the hardware memory encryption for GPUs and identifies counter cache misses as one of the key performance bottlenecks. To mitigate the overheads of counter cache misses, this paper proposes a novel technique, called common counters, for efficient counter-mode encryption and counter integrity protection. The proposed technique exploits unique characteristics of common GPU applications. In GPU applications, a large portion of application memory is written only once by the initial data transfer from the CPU memory, or the number of writes by the GPU applications to major data structures tends to be uniform. Exploiting the uniform write property, this study proposes to use a common counter representation to complement the existing per-block encryption counters. With the common counters, the proposed technique can almost eliminate the performance overheads caused by counter cache misses, reducing the degradation to 2.9%.
