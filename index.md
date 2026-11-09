---
layout: default
title: Quarter 2 Project Brainstorm
---

# Quarter 2 Project Brainstorm

**Name:** Jaden Vo  
**Email:** j9vo@ucsd.edu  
**Section:** D-32 — Steering Diffusion Models  
**Mentor:** Professor Yusu Wang

### 1. What is the most interesting topic covered in your domain this quarter?

The most interesting topic covered so far has been learning how to steer diffusion models toward specific outputs. In particular, I find it interesting how PCA and Recursive Feature Machines (RFM) can be used to identify patterns in the data and use them to guide the generation process.

My understanding is that PCA can identify important directions in the model's representations, especially at high noise levels, which can then be used to influence what the model generates. RFM provides another way to learn useful features and potentially capture more complex patterns in the data. I think it is interesting how these methods can give us more control over what diffusion models generate rather than simply relying on the original conditioning of the model.

### 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.

One potential investigation I would like to pursue is using diffusion models to generate synthetic data for testing real-world systems.

More specifically, I am interested in whether steering techniques can help generate realistic anomalies based on patterns in existing datasets. These synthetic examples could represent unusual situations that a system might encounter but that are not well represented in its original training data.

For example, this could be useful for testing anomaly detection systems and seeing how well they identify unexpected patterns. It could also help test how well systems handle data that they have not seen before. Although this idea is still fairly broad, I think it would be interesting to explore how diffusion models could be used to generate more controlled and realistic synthetic data.

### 3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?

Since our Quarter 1 Project was largely determined by our professor, I would be interested in moving away from image generation and exploring other applications of diffusion models.

I am not particularly interested in image generation, and I would like to see how diffusion models can be applied to other types of data, such as time series or tabular data. One reason for this is that evaluating generated images can sometimes be subjective, especially when judging their quality or similarity to a target image. I would rather work on something where we can evaluate the results using more objective measurements, such as accuracy or other quantitative metrics.

### 4. What other techniques would you be interested in using in your project?

I am not entirely sure what additional techniques I would want to use yet, since the methods we are currently exploring are still relatively new to me. I would first like to better understand PCA and NA-RFM steering before trying to introduce something new.

If I had to choose, I would be interested in exploring autoencoders as an alternative to PCA. While PCA mainly captures linear patterns in data, autoencoders can learn more complex, nonlinear patterns. Although they would likely require more computation, they might be able to capture more information about the data and potentially improve the steering process. I think comparing the two approaches could be interesting.