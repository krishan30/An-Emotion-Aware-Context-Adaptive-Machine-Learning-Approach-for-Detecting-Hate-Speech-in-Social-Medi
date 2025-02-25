# AiLERT-FYP
# An Emotion Aware Context Adaptive Machine Learning Approach for Detecting Hate Speech in Social Media

## Overview

"Unmasking Hate: An Integrated Approach to Detecting Hate Speech in Social Media" aims to develop a comprehensive method for identifying hate speech on social media platforms. Hate speech is a serious problem that can have harmful effects on individuals and society. By developing a system that can accurately identify instances of hate speech, we hope to promote a safer and more inclusive online environment.

## Objectives

- **Enhance Hate Speech Detection Performance**: Improve hate speech detection using the DCL framework by using fine-tuned embeddings for context-aware accuracy.
- **Incorporate Emotion Modeling**: Integrate emotional context recognition into DCL framework to further improve the hate speech detection accuracy.
- **Incorporate Author Profiling**: Implement author profiling to better understand user interactions and context using personality detection and user features to further improve the DCL framework.
- **Implement a Scalable Technology Platform**: Transform AI algorithm into a practical, cloud-deployable technology platform for widespread use in combating hate speech online.Deployed in [Huggingface spaces]([url](https://huggingface.co/spaces/Thushalya/AiLERT)) 


## Methodology

Our approach combines natural language processing techniques and machine learning algorithms to create a robust hate speech detection system. The methodology is divided into several key steps:

### 1. Data Collection and Preprocessing

- **Dataset**: Collect a dataset(hateval, davidson, unified) of social media posts manually labeled as hate speech or non-hate speech.
- **Preprocessing**: Remove noise and irrelevant information from the data.

### 2. Dual Contrastive Learning (DCL) Framework

Enhance the existing DCL framework for hate speech detection through the following steps:

- **Utilize self-supervised and supervised contrastive learning losses**: Capture span-level information for detecting Hate speech using pre-trained BERT embeddings, data augmentation, and dual contrastive learning mechanisms.
- **Enhance DCL with fine-tuned models**: Incorporate models like Bertweet, TimeLMs, and Roberta to improve the DCL architecture's ability to understand the context of hate speech within specific datasets.
- **Emotion Modeling** : Incorporate the scores of eleven different emotions to create an Emotion vector, which improves the classifier component.

- **Author Profiling** : Developing author profiling involves employing personality detection and user features to enhance the DCL framework, aiming to better grasp user interactions and context.

### Overall Framework

![overall1](https://github.com/user-attachments/assets/138d5598-9b76-4cd3-9c54-9f61c131be04)

- **Combine components**: The final framework combines the enhanced DCL model, emotion modeling, and author profiling to create a robust system for hate speech detection.
  
![overall2](https://github.com/user-attachments/assets/ae1662c0-d707-42d4-a495-bd1112b471c5)

The datasets that were used in our experiments are here.[All_Datasets](https://huggingface.co/krishan-CSE)

you can watch full video using this [link](https://youtu.be/A6JjaFI_6QQ)
