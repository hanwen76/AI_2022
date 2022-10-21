## basic idea
- based on VIT
- self-supervised learning
- generative pre-training
- masked patches
## model 
1. 首先通过 Linear Projection 和位置编码得到 image tokens。
2. 随机 shuffle 这些 tokens，按照 masking ratio 扔掉最后的一部分。
3. 把 unmasked patches 输出到 Encoder 中，得到这些 tokens 的表征。
4. 把 Encoder 的输出，结合 masked tokens (可学习的向量)，执行 unshuffle操作恢复顺序，再一起输入到 Decoder 中。
5. shuffle 和 unshuffle 操作的时间开销可忽略不计。
