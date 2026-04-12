---

**🇬🇧 ENGLISH:**

---

### Ümit Duman

From backend developer to AI researcher. Building analytical alternatives to backpropagation.

**Original Contributions:**

**BackLoss** — Single-formula weight computation without gradient calculation. 22x faster than backprop in classification, 99.77% on MNIST (world #7).

**PropLoss** — Multi-layer gradient-free learning system. Outperforms backprop by 50.9 percentage points at 6 layers. PyPI: `pip install proploss`

**LazySmart Optimizer** — Combines Shampoo-lite + Lookahead + P3. Beats AdamW by 14.4%. Trains Shakespeare language models on CPU in 120 seconds.

**Backloss Gradient Scaling** — Analytical gradient correction for transformer linear layers. Derived from linear regression closed-form solution: `grad_new = grad / (n × |x|)`

**ChunkBLAS Linear Attention** — BLAS-friendly alternative to softmax attention. 42% faster on CPU at ctx=512 with O(n) complexity.

**Research Areas:** Transformer optimization, gradient-free learning, CPU-first AI training, small language models (SLM)

📦 [proploss-classifier](https://github.com/umiteknoloji/proploss-classifier) · [backloss-for-classifier](https://github.com/umiteknoloji/backloss-for-classifier) · [GPT_at_CPU](https://github.com/umiteknoloji/GPT_at_CPU)

---

**🇹🇷 TÜRKÇE:**

---

### Ümit Duman

Backend developer'dan AI araştırmacısına. Backpropagation'a alternatif analitik yöntemler geliştiriyorum.

**Özgün Katkılar:**

**BackLoss** — Gradient hesaplamadan, tek satır formülle ağırlık hesaplayan analitik yöntem. Sınıflandırmada backprop'tan 22x hızlı, MNIST'te %99.77 doğruluk (dünya #7).

**PropLoss** — Çok katmanlı gradient-free öğrenme sistemi. 6 katmanda backprop'u %50.9 puan geçiyor. PyPI: `pip install proploss`

**LazySmart Optimizer** — Shampoo-lite + Lookahead + P3 birleşimi. AdamW'yi %14.4 yendi. CPU'da 120 saniyede Shakespeare dil modeli eğitiyor.

**Backloss Gradient Scaling** — Transformer'ın lineer katmanlarında analitik gradyan düzeltmesi. Doğrusal regresyon kapalı-form çözümünden türetilmiş: `grad_new = grad / (n × |x|)`

**ChunkBLAS Linear Attention** — Softmax attention'a BLAS-dostu alternatif. CPU'da ctx=512'de %42 daha hızlı, O(n) karmaşıklık.

**Araştırma Alanları:** Transformer optimizasyonu, gradient-free öğrenme, CPU-first AI eğitimi, küçük dil modelleri (SLM)

📦 [proploss-classifier](https://github.com/umiteknoloji/proploss-classifier) · [backloss-for-classifier](https://github.com/umiteknoloji/backloss-for-classifier) · [GPT_at_CPU](https://github.com/umiteknoloji/GPT_at_CPU)


