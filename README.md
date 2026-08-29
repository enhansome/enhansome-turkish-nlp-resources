# Awesome turkish nlp resources with stars

![](https://user-images.githubusercontent.com/16024979/164789225-7468c77e-8816-406a-9987-44aa8d47ec47.png "Türkçe Natural Language Processing")

<div align="right">
<i><h6> artwork: <a href="https://en.wikipedia.org/wiki/Mihrab_(painting)">Mihrap, Osman Hamdi Bey</a></h6></i>
</div>

<div align="center">
<h2><b>Turkish NLP Resources</b></h2>
Turkish NLP (Türkçe Doğal Dil İşleme) Tools, Libraries, Models, Datasets, and other resources.
<br>
<i>Aligned with new NLP Trends: Generative AI, Retrieval Systems, and Evaluation</i>

<h2>Contents:</h2>
<p> |
<a href="#generative-ai--llms">Generative AI & LLMs</a> |
<a href="#retrieval--semantic-search-rag">Retrieval & RAG</a> |
<a href="#evaluation--benchmarks">Evaluation & Benchmarks</a> |
<a href="#encoder-models">Encoder Models</a> |
<a href="#tools--libraries">Tools & Libraries</a> |
<a href="#datasets">Datasets</a> |
<a href="#community--learning">Community & Learning</a> |
<a href="#misc">Misc</a> |
</p>
</div>
<br>

## Generative AI & LLMs

### Foundation & Chat Models

> *Language models specific to Turkish, ranging from adaptations of open weights (Llama, Mistral) to native pretrained models.*

* [Trendyol LLMs](https://huggingface.co/Trendyol/models) : Bilingual (TR/EN) models ranging from 7B to 70B parameters, including specialized cybersecurity variants.
* [Kumru-2B](https://huggingface.co/vngrs-ai/Kumru-2B) : Decoder-only foundational models trained from scratch for Turkish with a native tokenizer. [blog](https://medium.com/vngrs/kumru-llm-34d1628cfd93)
* [TURNA](https://huggingface.co/boun-tabi-LMG/TURNA) : A 1.1B parameter foundational model for NLU and generation.
* [Cosmos Turkish Llama](https://huggingface.co/ytu-ce-cosmos/Turkish-Llama-8b-DPO-v0.1) : The Cosmos Llama is designed for text generation tasks, trained with DPO for coherent Turkish continuation.
* [Kanarya-2b](https://huggingface.co/asafaya/kanarya-2b) : Turkish GPT-J model trained on large-scale corpora.
* [Turkcell-LLM-7b-v1](https://huggingface.co/TURKCELL/Turkcell-LLM-7b-v1) : Extended version of Mistral fine-tuned on Turkish instruction sets.
* [WiroAI/wiroai-turkish-llm-9b](https://huggingface.co/WiroAI/wiroai-turkish-llm-9b) : Robust language models adapted to Turkish culture and context.
* [Kocdigital-LLM-8b-v0.1](https://huggingface.co/KOCDIGITAL/Kocdigital-LLM-8b-v0.1) : Fine-tuned version of Llama3 8b for Turkish.

### Domain Specific LLMs

> *Models adapted for specific verticals (Legal, Medical, Finance).*

* [Mecellem](https://huggingface.co/collections/newmindai/mecellem-models) : Specialized ModernBERT-based models for the Turkish legal domain. [arxiv](https://arxiv.org/abs/2601.16018)

### LLM Integrations (MCP Servers)

> *Model Context Protocol (MCP) servers enabling AI agents to interact with Turkish data sources.*

* [Yargı MCP](https://github.com/saidsurucu/yargi-mcp) ⭐ 1,107 | 🐛 4 | 🌐 Python | 📅 2026-08-06 : Search for Turkish Legal Databases (Yargıtay, Danıştay).
* [Borsa MCP](https://github.com/saidsurucu/borsa-mcp) ⭐ 643 | 🐛 4 | 🌐 Python | 📅 2026-08-07 : Istanbul Stock Exchange (BIST) and investment fund data.
* [Mevzuat MCP](https://github.com/saidsurucu/mevzuat-mcp) ⭐ 233 | 🐛 2 | 🌐 Python | 📅 2026-06-18 : Search Turkish Legislation (laws, regulations).
* [YÖK Tez MCP](https://github.com/saidsurucu/yoktez-mcp) ⭐ 125 | 🐛 1 | 🌐 Python | 📅 2026-05-20 : Turkish National Thesis Center (YÖK Tez) search.
* [YÖK Atlas MCP](https://github.com/saidsurucu/yokatlas-mcp) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2026-07-23 : YÖK Atlas higher education and ranking data.

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Retrieval & Semantic Search (RAG)

> *Crucial for RAG (Retrieval Augmented Generation) pipelines, moving beyond keyword search.*

### Late-Interaction Models

> *Late-interaction models (ColBERT) are specifically designed for high-performance retrieval tasks.*

* [TurkColBERT](https://huggingface.co/collections/newmindai/turkcolbert-turkish-late-interaction-models) : Benchmark and collection of token-level matching models for high-performance retrieval. [arxiv](https://arxiv.org/abs/2511.16528), [blog](https://huggingface.co/blog/newmindai/late-interaction-models)

### Embedding Models

> *Embedding models for semantic search and retrieval.*

* [TurkEmbed4Retrieval](https://huggingface.co/newmindai/TurkEmbed4Retrieval) : Specialized embedding model for Turkish retrieval tasks.
* [Mursit-Large-TR-Retrieval](https://huggingface.co/newmindai/Mursit-Large-TR-Retrieval) : Late-interaction retrieval model for Turkish.
* [TY-ecomm-embed-multilingual-base-v1.2.0](https://huggingface.co/Trendyol/TY-ecomm-embed-multilingual-base-v1.2.0) : Multilingual e-commerce embeddings.
* [Floret Embeddings](https://huggingface.co/turkish-nlp-suite) : Turkish Floret Embeddings, large and medium sized.
* [VNLP Word Embeddings](https://vnlp.readthedocs.io/en/latest/main_classes/word_embeddings.html) : Word2Vec Turkish word embeddings.
* [TurkishGloVe](https://github.com/inzva/Turkish-GloVe) ⭐ 70 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-04-12 : Turkish GloVe word embeddings.

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Evaluation & Benchmarks

> *Leaderboards and datasets to validate model performance in Turkish.*

* [TrGLUE](https://github.com/turkish-nlp-suite/TrGLUE) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-17 : Turkish-native corpora curated for GLUE-style evaluations.
* [Mezura](https://huggingface.co/spaces/newmindai/Mezura) : Leaderboard focusing on human evaluation (ELO) and RAG performance.
* [Mizan](https://huggingface.co/spaces/newmindai/Mizan) : Embedding model leaderboard for retrieval and clustering tasks.
* [TurkBench](https://huggingface.co/spaces/TurkBench/TurkBench) : Comprehensive generative LLM benchmark with 21 subtasks. [arxiv](https://arxiv.org/abs/2601.07020)
* [Cetvel](https://huggingface.co/spaces/KUIS-AI/Cetvel) : A 26-task benchmark including translation, summarization, and correction.
* [TR-MMLU](https://github.com/NovusResearch/TR-MMLU) : Evaluation framework with 6,200 Turkish-specific multiple-choice questions.

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Encoder Models

> *Traditional Transformer models (BERT, RoBERTa, etc.) and Word Vectors.*

* [ELMO For ManyLangs](https://github.com/HIT-SCIR/ELMoForManyLangs) ⭐ 1,460 | 🐛 53 | 🌐 Python | 📅 2021-05-19 : Pre-trained ELMo Representations.
* [Loodos/Turkish Language Models](https://github.com/Loodos/turkish-language-models) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2021-01-09 : Transformer based Turkish language models.
* [BERTurk](https://huggingface.co/dbmdz/bert-base-turkish-cased) : Turkish BERT/DistilBERT, ELECTRA and ConvBERT models.
* [TurkishBERTweet](https://huggingface.co/VRLLab/TurkishBERTweet) : A BERTweet model fine-tuned on Turkish tweets.
* [Fasttext - Word Vector](https://fasttext.cc/docs/en/crawl-vectors.html) : Pre-trained word vectors for 157 languages.

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Tools & Libraries

> *Core libraries for morphological analysis, tokenization, and processing.*

* [Zemberek-NLP](https://github.com/ahmetaa/zemberek-nlp) ⭐ 1,354 | 🐛 56 | 🌐 Java | 📅 2026-04-28 (Java) : The veteran NLP library for Turkish (Morphology, Spell Check, etc.).
* [VNLP](https://github.com/vngrs-ai/vnlp) ⭐ 290 | 🐛 0 | 🌐 Python | 📅 2025-09-11 (Python) : State-of-the-art, lightweight NLP tools for Turkish.
* [Turkish Stemmer](https://github.com/otuncelli/turkish-stemmer-python/) ⚠️ Archived (Python) : Stemming algorithm.
* [TRmorph](https://github.com/coltekin/TRmorph) ⭐ 197 | 🐛 11 | 🌐 Python | 📅 2023-09-23 (FST) : Finite-state morphological analyzer.
* [Zemberek-Python](https://github.com/Loodos/zemberek-python) ⭐ 140 | 🐛 9 | 🌐 Python | 📅 2025-06-23 (Python) : Python wrapper/implementation of Zemberek.
* [Nuve](https://github.com/hrzafer/nuve) ⭐ 104 | 🐛 28 | 🌐 C# | 📅 2023-02-21 (C#) : Turkish NLP library for morphological analysis.
* [SadedeGel](https://github.com/GlobalMaksimum/sadedegel) ⭐ 94 | 🐛 65 | 🌐 Python | 📅 2023-04-12 (Python) : Extraction-based news summarization.
* [sinKAF](https://github.com/eonurk/sinkaf) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2024-03-12 (Python) : Profanity detection library.
* [Zemberek-Server](https://github.com/cbilgili/zemberek-nlp-server) ⭐ 83 | 🐛 1 | 🌐 Java | 📅 2022-05-20 (Docker) : REST Docker server for Zemberek.
* [snnclsr/NER](https://github.com/snnclsr/ner) ⭐ 39 | 🐛 1 | 🌐 Python | 📅 2020-05-26 (Python) : Named Entity Recognition system.
* [TrTokenizer](https://github.com/apdullahyayik/TrTokenizer) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2023-10-31 (Python) : Sentence and word tokenizers.
* [spaCy Turkish models](https://huggingface.co/turkish-nlp-suite) : Pre-trained Turkish pipelines for spaCy.
* [Starlang Tools](https://github.com/StarlangSoftware) (Python) : Comprehensive suite (Morphology, Spell Check, Dependency Parsing, Deasciifier, NER).
* [ITU Turkish NLP](http://tools.nlp.itu.edu.tr/api_usage.jsp) (Web/API) : Tools from ITU Natural Language Processing Group.
* [Helsinki-NLP Translation](https://huggingface.co/Helsinki-NLP/opus-mt-tc-big-en-tr) : Neural machine translation (EN-TR).

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Datasets

> *Extensive corpora and collections for training and evaluation.*

### Instruction Tuning & Dialogue (LLM)

* [Boğaziçi University TABI - NLI-TR](https://github.com/boun-tabi/NLI-TR) ⭐ 65 | 🐛 0 | 📅 2024-01-25 : Natural Language Inference datasets.
* [InstrucTurca](https://huggingface.co/datasets/turkish-nlp-suite/InstrucTurca) : 2.58M instruction samples (OpenOrca/MedText translations).
* [Turkish-Alpaca](https://huggingface.co/datasets/TFLai/Turkish-Alpaca) : 52k cleaned/verified instruction following samples.
* [WikiRAG-TR](https://huggingface.co/datasets/Metin/WikiRAG-TR) : Questions derived from Turkish Wikipedia for RAG.
* [turkish-math-186k](https://huggingface.co/datasets/ituperceptron/turkish-math-186k) : Large-scale dataset for mathematical reasoning.

### Multimodal & Vision

* [TurkishLLaVA OCR Enhancement](https://huggingface.co/datasets/ytu-ce-cosmos/turkce-kitap) : Specialized books collection for OCR improvement.
* [unsloth-pmc-vqa-tr](https://huggingface.co/datasets/nezahatkorkmaz/unsloth-pmc-vqa-tr) : Turkish PMC-VQA (Medical Visual Question Answering).
* [BosphorusSign22k](https://ogulcanozdemir.github.io/bosphorussign22k/) : Turkish Sign Language Recognition (SLR) benchmark.

### Major Corpora & Collections

* [Cosmos Datasets](https://huggingface.co/ytu-ce-cosmos/datasets) : Extensive datasets from YTU Cosmos Research Group.
* [Trendyol Datasets](https://huggingface.co/Trendyol/datasets) : E-commerce and general datasets from Trendyol.
* [Turkish National Corpus (TNC)](https://www.tnc.org.tr/) : Balanced, large scale (50M words) general-purpose corpus.
* [TS Corpus](https://tscorpus.com/) : Independent project for Turkish corpora and datasets.
* [TDD - Turkish Data Depository](https://data.tdd.ai/) : Foundational datasets.
* [METU Corpora](https://ii.metu.edu.tr/metu-corpora-research-group) : MTC and Discourse Bank.

### Treebanks (Syntax & Morphology)

* [UD Ottoman Turkish](https://github.com/UniversalDependencies/UD_Ottoman_Turkish-BOUN) ⭐ 3 | 🐛 1 | 📅 2026-05-06 : Historical treebank.
* [Universal Dependencies (UD)](https://universaldependencies.org/#turkish-treebanks) : Standardized cross-linguistic treebanks.
* [UD Turkish BOUN](https://universaldependencies.org/treebanks/tr_boun/index.html) : 9.7k sentences, created by TABILAB.
* [UD Turkish Kenet](https://universaldependencies.org/treebanks/tr_kenet/index.html) : 18.7k sentences, based on TDK dictionary.
* [METU-Sabancı Treebank](https://web.itu.edu.tr/gulsenc/treebanks.html) : Syntactic analysis resources.

### Sentiment, General NLP & Others

* [Amazon MASSIVE](https://github.com/alexa/massive) ⭐ 565 | 🐛 4 | 🌐 Python | 📅 2022-11-28 & [OPUS](https://opus.nlpl.eu/) : Multilingual resources.
* **Miscellaneous**: [Song Lyrics](https://www.kaggle.com/datasets/emreokcular/turkish-song-lyrics), [Poems](https://www.kaggle.com/datasets/emreokcular/turkish-poems), [Idioms](https://www.kaggle.com/datasets/emreokcular/turkish-idioms-and-proverbs), [Stop Words](https://github.com/ahmetax/trstop) ⭐ 127 | 🐛 1 | 🌐 Python | 📅 2018-06-29, [Bad Word Blacklist](https://github.com/ooguz/turkce-kufur-karaliste) ⭐ 206 | 🐛 13 | 📅 2021-08-01, [Tatoeba: Multilingual Sentences](https://tatoeba.org/tr/downloads)
* [FSMTSAD](https://github.com/kevserbusrayildirim/FSMTSAD) ⭐ 0 | 🐛 1 | 📅 2025-02-17 : Balanced sentiment dataset (Hotel, Movie, Product).
* [SentiTurca](https://huggingface.co/datasets/turkish-nlp-suite/SentiTurca) : Sentiment analysis benchmark.
* [HisTR](https://huggingface.co/datasets/Saziye/HisTR) : NER dataset for historical Turkish.
* [Turkish NLP Suite Datasets](https://github.com/turkish-nlp-suite) : NER, medical, and sentiment resources.
* [Common Crawl (CC-100)](https://data.statmt.org/cc-100/) & [OSCAR](https://oscar-corpus.com/) : Large/Web-scale corpora.

### Dataset Search

* [Google Dataset Search/Turkish](https://datasetsearch.research.google.com/search?src=0\&query=turkish)
* [Kaggle - Datasets/Turkish](https://www.kaggle.com/search?q=turkish+in:datasets)
* [Hugging Face - Datasets/Turkish](https://huggingface.co/datasets?search=turkish)

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Community & Learning

### YouTube Channels

* [KUIS AI](https://www.youtube.com/@kuisaicenter/videos)
* [Türkiye Yapay Zeka İnisiyatifi](https://www.youtube.com/c/T%C3%BCrkiyeYapayZeka%C4%B0nisiyatifi)
* [Trendyol Tech](https://www.youtube.com/@TrendyolTech/videos)
* [Starlang Yazılım](https://www.youtube.com/@starlangyazilim/videos)
* [NLP with Duygu](https://www.youtube.com/@NLPwithDuygu)

### Awesome Lists

* [Açık Veri Kaynakları](https://github.com/kaymal/acik-veri) ⭐ 114 | 🐛 5 | 📅 2025-01-25 : Open data sources in Turkey.
* [Awesome Turkish Language Models](https://github.com/kesimeg/awesome-turkish-language-models) ⭐ 96 | 🐛 4 | 📅 2026-08-18 : Curated list of models.
* [Awesome Turkish NLP](https://github.com/yusufusta/awesome-turkish-nlp) ⭐ 48 | 🐛 1 | 📅 2020-09-12 : Alternative curated list.

### Educational Resources

* [Turkish Natural Language Processing - Kemal Oflazer](https://www.amazon.com/Turkish-Natural-Language-Processing-Applications/dp/331990163X)

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Misc

* [Kip](https://kip-dili.github.io/) : A programming language in Turkish based on case and mood.

<div align="right">
    <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Contributing

Your contributions are welcome! If you want to contribute to this list, send a *pull request* or just open a *new issue*.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
