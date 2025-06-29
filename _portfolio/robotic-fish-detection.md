---
title: "基于深度学习的机器鱼障碍检测与距离预测"
excerpt: "采用SAM2模型和STFT特征提取技术，结合CSLA回归模型，实现机器鱼在复杂水下环境中的精确障碍感知与距离预测。"
collection: portfolio
---

## 项目概述

本项目旨在优化机器鱼在复杂水下环境中的障碍感知能力，从最初的二分类感知问题发展为精确的距离预测回归分析。

## 技术方案

### 目标识别
* **Segment Anything Model (SAM2)**: 用于提升障碍物检测精度
* 实现了从二分类问题到回归分析问题的转化

### 特征提取
* **短时傅里叶变换 (STFT)**: 优化特征提取过程
* 捕捉传感器数据的时频特性
* 提升特征表达能力

### 回归模型
* **CSLA架构**: Conv1D-LSTM-Attention组合模型
* 预测机器鱼与障碍物的精确距离
* 结合卷积、循环和注意力机制

## 主要贡献

* **数据预处理**: 设计完整的数据清洗和预处理流程
* **特征工程**: 基于STFT的创新特征提取方法
* **模型优化**: 通过实验验证优化网络结构
* **性能验证**: 全面的实验评估和性能分析

## 项目时间
2024.12 - 2025.02

## 合作单位
北京大学工学院智能仿生实验室

## 技术栈
- Python
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- STFT信号处理