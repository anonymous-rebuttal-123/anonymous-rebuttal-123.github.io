# Anonymous rebuttal page for APLDM
We would like to sincerely thank the reviewers for taking time out of their busy schedules to provide valuable and insightful feedback on our work. Their suggestions are greatly appreciated.

On this webpage, we will provide detailed answers to your questions regarding APLDM.

# 1. Displaying Intermediate Generation Results of APLDM
TODO

# 2. How Does PFSA Work?
The role of PFSA is manifested in two aspects:

***(i) adjusting the variance and intensity across different frequency bands***: during the early and middle stages of denoising, PFSA amplifies the high-frequency signal intensity of the latent representation, and increases the variance, while in the later stages of denoising, it reduces the high-frequency signal intensity, and decreases the variance;

***(ii) clustering effect***: It has the ability to cluster tokens into several categories.

## 2.1 PFSA Adjusts the Variance and High-Frequency Signal Intensity of Latent Representations
Let us use the notation from the paper: let $\boldsymbol{z}_t$ represent the latent representation at step $t$, and $\tilde{\boldsymbol{z}}_t = \text{PFSA}(\boldsymbol{z}_t)$


## 2.2 PFSA Clusters Tokens of Latent Representations


