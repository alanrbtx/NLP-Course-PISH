# Week 1. Основы NLP и векторные представления

Материалы лекций к занятию 24 октября. В папке опубликованы две презентации в PDF.

## Лекция 1. Введение в NLP

[Открыть презентацию](<Введение в NLP — 24 октября.pdf>)

Охваченные темы:

- **Задачи NLP:** text classification, sentiment analysis, information extraction, sequence labeling, information retrieval, text generation, summarization и machine translation.
- **Развитие методов:** rule-based, statistical и neural NLP, переход к LLM.
- **Данные:** corpus, data collection, annotation guidelines, train/dev/test, group split и time-based split.
- **Text preprocessing:** tokenization, normalization, lemmatization, stemming, morphological analysis, stop words и обработка русского текста.
- **Текстовые признаки:** corpus statistics, Zipf’s law, word и character n-grams, Bag of Words, term–document matrix, sparse representations и TF-IDF.
- **Классификация:** generative и discriminative models, Naive Bayes, smoothing, Logistic Regression, decision threshold и scikit-learn Pipeline.
- **Evaluation:** cross-validation, model selection, data leakage, confusion matrix, precision, recall, class imbalance и macro-F1.
- **Последовательностные модели:** RNN, bidirectional RNN, long-range dependencies, LSTM и GRU; переход к attention и Transformer.
- **Библиотеки:** NLTK, spaCy, scikit-learn, Gensim, Hugging Face и Sentence Transformers.

## Лекция 2. Векторные представления текста

[Открыть презентацию](<Векторные представления текста — 24 октября.pdf>)

Охваченные темы:

- **Основы representations:** sparse и dense vectors, one-hot encoding, embedding lookup, distributional hypothesis, context window и word–context matrix.
- **Embedding space:** cosine similarity, nearest neighbors, similarity и relatedness, word analogies, multilingual spaces и ограничения representations.
- **Static word embeddings:** Word2Vec, Skip-gram, CBOW, negative sampling, GloVe, fastText, subword information и OOV.
- **Sentence и document representations:** averaging, weighted pooling, TF-IDF как baseline, Latent Semantic Analysis, doc2vec, PV-DM и PV-DBOW.
- **Evaluation representations:** intrinsic и extrinsic evaluation, влияние corpus и semantic change.
- **Contextual embeddings:** polysemy, ELMo, BERT, Masked Language Modeling, hidden states и pooling.
- **Transfer learning:** pretraining, feature extraction, fine-tuning, backbone, task head и domain adaptation.
- **Sentence embeddings:** Sentence-BERT, Siamese architecture, обучающие пары и выбор pretrained model.
- **Semantic search:** bi-encoder retrieval, symmetric и asymmetric search, chunking, vector index, ANN, lexical/dense/hybrid retrieval, cross-encoder и re-ranking.
- **Введение в RAG:** роль embeddings, retrieval evaluation и grounded generation.

Практическое применение preprocessing, TF-IDF + Logistic Regression и pretrained sentence embeddings относится к семинару.
