---
title: "AdapSan: Adaptive Input Sanitization in Medical Systems with eBPF"
collection: publications
permalink: /publication/20241014-AACD-AdapSan
date: 2024-10-14
venue: 'ACM Workshop on Adaptive and Autonomous Cyber Defense (AACD)'
paperurl: 'https://dl.acm.org/doi/10.1145/3689935.3690397'
citation: 'S. Chang, A. Li, E. Jaff, Y. Chang, J. Wang, N. Zhang, H. Hsiao. AdapSan: Adaptive Input Sanitization in Medical Systems with eBPF. ACM Workshop on Adaptive and Autonomous Cyber Defense (AACD), 2024'
---
## Abstract
The current state of medical systems is challenged by the widespread use of legacy systems, which often lack the advanced security features necessary to combat modern cyber threats. However, our investigation reveals that hospital systems are often reluctant to upgrade their systems. This reluctance is primarily due to the following factors: the low tolerance to both service downtime and patch errors, the diversity of platforms, and the resource constraints of embedded medical devices.

Motivated by these challenges, we propose AdapSan, a dynamic sandboxing framework that allows users to deploy different levels of sandboxing schemes according to the risk profiles of the target system. AdapSan utilizes eBPF as the key technique to enable dynamic reconfiguration of defense strategies, thereby avoiding downtime. Additionally, it uses eBPF's verification mechanisms to sandbox patch code, minimizing the impact of potentially buggy patches. Furthermore, the platform-agnostic nature of eBPF bytecode and its Just-In-Time (JIT) compilation facilitate the deployment of this solution across various platforms while maintaining the execution speed of native code. AdapSan incorporates two types of sandboxing schemes, each offering a balance between usability and code complexity, making them suitable for different kinds of patch code. Preliminary evaluations of AdapSan indicate that the patching time can be less than 19 milliseconds and the average runtime overhead post-patching can be maintained below 36%.
