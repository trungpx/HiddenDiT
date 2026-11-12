# HiddenDiT
"A Hidden Semantic Bottleneck in Conditional Embeddings of Diffusion Transformers", the paper has been accepted at ICLR 2026

**Authors: Trung X. Pham, Kang Zhang, Ji Woo Hong, Chang D. Yoo**

# Keywords: 
conditional embeddings, diffusion models, generative AI, transformer-based diffusion, sparse representation learning, efficient learning

# TL;DR: 
Conditional embeddings in diffusion Transformers are highly redundant, with semantics concentrated in a few dimensions, enabling large-scale pruning without harming generation quality.

# Abstract:
Diffusion Transformers have achieved state-of-the-art performance in class-conditional and multimodal generation, yet the structure of their learned conditional embeddings remains poorly understood. In this work, we present the first systematic study of these embeddings and uncover a notable redundancy: class-conditioned embeddings exhibit extreme angular similarity, exceeding 99% on ImageNet-1K, while continuous-condition tasks such as pose-guided image generation and video-to-audio generation reach over 99.9%. We further find that semantic information is concentrated in a small subset of dimensions, with head dimensions carrying the dominant signal and tail dimensions contributing minimally. By pruning low-magnitude dimensions--removing up to two-thirds of the embedding space--we show that generation quality and fidelity remain largely unaffected, and in some cases improve. These results reveal a semantic bottleneck in Transformer-based diffusion models, providing new insights into how semantics are encoded and suggesting opportunities for more efficient conditioning mechanisms.
