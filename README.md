# Markov-Chain-Text-Generation-BLEU-Evaluation
This project explores text generation using variations of Markov Chains and evaluates text quality using BLEU scores.

# Text Generation with Variations of Markov Chains and Evaluating Text Quality with BLEU Scores

## Objective
This project was developed on the **Databricks platform**, utilizing its capabilities for data processing and analysis.
This project is presented as a **story**, beginning with **text generation** using a simple **Markov Chain** and evaluating its quality. The evaluation is performed by comparing the generated text to a reference text using **BLEU scores**. BLEU is a widely used metric for assessing the quality of machine-generated text by measuring its similarity to a reference text.

## Progression of Methods
After analyzing the initial BLEU scores, improvements are made through variations of the Markov Chain approach. The steps include:

1. **First Markov Chain**: Basic text generation.
2. **First Markov Chain with a Fallback Method**: Introducing fallback mechanisms.
3. **Second Markov Chain**: Enhancing the model with improved n-gram handling.
4. **Second Markov Chain with a Fallback Method**: Refining the fallback logic.
5. **Weighted Random Selection**: Incorporating weighted probabilities with fallbacks to bigrams and unigrams.
6. **Final Version**: Eliminating the fallback to unigrams and instead selecting words directly from the reference text.

## Results
This project serves as a **demonstration** of various text generation and evaluation techniques rather than a showcase of high-quality generated text. The results are naturally limited by the simplicity of the methods and the relatively small dataset used. 

Compared to modern **large language models (LLMs)** like ChatGPT, which are trained on vast datasets and advanced architectures, the generated text in this project is not expected to achieve similar fluency or coherence.

## Data Source
The text data used in this project comprises all available books from the **Anne of Green Gables** series by **Lucy Maud Montgomery**, downloaded from **Project Gutenberg**—an online library of free eBooks.

The books were combined into a single **TXT file**. Since this project is developed on the **Databricks platform**, the file was converted into a **table within the Databricks Catalog**.
