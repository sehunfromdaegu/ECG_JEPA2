# ECG_JEPA2 (under development)

Welcome to the repository for **ECG-JEPA 2.0**, the enhanced version of the original [ECG-JEPA](https://github.com/sehunfromdaegu/ECG_JEPA). This repository showcases advancements in the model, offering better performance and efficiency tailored to 12-lead ECG analysis.

## Key Improvements
1. **Larger Dataset**: ECG-JEPA 2.0 is trained on an expanded dataset, providing better generalizability and robustness.
2. **Optimized Training and Inference**: By leveraging flash attention, the pretraining process is approximately **25–30% faster**, enabling quicker development cycles and lower computational costs.
3. **Enhanced Positional Encoding**: The model now incorporates a new positional encoding scheme specifically designed for ECG datasets, improving the representation of lead and temporal information.

## Ongoing Research
~~We have identified the presence of **attention noise** in ECG-JEPA, a phenomenon similar to what has been observed in large language models (LLMs). To mitigate this issue, we are currently exploring the use of **Differential Transformers** ([arXiv:2410.05258](https://arxiv.org/abs/2410.05258)). If this approach demonstrates improved performance, we plan to adopt Differential Transformers in future updates.~~

**&rarr; Differential transformer backbone collapses, which is a common problem in non-contrastive SSL frameworks.**

Stay tuned for further updates and improvements!
