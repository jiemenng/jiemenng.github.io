---
title: "SePanner: Analyzing Semantics of Controller Variables in Industrial Control Systems based on Network Traffic"
collection: publications
permalink: /publication/ACSAC2023/
excerpt: '> *The 39th Computer Security Applications Conference (ACSAC 2023)**Distinguished Paper Award*<br>***Jie Meng**, Zeyu Yang, Zhenyong Zhang, Yangyang Geng, Ruilong Deng, Peng Cheng, Jiming Chen, Jianying Zhou*.'
<!-- date: 2022-10-01 -->
venue: 'Online'
#paperurl: ''
#citation: ''
---
- [Download paper](https://dl.acm.org/doi/10.1145/3627106.3627179)

Conference:
===
*The 39th Computer Security Applications Conference(ACSAC 2023)*

Authors: 
===
***Jie Meng**, Zeyu Yang, Zhenyong Zhang, Yangyang Geng, Ruilong Deng, Peng Cheng, Jiming Chen, Jianying Zhou*.

Abstract:    
===
Programmable logic controllers (PLCs), the essential components of critical infrastructure, play a crucial role in various industrial manufacturing processes. Recent attack events show that attackers have a strong interest in tampering with the controller variables, such as the device status and internal program logic. A typical attack strategy is that the attackers just send malicious network traffic of industrial control protocols (ICPs) to change the controller variables of PLCs. To defend against this attack, a lot of countermeasures have been proposed to detect anomalies in network traffic based on the semantic analysis.
However, the proprietary nature of ICPs poses a challenge to extracting the required semantics for evaluating the controller variables. In this paper, we propose a novel framework named SePanner to extract the semantics of controller variables from proprietary ICPs based on network traffic. Specifically, SePanner conducts the multi-state comparison to locate the semantic fields directly, then removes the interfering fields by the single-state comparison and filtering criteria. Our experiments demonstrate that SePanner can precisely extract the semantics of controller variables from proprietary ICPs, providing protection for PLCs while remaining compatible with various proprietary binary protocols.
