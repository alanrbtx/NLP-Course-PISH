# Курс по NLP

Учебный курс по Natural Language Processing: от подготовки текстовых данных и классических моделей до Large Language Models, их адаптации и применения.

Курс сочетает лекции и семинары с кодом. Основной акцент — на использовании библиотек, работе с pretrained models, оценке качества и построении прикладных NLP-систем.

## Планируемые темы

1. **Основы NLP и векторные представления**
   - Задачи NLP, сбор и разметка данных, text preprocessing.
   - Tokenization, lemmatization, stemming, stop words, n-grams, Bag of Words и TF-IDF.
   - Классическая text classification, evaluation и обзор RNN.
   - Word2Vec, GloVe, fastText, doc2vec, static и contextual embeddings, transfer learning.
   - Семинар: TF-IDF + Logistic Regression и сравнение с pretrained sentence embeddings.

2. **Transformer и pretrained models**
   - Attention, encoder-only, decoder-only и encoder–decoder architectures.
   - BERT, RoBERTa, DeBERTa, multilingual models.
   - BPE, WordPiece и SentencePiece.
   - Hugging Face: Transformers, Datasets, Tokenizers и Hub.
   - Применение моделей к classification, NER, QA и summarization; fine-tuning через Trainer API.

3. **LLM и prompt engineering**
   - Decoder-only models, scaling laws и параметры генерации.
   - In-context learning: zero-shot, one-shot и few-shot.
   - Структура промптов, chain-of-thought и self-consistency.
   - Hallucinations, context window и positional bias.
   - Работа с LLM через API и локально, сравнение моделей и промптов на одной задаче.

4. **Fine-tuning и адаптация LLM**
   - Supervised fine-tuning, instruction datasets и chat templates.
   - PEFT, LoRA и QLoRA; инструменты Hugging Face TRL и PEFT.
   - RLHF и DPO, безопасность и ограничения моделей.
   - LLM-as-a-judge, pairwise evaluation и benchmarks.
   - Семинар: LoRA fine-tuning небольшой модели и оценка результата до и после адаптации.

5. **RAG, агенты и продвинутые применения**
   - Semantic search, embeddings и vector databases.
   - Chunking, retrieval, hybrid search, re-ranking и генерация ответов по документам.
   - Evaluation RAG: relevance и faithfulness.
   - Function calling, tool use, ReAct и agent frameworks.
   - Multimodal LLM, multilingual tasks и cross-lingual transfer.
   - Практика: сборка RAG pipeline и простого агента.

6. **Деплой, оптимизация и хакатон**
   - Quantization, inference servers, vLLM и TGI.
   - Интеграция моделей через API, latency и стоимость.
   - Мониторинг и evaluation в production.
   - Командный проект: RAG-система, чат-бот, адаптированная модель или агент.

## Материалы

| Папка | Блок | Опубликовано |
| --- | --- | --- |
| [week_1](week_1/) | Основы NLP и векторные представления | Две лекции в PDF и ноутбук семинара |

Материалы следующих блоков будут добавляться по мере подготовки.
