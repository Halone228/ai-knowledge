[NV-Embed-v2](https://arxiv.org/pdf/2405.17428) is the latest release of the generalist embedding models developed by NVIDIA. It delivers state-of-the-art performance across a wide variety of tasks, which once ranked No. 1 on the [MTEB](https://huggingface.co/spaces/mteb/leaderboard) leaderboard. It achieves an impressive score of 72.31 across 56 different tasks, spanning retrieval, classification, clustering, STS, and more. It’s worth mentioning that the previous version NV-Embed-v1 also earned the top spot on the same leaderboard.

Why choose it:

- **Novel design**: The model uses latent-attention pooling, enabling the LLM to attend to specific latent vectors, resulting in better embedding quality. Additionally, it uses a two-staged instruction tuning approach that makes it versatile across both retrieval and non-retrieval tasks.
- **Retrieval excellence**: NV-Embed-v2 holds the No. 1 rank in the retrieval sub-category, scoring 62.65 across 15 retrieval tasks, which are essential for applications like RAG.
- **Negative mining**: NV-Embed-v2 introduces hard-negative mining techniques to improve the accuracy of embedding tasks by eliminating false negatives more effectively.

Points to be cautious about:

- **Non-commercial license**: NV-Embed-v2 is released under the **CC-BY-NC-4.0** license, which prohibits commercial usage.