# APoLLo: Unified Adapter and Prompt Learning for Vision Language Models, <code style="color: red">EMNLP 2023</code> 

# Abstract:
The choice of input text prompt plays a critical role in the performance of Vision-Language Pretrained (VLP) models such as CLIP. We present APoLLo, a unified multi-modal approach that combines Adapter and Prompt learning for Vision-Language models. Our method is designed to substantially improve the generalization capabilities of VLP models when they are fine-tuned in a few-shot setting. We introduce trainable cross-attention-based adapter layers in conjunction with vision and language encoders to strengthen the alignment between the two modalities. We enforce consistency between the respective encoder branches (receiving augmented inputs) to prevent overfitting in downstream tasks. Our method is evaluated on three representative tasks: generalization to novel classes, cross-dataset evaluation, and unseen domain shifts. In practice, APoLLo achieves a relative gain up to 6.03% over MaPLe (SOTA) on novel classes for 10 diverse image recognition datasets.

# Proposed Approach:
![alt text](https://github.com/schowdhury671/APoLLo/blob/main/figs/apollo-diagram.jpg)


# Main Results:
![alt text](https://github.com/schowdhury671/APoLLo/blob/main/figs/apollo-table.jpg)



# Citation:
If you find this article useful in your research, please consider citing:

```


```



