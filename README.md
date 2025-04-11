# MoLE-Mixture-of-LoRA-Experts-
NLP project implementation
We present MoLE (Mixture of LoRA Experts), a modular framework for rapidly personalizing large language models (LLMs) through user-uploaded domain data. Instead of fine-tuning the full model, MoLE trains lightweight LoRA (Low-Rank Adaptation) adapters for specific tasks such as summarization, translation, and question answering, using datasets from legal, biomedical, and multilingual domains. These adapters are stored independently and routed dynamically based on the query's semantics. Users can upload task-specific datasets via a simple interface, which triggers adapter training and deploys them within a shared base LLM (e.g., Mistral-7B). We demonstrate that MoLE enables efficient, composable, and accurate domain adaptation—achieving improved task performance while reducing training costs and maintaining model privacy. Our evaluation shows that MoLE outperforms monolithic LoRA approaches in multi-task settings and provides a scalable foundation for customizable and modular LLM systems.
