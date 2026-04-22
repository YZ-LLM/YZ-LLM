From backend developer to AI researcher. Building analytical alternatives to backpropagation.

## Original Contributions

**🧮 BackLoss** — Single-formula weight computation without gradient calculation. 22x faster than backprop in classification, 99.77% on MNIST (world #7).

**🔗 PropLoss** — Multi-layer gradient-free learning system. Outperforms backprop by 50.9 percentage points at 6 layers.
`pip install proploss`

**⚡ LazySmart Optimizer** — Combines Shampoo-lite + Lookahead + P3. Beats AdamW by 14.4%. Trains Shakespeare language models on CPU in 120 seconds.

**📐 Backloss Gradient Scaling** — Analytical gradient correction for transformer linear layers. Derived from linear regression closed-form solution: `grad_new = grad / (n × |x|)`

**🚀 ChunkBLAS Linear Attention** — BLAS-friendly alternative to softmax attention. 42% faster on CPU at ctx=512 with O(n) complexity.

## Research Areas

Transformer optimization · Gradient-free learning · CPU-first AI training · Small language models (SLM)

## Repositories
 

*"Intelligence is sometimes simplicity. My formula proves it."*
