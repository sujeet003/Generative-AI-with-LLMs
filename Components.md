Data cleaning: Ensure data is clean and correct.

Chunking: Choice of chunking technique, chunk size (chunk_size) and chunk overlap (overlap).

Embedding models: Choice of the embedding model, incl. dimensionality, and whether to fine-tune it.

Metadata: Whether to use metadata and choice of metadata.

Multi-indexing: Decide whether to use multiple indexes for different data collections.

Indexing algorithms: Choice and tuning of ANN and vector compression algorithms can be tuned but are usually not tuned by practitioners.

And the following strategies in the inferencing stage (retrieval and generation):
Query transformations: Experiment with rephrasing, HyDE, or sub-queries.

Retrieval parameters: Choice of search technique (alpha if you have hybrid search enabled) and the number of retrieved search results.
Advanced retrieval strategies: Whether to use advanced retrieval strategies, such as sentence-window or auto-merging retrieval.

Re-ranking models: Whether to use a re-ranking model, choice of re-ranking model, number of search results to input into the re-ranking model, and whether to fine-tune the re-ranking model.

LLMs: Choice of LLM and whether to fine-tune it.

Prompt engineering: Experiment with different phrasing and few-shot examples.