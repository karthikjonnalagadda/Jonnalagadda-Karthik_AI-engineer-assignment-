# LLM Text Summarization using BART

This project implements an abstractive text summarization system using a pre-trained BART model to summarize user reviews. The goal is to generate concise and meaningful summaries from large collections of real-world review data.

## Project Structure
- notebooks/: Contains the Jupyter Notebook with the full implementation
- data/: Dataset files or dataset references
- README.md: Project documentation
- requirements.txt: Python dependencies
- .gitignore: Files excluded from version control

## Dataset
The dataset consists of user reviews containing mixed sentiment and informal language. Due to size constraints, the dataset is not fully stored in the repository and is referenced externally.

## Model
- Model: facebook/bart-large-cnn
- Type: Abstractive summarization
- Framework: HuggingFace Transformers

## Approach
- Text extraction and preprocessing
- Chunk-based summarization to handle long inputs
- Abstractive summarization using BART
- Selection of top reviews based on content richness

## Evaluation
Summaries were evaluated qualitatively based on coherence, readability, and coverage of key themes. ROUGE metrics were considered as an optional quantitative evaluation.

## Future Work
- Fine-tuning the model on domain-specific data
- Multilingual summarization using mBART or mT5
- Sentiment-aware summarization
- Aspect-based analysis of reviews
