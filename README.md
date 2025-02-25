# deepseek-r1-medical-fine-tune

简介：
本项目是基于200万条医疗数据  https://huggingface.co/datasets/shibing624/medical  对DeepSeek-R1-Distill-Qwen-32B进行微调，形成一个在医学方面具有极高专业性的可本地部署的大语言模型

可以直接使用ipynb自己运行，也有可以直接调用的版本https://huggingface.co/beita6969/DeepSeek-R1-Distill-Qwen-32B-Medical/tree/main

2025.2.13 更新部署代码，添加了简单的ui界面

2025.2.19 更新ipynb，全面优化参数

2025.2.25 更新模型为DeepSeek-R1-Distill-Qwen-32B更加专业减少bug，加强输出的专业性，优化ui界面
![Uploading image.png…]()



## Table of Contents
1. [Setting up](#setting-up)
2. [Loading the model and tokenizer](#loading-the-model-and-tokenizer)
3. [Model inference before fine-tuning](#model-inference-before-fine-tuning)
4. [Loading and processing the dataset](#loading-and-processing-the-dataset)
5. [Setting up the model](#setting-up-the-model)
6. [Model training](#model-training)
7. [Model inference after fine-tuning](#model-inference-after-fine-tuning)
8. [Saving the model locally](#saving-the-model-locally)
9. [Pushing the model to Hugging Face Hub](#pushing-the-model-to-hugging-face-hub)



