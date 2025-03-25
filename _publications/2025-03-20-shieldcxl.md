---
title: "ShieldCXL: A Practical Obliviousness Support with Sealed CXL Memory"
collection: publications
permalink: /publication/2025-03-20-shieldcxl
date: 2025-03-20
venue: 'TACO'
paperurl: 'http://myshlee417.github.io/files/shieldcxl_taco_2025.pdf'
slideurl: 'http://myshlee417.github.io/files/shieldcxl_slide_taco_2025.pdf'
citation: 'Kwanghoon Choi, Igjae Kim, Sunho Lee, and Jaehyuk Huh, &quot;ShieldCXL: A Practical Obliviousness Support with Sealed CXL Memory&quot;, ACM Transactions on Architecture and Code Optimization (TACO), March 2025'
---
Kwanghoon Choi, Igjae Kim, **Sunho Lee**, and Jaehyuk Huh, &quot;ShieldCXL: A Practical Obliviousness Support with Sealed CXL Memory&quot;, *ACM Transactions on Architecture and Code Optimization (* ***TACO*** *)*, March 2025

[Paper](http://myshlee417.github.io/files/shieldcxl_taco_2025.pdf)
[Slide](http://myshlee417.github.io/files/shieldcxl_slide_taco_2025.pdf)

The CXL (Compute Express Link) technology is an emerging memory interface with high-level commands. Recent studies applied the CXL memory expanding technique to mitigate the capacity limitation of the conventional DDRx memory. Unlike the prior studies to use the CXL memory as the capacity expander, this study proposes to use the CXL-based memory as a secure main memory device, while removing the conventional memory. In the conventional DDRx memory, to provide confidentiality, integrity, replay protection, and obliviousness, costly mechanisms such as counter-based integrity trees and location shuffling by ORAM (Oblivious RAM) are used. Such mechanisms incur significant performance degradation in the current DDR-based memory systems, and their costs increase as the capacity of the memory increases. To mitigate the performance degradation, the prior work proposed an obfuscated channel for a secure memory module enclosing its controller in the package. Based on the approach, we propose a secure CXL-only memory architecture called *ShieldCXL*. It uses the channel encryption and integrity protection mechanism of the CXL interface to provide a practical ORAM while supporting confidentiality, integrity, and replay protection from physical attacks and rowhammers. To protect the PCIe-connected memory expanding board, this study proposes to use the standard physical sealing technique to detect physical intrusion. To mitigate the increased latency with the sealed CXL memory module, the study further optimizes performance by adopting an in-package DRAM cache. In addition, this study investigates destination obfuscation when a CXL switch is used to route among multiple hosts and memory devices. The evaluation shows that *ShieldCXL* provides 9.16x performance improvements over the prior ORAM technique.
