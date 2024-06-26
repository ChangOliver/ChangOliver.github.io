---
title: "XCheck: Integrity Verification for 3D Printed Patient-Specific Devices via Computing Tomography"
collection: publications
permalink: /publication/20230809-USENIX-XCheck
date: 2023-08-09
venue: 'USENIX Security Symposium'
paperurl: 'https://www.usenix.org/conference/usenixsecurity23/presentation/yuzhiyuan-0'
citation: 'Z. Yu, Y. Chang, S. Zhai, N. Deily, T. Ju, XF. Wang, U. Jammalamadaka, N. Zhang. XCheck: Integrity Verification for 3D Printed Patient-Specific Devices via Computing Tomography. USENIX Security Symposium, 2023'
---
## Abstract
3D printing is bringing revolutionary changes to the field of medicine, with applications ranging from hearing aids to regrowing organs. As our society increasingly relies on this technology to save lives, the security of these systems is a growing concern. However, existing defense approaches that leverage side channels may require domain knowledge from computer security to fully understand the impact of the attack.

To bridge the gap, we propose XCheck, which leverages medical imaging to verify the integrity of the printed patient-specific device (PSD). XCheck follows a defense-in-depth approach and directly compares the computed tomography (CT) scan of the printed device to its original design. XCheck utilizes a voxel-based approach to build multiple layers of defense involving both 3D geometric verification and multivariate material analysis. To further enhance usability, XCheck also provides an adjustable visualization scheme that allows practitioners' inspection of the printed object with varying tolerance thresholds to meet the needs of different applications. We evaluated the system with 47 PSDs representing different medical applications to validate the efficacy.