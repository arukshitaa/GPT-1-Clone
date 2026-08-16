Multi-head attention runs multiple self-attention mechanisms in parallel. Instead of just one, multiple "heads" independently process input tokens to learn different types of relationships (e.g., semantic meaning, grammatical structure, and long-range dependencies). Their outputs are then concatenated and combined into a rich, unified representation.
present LLMs and language models that continue to utilize pure/standard Multi-Head Attention include:
GPT-2: OpenAI's foundational language model relies on standard MHA.
StableLM (Standard versions): Stability AI's base models use standard multi-head attention.
Flan-T5: Google's encoder-decoder model relies natively on multi-head cross-attention and self-attention.
