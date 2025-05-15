# A-Continual-Learning-Solution-for-Plant-Stress-Classification
*🌱 "Optimizing CNN Memory Efficiency: A Continual Learning Solution for Plant Stress Classification"*



## ✨ Highlights
- Applying continual learning techniques such as Elastic Weight Consolidation (EWC) and Learning without Forgetting (LwF) to CNN models, allowing them to continuously acquire new knowledge without losing previously acquired information.
- Dividing the dataset into tasks that simulate real-world scenarios of continuous data flow, enabling the evaluation of the proposed methods under conditions that mirror dynamic agricultural environments.
- Optimizing the EfficientNet-B0 architecture for multi-task classification, ensuring high accuracy across different plant stress detection tasks while mitigating the catastrophic forgetting typically associated with re-training large models for each new task.

# 🔍 Proposed Methodology
![Methodology](https://github.com/user-attachments/assets/05396c0e-2d71-40ed-878e-209ab1eae4a5)

## 📑 Dataset

The dataset used in this paper is a **secondary dataset** published by researchers from the **Islamic University of Technology (IUT)** and the **Bangladesh Agricultural Research Institute (BARI)**, Gazipur. It was made publicly available for the research community and can be accessed through the following link:

[Dataset Link](https://www.frontiersin.org/articles/10.3389/fpls.2023.1251888)

This dataset is crucial for plant stress classification and has been utilized to evaluate different continual learning methods in the context of agricultural data. The dataset includes various plant stress conditions, making it suitable for developing machine learning models that can identify and classify these stresses under real-world agricultural scenarios.


## 📊 Results

### Multiclass Classification Accuracy on Task-1, Task-2, Task-3, and Task-4 using different training methods

| Training Method           | Task       | Task-1 Accuracy | Task-2 Accuracy | Task-3 Accuracy | Task-4 Accuracy |
|---------------------------|------------|-----------------|-----------------|-----------------|-----------------|
| **Training without CL**    | Task-1     | 97%             |                 |                 |                 |
|                           | Task-2     | 60%             | 94%             |                 |                 |
|                           | Task-3     | 47%             | 60%             | 98%             |                 |
|                           | **Task-4** | **42%**         | **55%**         | **57%**         | **97%**         |
| **Training with EWC**      | Task-1     | 97%             |                 |                 |                 |
|                           | Task-2     | 60%             | 93%             |                 |                 |
|                           | Task-3     | 37%             | 60%             | 98.5%           |                 |
|                           | **Task-4** | **60%**         | **65%**         | **66%**         | **98%**         |
| **Training with LwF**      | Task-1     | 98%             |                 |                 |                 |
|                           | Task-2     | 44%             | 72%             |                 |                 |
|                           | Task-3     | 53%             | 43%             | 75%           |                 |
|                           | **Task-4** | **60%**         | **61%**         | **55%**         | **75%**         |

## 👥 Contributors
- Ahmed Shakib Reza, Shakib Sadat Shanto, Farah Ulfat Zaima, Tazkera Sattar, Mysha Maliha Annisa, Muhammad Iqbal Hossain
