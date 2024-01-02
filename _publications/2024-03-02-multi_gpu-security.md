---
title: "Supporting Secure Multi-GPU Computing with Dynamic and Batched Metadata Management"
collection: publications
permalink: /publication/2024-03-02-multi_gpu_security
date: 2024-03-02
venue: 'HPCA'
paperurl: 'http://myshlee417.github.io/files/multi_gpu_security_hpca_2024.pdf'
# slideurl: 'http://myshlee417.github.io/files/multi_gpu_security_slide_hpca_2024.pdf'
citation: 'Seonjin Na, Jungwoo Kim, Sunho Lee, and Jaehyuk Huh, &quot;Supporting Secure Multi-GPU Computing with Dynamic and Batched Metadata Management&quot;, the 30th IEEE International Symposium on High-Performance Computer Architecture (HPCA), March 2024'
---
Seonjin Na, Jungwoo Kim, **Sunho Lee**, and Jaehyuk Huh, &quot;Supporting Secure Multi-GPU Computing with Dynamic and Batched Metadata Management&quot;, *the 30th IEEE International Symposium on High-Performance Computer Architecture (* ***HPCA*** *)*, March 2024

[Paper](http://myshlee417.github.io/files/multi_gpu_security_hpca_2024.pdf)

With growing problem sizes for GPU computing, multi-GPU systems with fine-grained memory sharing have emerged to improve the current coarse-grained unified memory support based on page migration. Such multi-GPU systems with shared memory pose a new challenge in securing CPU-GPU and inter-GPU communications, as the cost of secure data transfers adds a significant performance overhead. There are two overheads of secure communication in multi-GPU systems: First, extra overhead is added to generate one-time pads (OTPs) for authenticated encryption. Second, the security metadata such as MACs and counters passed along with encrypted data consume precious network bandwidth. This study investigates the performance impact of secure communication in multi-GPU systems and evaluates the prior CPU-oriented OTP precomputation schemes adapted for multi-GPU systems. Our investigation identifies the challenge with the limited OTP buffers for inter-GPU communication and the opportunity to reduce traffic for security meta-data with bursty communications in GPUs. Based on the analysis, this paper proposes a new dynamic OTP buffer allocation technique, which adjusts the buffer assignment for each source-destination pair to reflect the communication patterns. To address the bandwidth problem by extra security metadata, the study employs a dynamic batching scheme to transfer only a single set of metadata for each batched group of data responses. The proposed design constantly tracks the communication pattern from each GPU, periodically adjusts the allocated buffer size, and dynamically forms batches of data transfers. Our evaluation shows that in a 16-GPU system, the proposed scheme can improve the performance by 13.2\% and 17.5\% on average from the prior cached and private schemes, respectively.
