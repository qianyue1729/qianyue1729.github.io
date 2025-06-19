---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 本科，信息安全专业，北京邮电大学，2021.09 - 2025.07（预期）
  * 专业成绩：3.31/4.0
  * 英语水平：CET-4 527分，CET-6 465分
  * 核心课程：线性代数(94)，信息隐藏与数字水印(96)，高级智能安全(92)，机器智能与信息对抗(92)

科研经历
======
* 2024.12 - 2025.02: 基于深度学习的机器鱼障碍检测与距离预测
  * 北京大学工学院智能仿生实验室
  * 项目目标：优化机器鱼在复杂水下环境中的障碍感知能力
  * 技术方案：采用Segment Anything Model (SAM2)进行目标识别，引入短时傅里叶变换（STFT）优化特征提取，基于CSLA（Conv1D-LSTM-Attention）构建回归模型
  * 贡献：数据预处理、特征工程及模型优化，设计并实现基于STFT的特征提取方法

* 2023.12 - 2024.06: 基于深度学习的网络层析拥塞状态识别
  * 北京邮电大学可信分布式计算与服务实验室
  * 项目目标：提出一种端到端网络拥塞检测方法，提升多路径网络中的拥塞检测准确率
  * 创新点：设计了一种基于对抗自编码器(AAE)和长短期记忆网络(LSTM)的混合模型
  * 贡献：参与方法设计与实验流程，负责数据收集、分析和可视化，并产出学术论文

项目经历
======
* 2023.06 - 2023.07: 信息安全攻防对抗综合实验
  * 项目目标：搭建渗透测试与防御联调环境，验证多场景下漏洞攻击与防御技术的有效性
  * 主要工作：
    * 混合漏洞场景覆盖：针对WordPress插件、WebLogic、Linux内核等不同层级漏洞，复现SQL注入（CVE-2024-35548）、权限提升（CVE-2024-1086）、XSS攻击（CVE-2023-6933）等漏洞攻击链
    * AI辅助行为分析：基于BERT预训练模型对网络流量进行智能分类
    * 主动防御技术：基于深度强化学习（DQN）动态优化WAF策略，引入生成对抗训练（GAN）框架提升WAF泛化能力

技能
======
* 编程语言
  * Python
  * C/C++
  * Java
* 深度学习框架
  * PyTorch
  * TensorFlow
  * Keras
* 网络安全工具
  * Wireshark
  * Metasploit
  * Burp Suite
  * Nmap
* 其他技能
  * Linux系统管理
  * Git版本控制
  * Docker容器化
  * 数据分析与可视化

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
