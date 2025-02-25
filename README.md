# DeepSeek-R1-Distill-Qwen-32B-Medical

![Medical AI](https://img.shields.io/badge/AI-Medical-blue.svg)  
![License](https://img.shields.io/badge/License-MIT-green.svg)  
![Last Updated](https://img.shields.io/badge/Last%20Updated-February%2025,%202025-brightgreen.svg)

## 简介 | Introduction

本项目基于 [200 万条医疗数据](https://huggingface.co/datasets/shibing624/medical)，对 **DeepSeek-R1-Distill-Qwen-32B** 模型进行微调，打造出一款在医学领域具备极高专业性的可本地部署大语言模型。该模型适用于医疗研究、辅助诊断等场景，支持灵活的本地运行和便捷的调用。

This project fine-tunes the **DeepSeek-R1-Distill-Qwen-32B** model using a dataset of [2 million medical records](https://huggingface.co/datasets/shibing624/medical), delivering a highly specialized, locally deployable large language model tailored for the medical domain. It is ideal for medical research, diagnostic assistance, and more, with flexible local deployment and easy integration.

![ui]()
### 获取模型 | Get Started
- **运行笔记本**：通过 IPython Notebook (ipynb) 文件自行运行模型。  
- **直接调用**：访问现成版本 [Hugging Face 模型仓库](https://huggingface.co/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical/tree/main)。  

- **Run it yourself**: Use the provided IPython Notebook (ipynb).  
- **Ready-to-use**: Access the pre-built version on [Hugging Face](https://huggingface.co/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical/tree/main).

## 更新日志 | Updates

| 日期          | 更新内容                                      |
|---------------|---------------------------------------------|
| 2025.2.13     | 更新部署代码，新增简洁 UI 界面                |
| 2025.2.19     | 更新 ipynb 文件，全面优化模型参数             |
| 2025.2.25     | 升级至 DeepSeek-R1-Distill-Qwen-32B，提升专业性，减少 Bug，优化 UI |

- **February 13, 2025**: Updated deployment code with a simple UI interface.  
- **February 19, 2025**: Updated ipynb with comprehensive parameter optimization.  
- **February 25, 2025**: Upgraded to DeepSeek-R1-Distill-Qwen-32B, enhancing professionalism, reducing bugs, and improving UI.

## 目录 | Table of Contents

1. [环境配置](#环境配置--setting-up)  
2. [加载模型与分词器](#加载模型与分词器--loading-the-model-and-tokenizer)  
3. [微调前模型推理](#微调前模型推理--model-inference-before-fine-tuning)  
4. [加载与处理数据集](#加载与处理数据集--loading-and-processing-the-dataset)  
5. [模型设置](#模型设置--setting-up-the-model)  
6. [模型训练](#模型训练--model-training)  
7. [微调后模型推理](#微调后模型推理--model-inference-after-fine-tuning)  
8. [本地保存模型](#本地保存模型--saving-the-model-locally)  
9. [推送至 Hugging Face Hub](#推送至-hugging-face-hub--pushing-the-model-to-hugging-face-hub)  

## 使用方法 | How to Use

### 环境配置 | Setting Up
```bash
run ipynb
