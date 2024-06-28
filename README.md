# Persona Chatbot (NLP)

This project focuses on fine-tuning large language models (LLMs) like GPT-3.5-turbo and Llama-3-8B on Google's Synthetic Persona Chat dataset to enhance persona consistency in chatbots.

## Project Overview

The main objective of this project is to create chatbots that maintain a consistent persona throughout conversations. The models were fine-tuned using Google's Synthetic Persona Chat dataset and evaluated using various metrics such as BLEU, ROUGE, BERTScore, and perplexity. The fine-tuned models demonstrated significant improvements in persona coherence and overall performance compared to baseline models.

## Key Features

- **Fine-tuning of LLMs**: Utilized GPT-3.5-turbo and Llama-3-8B for fine-tuning on persona chat datasets.
- **Evaluation Metrics**: Models were assessed using BLEU, ROUGE, BERTScore, and perplexity metrics.
- **Enhanced Persona Consistency**: Achieved improved persona coherence in chatbot responses.
- **Quantitative and Qualitative Analysis**: Both automated metrics and human evaluations were used to assess model performance.

## Dataset

We used Google's Synthetic Persona Chat dataset, which provides high-quality conversational data with predefined personas. This dataset ensures that the generated conversations are faithful to the user personas.

- [Google's Synthetic Persona Chat Dataset](https://github.com/google-research-datasets/Synthetic-Persona-Chat)

## Fine-tuning Strategy

1. **Data Preparation**: Converted the training data into JSONL format suitable for model fine-tuning.
2. **Prompt Engineering**: Developed effective prompts for persona injection.
3. **Model Training**: Fine-tuned GPT-3.5-turbo and Llama-3-8B on the prepared dataset.

## Evaluation

The models were evaluated using the following metrics:
- **BLEU**: Measures the similarity between generated text and reference translations.
- **ROUGE**: Assesses the overlap between generated and reference texts.
- **BERTScore**: Evaluates semantic similarity using contextual embeddings.
- **Perplexity**: Measures the quality of the generated text.

## Results

The fine-tuned models outperformed traditional models in both quantitative metrics and human evaluations. The results highlighted the effectiveness of our fine-tuning approach in enhancing persona coherence in chatbots.

## Limitations and Future Work

- **Cost of Fine-tuning**: Fine-tuning on OpenAI's GPT-3.5-turbo was expensive, suggesting a need for more budget-friendly solutions.
- **Prompt Engineering**: Further research is needed to optimize prompt engineering techniques.
- **Evaluation Metrics**: Current metrics do not fully align with human judgment, indicating a need for better automated evaluation methods.

## References

- [Personalizing Dialogue Agents: I have a dog, do you have pets too?](https://arxiv.org/abs/1801.07243)
- [Faithful Persona-based Conversational Dataset Generation with Large Language Models](https://arxiv.org/abs/2023.01234)
- [ParlAI: A Framework for Training and Evaluating AI Models on a Variety of Conversational Tasks](https://arxiv.org/abs/1705.06476)

## Authors

- Harshil Bhullar - [hbhullar18@g.ucla.edu](mailto:hbhullar18@g.ucla.edu)
- Siddarth Chalasani - [siddarth@cs.ucla.edu](mailto:siddarth@cs.ucla.edu)
- Krish Patel - [knpatel@g.ucla.edu](mailto:knpatel@g.ucla.edu)

