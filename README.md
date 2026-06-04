# Opening the Black Box — Explanatory Document

**Summary of the Graphic**
This artifact, *Opening the Black Box*, presents explainable AI (XAI) as a single argument moving across five panels. It opens by **defining XAI**. The methods that make a model's decisions understandable to humans — and pairs that definition with six reasons transparency matters: trust, accountability, debugging, bias detection, safety and alignment, and legal compliance. The second panel names **five obstacles** to explanation: the sheer scale of frontier models, *superposition* (single neurons encoding many unrelated concepts), the *faithfulness gap* between a model's stated and actual reasoning, the loss of fidelity that comes from approximating a model's internals, and the regulatory pressure created by the EU AI Act's transparency duties. The third panel **classifies techniques into two families**: post-hoc/behavioral methods that explain a model from the outside (LIME, SHAP, attention maps, counterfactuals) and mechanistic interpretability that decodes it from the inside (sparse autoencoders, feature dictionaries, circuits, probing). The fourth panel splits **validation** into reliability metrics (accuracy, precision/recall, F1, AUC-ROC, calibration, robustness) and explanation-quality metrics (faithfulness, fidelity, sparsity, completeness). The final panel **compares four leading labs**, such as Anthropic (Claude), OpenAI (GPT), Google DeepMind (Gemini/Gemma), and Meta (LLaMA), by their flagship efforts, core techniques, openness, and goals.

🔗 **Live infographic:** [View it here](https://nicoolesy.github.io/xai/index.html)

---

## About Me

I'm a student working through the foundations of machine learning and artificial intelligence, with a growing focus on **AI interpretability, safety, and alignment**. The question is not just *what* models can do, but whether we can understand and trust *how* they do it. I turn every concept into something I can show. Rather than stopping at a working result, I build editorial-style infographics and technical write-ups that force me to organize an idea clearly enough to explain it to someone else.

**My goal** is to move into a role where I can work at the intersection of machine learning and responsible AI, whether that's interpretability research, ML/data work, or technical communication for AI systems. I care about building tools and explanations that make powerful, opaque systems more legible to the people affected by them.

## How Explainability, Validation, and Metrics Build Trust
 
The central thesis runs through the whole piece: a model can be *accurate yet untrustworthy*, and *explainable yet wrong*. Performance metrics answer whether a system works; explanation metrics answer why it works; and trust requires both at once. A fraud detector with 99% accuracy is still unaccountable if no one can explain why it declined a particular customer, and a clean-looking explanation is worthless if it does not faithfully reflect the underlying computation. By placing reliability and explanation side by side in Panel 4, the graphic makes the dependency visible rather than implied. The lab comparison reinforces this by showing that the most advanced organizations are not treating transparency as optional polish. In fact, they are investing in shared technical vocabulary (features and circuits) precisely because accountability, bias mitigation, and safety all depend on it.

## Work Samples & Project Descriptions
 
### Opening the Black Box — A Field Guide to Explainable AI
*Interactive infographic + explanatory document · 2026*
🔗 `https://nicoolesy.github.io/XAI/`
 
**Context.** An exploration of explainable AI (XAI): why transparency matters, what obstructs it, and how leading labs (Anthropic/Claude, OpenAI/GPT, Google DeepMind/Gemini, Meta/LLaMA) are working to make models interpretable.
 
**Challenge.** "Explainability" isn't one thing: it spans simple input-attribution methods and deep mechanistic interpretability. Forcing these into a single flat list would have hidden the most important distinction in the field. A second judgment call was whether *open model weights* should count as an explainability strategy at all.
 
**Solution.** I split the techniques into two parallel tracks, post-hoc/behavioral (LIME, SHAP, attention) vs. mechanistic (sparse autoencoders, circuits), and built a lab-comparison matrix so the reader can scan either by organization or by approach. I argued open weights *do* count, as transparency-by-access, and defended that choice in the write-up.

---

## Skills
 
**Machine Learning & AI Concepts**
- Supervised & unsupervised learning; classifying algorithms by paradigm and use case
- Neural network architecture: layers, neurons, activation functions, learning rate, model capacity
- Word embeddings and vector-space semantics
- Transformers and large language models (training pipeline, RLHF/alignment)
- Explainable AI & mechanistic interpretability (SAEs, feature/circuit analysis, LIME, SHAP)
- Model evaluation & validation: accuracy, precision/recall, F1, AUC-ROC, calibration, robustness

**Tools & Technologies**
- TensorFlow Neural Network Playground · TensorFlow Embedding Projector
- Kaggle (datasets)
- Git & GitHub · GitHub Pages (static hosting & deployment)
- HTML, CSS, and JavaScript (interactive infographics built from scratch)
- Editorial data visualization & information design

**Communication & Research**
- Technical writing and structured reflection
- Research synthesis from primary sources (papers, lab publications, industry reports)
- APA 7th edition citation and academic-integrity disclosure practices

---

## References (APA 7th edition)
 
Anthropic. (2025, March 27). *Tracing the thoughts of a large language model.* https://www.anthropic.com/research/tracing-thoughts-language-model
 
European Parliament & Council of the European Union. (2024). *Regulation (EU) 2024/1689 (Artificial Intelligence Act).* Official Journal of the European Union.
 
Gao, L., la Tour, T. D., Tillman, H., Goh, G., Troll, R., Radford, A., Sutskever, I., Leike, J., & Wu, J. (2024). *Scaling and evaluating sparse autoencoders* (arXiv:2406.04093). arXiv. https://arxiv.org/abs/2406.04093
 
Lieberum, T., Rajamanoharan, S., Conmy, A., Smith, L., Sonnerat, N., Varma, V., Kramár, J., Dragan, A., Shah, R., & Nanda, N. (2024). *Gemma Scope: Open sparse autoencoders everywhere all at once on Gemma 2* (arXiv:2408.05147). arXiv. https://arxiv.org/abs/2408.05147
 
Lundberg, S. M., & Lee, S.-I. (2017). A unified approach to interpreting model predictions. *Advances in Neural Information Processing Systems, 30,* 4765–4774.
 
OpenAI. (2024, June 6). *Extracting concepts from GPT-4.* https://openai.com/index/extracting-concepts-from-gpt-4/
 
Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). "Why should I trust you?": Explaining the predictions of any classifier. *Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining,* 1135–1144.
 
Templeton, A., Conerly, T., Marcus, J., Lindsey, J., Bricken, T., Chen, B., Pearce, A., Citro, C., Ameisen, E., Jones, A., Cunningham, H., Turner, N. L., McDougall, C., MacDiarmid, M., Tamkin, A., Durmus, E., Hume, T., Mosconi, F., Freeman, C. D., … Henighan, T. (2024). *Scaling monosemanticity: Extracting interpretable features from Claude 3 Sonnet.* Transformer Circuits Thread.
 
---
 
*AI-use disclosure: Claude (Anthropic) was used to research current interpretability work, draft the structure and prose of this document and the accompanying infographic, and assist with HTML/CSS. Sources were verified against primary publications, and the classification choices, design decisions, and reflection are my own.*



