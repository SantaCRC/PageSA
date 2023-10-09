---
layout: page
title: About
permalink: /about/
---

# Geomagnetic Storm Prediction Model

## Introduction

We have developed a prototype model for predicting geomagnetic storms using data from the DSCOVR satellite. It's crucial to understand that this is an initial step, and there's significant optimization and enhancement work ahead.

## Model Features

Our model's primary approach is to transform numerical data into images and apply deep learning techniques to identify patterns and make predictions. 
<img src = "/PageSA/assets/img/dia.svg" alt="My Happy SVG"/>

**Preliminary Results:**
- Even as an unoptimized model, it showed a promising RSME (Root Mean Square Error) of 0.67 on validation data over a year's trend.

## Limitations and Considerations

### 1. **Issues with DSCOVR Data:** 
Due to the age of the DSCOVR satellite, there have been incorrect or missing measurements in the collected data. In future optimizations, an additional AI model could be implemented to identify and potentially correct these anomalies.

### 2. **Kp Values:** 
Some Kp values are indirect measurements that can introduce error into the prediction. It will be essential to develop methods to account for these indirect values or, ideally, integrate additional data.

### 3. **Integration of Multiple Systems:** 
For a more robust and accurate prediction, it would be ideal to combine data from multiple systems and satellites, not just DSCOVR. This integration would allow for a more resilient and reliable model.

## Conclusion

Despite the current limitations, this prototype demonstrates the potential of modern artificial intelligence techniques in predicting geomagnetic storms. The main challenge was the short development time: just 2 days during the hackathon. However, we are optimistic that with more time and resources, we can enhance this prototype and develop a highly accurate and dependable prediction system.

For now, this prototype serves as an exciting and promising starting point for future research and developments in the field.

[CNN model](https://colab.research.google.com/drive/1ow2oKtXP_ybUS_k49eYsizBxIV9xKzEw?usp=sharing)
[ANN model](https://colab.research.google.com/drive/1JQ0O0u_J18TkifCmi2h8PUnuRTVXijl6?usp=sharing)