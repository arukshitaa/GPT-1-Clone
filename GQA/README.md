Grouped Query Attention (GQA) is a transformer attention mechanism that reduces KV (Key-Value) cache memory. Instead of every query head having its own dedicated key and value (Multi-Head Attention) or all heads sharing a single key and value (Multi-Query Attention), GQA groups query heads together. All queries in a group share just one Key and Value.
Prominent LLMs that use GQA include:
Llama 3 (Meta)
Llama 2 (Meta)
Mistral 7B (Mistral AI)
Gemma (Google)
Qwen series (Alibaba)
