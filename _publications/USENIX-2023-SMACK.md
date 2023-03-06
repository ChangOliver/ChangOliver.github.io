---
title: "SMACK: Semantically Meaningful Adversarial Audio Attack"
collection: publications
permalink: /publication/USENIX-2023-SMACK
date: 2023-01-01
venue: 'USENIX Security Symposium'
paperurl: 'https://www.usenix.org/conference/usenixsecurity23/presentation/yuzhiyuan'
citation: 'Z. Yu, Y. Chang, N. Zhang, C. Xiao. SMACK: Semantically Meaningful Adversarial Audio Attack. USENIX Security Symposium, 2023'
---
## Abstract
Voice controllable systems rely on speech recognition and speaker identification as the key enabling technologies. While they bring revolutionary changes to our daily lives, their security has become a growing concern. Existing work has demonstrated the feasibility of using maliciously crafted perturbations to manipulate speech or speaker recognition. Although these attacks vary in targets and techniques, they all require the addition of noise perturbations. While these perturbations are generally restricted to $L_{p}$-bounded neighborhood, the added noises inevitably leave unnatural traces recognizable by humans, and can be used for defense. To address this limitation, we introduce a new class of adversarial audio attack, named **S**emantically **M**eaningful Adversarial **A**udio Atta**CK** (SMACK), where the inherent speech attributes (such as prosody) are modified such that they still semantically represent the same speech and preserves the speech quality. The efficacy of SMACK was evaluated against five transcription systems and two speaker recognition systems in a black-box manner. By manipulating semantic attributes, our adversarial audio examples are capable of evading the state-of-the-art defenses, with better speech naturalness compared to traditional $L_{p}$-bounded attacks in the human perceptual study.