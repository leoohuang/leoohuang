# Tianle (Leo) Huang

**AI Researcher & Engineer** · MSc in AI & Language, Stockholm University (expected 2027)

Building reliable, knowledge-centric AI systems at the intersection of NLP, information retrieval, knowledge representation, and machine learning.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tianle-huang-9066883a8/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tianleeleo@gmail.com)
![Location](https://img.shields.io/badge/Stockholm,_Sweden-2B3137?style=flat-square&logo=googlemaps&logoColor=white)

---

## 🔬 Research & Experience

### Industrial Knowledge Systems · KTH × AstraZeneca research collaboration
Contributing to an industrial research collaboration on reliable knowledge and retrieval systems for maintenance data.
- Knowledge graph construction and information extraction from maintenance records
- Graph modelling and querying with **Neo4j / Cypher**; ontology design with **SHACL** validation
- Retrieval-augmented generation with dense, structured, and hybrid retrieval
- Evaluation of knowledge quality and retrieval behaviour

<sub>Code, data, and results from this collaboration are confidential and not published here.</sub>

### Span-Based NER & Active Learning · MaintIE (public data)
Annotation-efficient nested NER for short maintenance texts — [`ae-ner-maintenance`](https://github.com/leoohuang/ae-ner-maintenance)
- **Done:** span-classification model on a Transformer encoder (PyTorch, Hugging Face); pre-registered encoder pilot (BERT / RoBERTa / ModernBERT); 10-seed learning curves comparing random, uncertainty, and uncertainty + diversity sampling, with paired significance tests
- **In progress:** replication of the comparison on NAISS GPU hardware (SLURM)
- Protocols, splits, and configs are frozen and tagged in Git before each experiment

### Speech Technology Research · KTH
Speech continuation under speaker-identity bias.
- Evaluating speech-language model continuations across speaker conditions
- Whisper transcription and an automated evaluation pipeline, including LLM-as-a-judge scoring

---

## 🧩 Featured Projects

**[ae-ner-maintenance](https://github.com/leoohuang/ae-ner-maintenance)** — *How much annotation does nested NER on maintenance text really need?*
Span-based NER with an active-learning loop, token-budget grid, pre-registered protocols, and unit tests for sampling, budgeting, and statistics.
`PyTorch` `Transformers` `active learning` `SLURM`

**[maintenance-mind](https://github.com/leoohuang/maintenance-mind)** — *Agent that checks whether its retrieved evidence is sufficient before answering.*
ReAct agent over work orders, equipment manuals, and the web, with a separate self-reflection step after each tool round. Synthetic demo data only.
`LLM agents` `function calling` `FAISS` `sentence-transformers` `Streamlit`

**[game-review-ir](https://github.com/leoohuang/game-review-ir)** — *Does a retrieved review actually discuss the aspect a query asks about?*
Team project: BM25 retrieval, LLM aspect classification, and aspect-aware reranking of Steam reviews. **My part:** the evaluation module — aspect-level nDCG@10, qrels construction, and paired permutation tests.
`BM25` `IR evaluation` `LLM classification` `Cohen's κ`

**[Podsearch](https://github.com/leoohuang/Podsearch)** — *Find the exact moment in a podcast where a topic is discussed.*
Ingests podcast feeds, transcribes with Faster-Whisper, indexes timestamped chunks with BGE-M3 in ChromaDB, and reranks results (Chinese / English) with playable audio clips.
`ASR` `BGE-M3` `ChromaDB` `reranking` `Streamlit`

**[spoiler-detector](https://github.com/leoohuang/spoiler-detector)** — *Three-level spoiler severity classification for movie reviews.*
IMDb + GPT-generated data, LLM-assisted labelling checked against a manual sample, sentence embeddings with four classical classifiers. [Live demo](https://huggingface.co/spaces/leoole/spoiler-detector) on Hugging Face.
`sentence-transformers` `scikit-learn` `Gradio` `Hugging Face`

**[swedish-vocab-trainer](https://github.com/leoohuang/swedish-vocab-trainer)** — *Turn messy Swedish notes into reviewable vocabulary practice.*
Local-first web app with file parsing, optional AI-assisted extraction that marks AI-added content, and unit + end-to-end tests.
`TypeScript` `React` `Vitest` `Playwright` `Docker`

<details>
<summary><b>More: NLP foundations, implemented from scratch</b></summary>
<br />

| Project | What it covers |
|---|---|
| [postagging](https://github.com/leoohuang/postagging) | HMM vs. BiLSTM POS tagging on UD English-EWT, incl. OOV analysis |
| [statistical-nlp](https://github.com/leoohuang/statistical-nlp) | N-gram LM, HMM tagger, Viterbi, word segmentation |
| [multilingual-text-search](https://github.com/leoohuang/multilingual-text-search) | Cross-lingual word embeddings from parallel text via truncated SVD |
| [essay-score-regression](https://github.com/leoohuang/essay-score-regression) | Linear regression with manual backpropagation vs. scikit-learn |
| [obsidian-knowledge-ingest](https://github.com/leoohuang/obsidian-knowledge-ingest) | Agent skill that turns course material into a linked Obsidian knowledge base |
| [naiss-sbatch](https://github.com/leoohuang/naiss-sbatch) | SLURM job templates and GPU checks for the NAISS Arrhenius cluster |

</details>

---

## 🛠️ Technical Skills

| Area | Tools & methods |
|---|---|
| **Languages & Engineering** | Python, TypeScript, R, Bash · Git/GitHub, Linux, Docker · pytest, Vitest, Playwright |
| **Machine Learning & Deep Learning** | PyTorch, Hugging Face Transformers, scikit-learn, NumPy, pandas · active learning, uncertainty sampling |
| **NLP & Information Retrieval** | span-based / nested NER, POS tagging, sentence embeddings, BM25, dense retrieval (FAISS, ChromaDB, BGE-M3), reranking, RAG, LLM agents |
| **Knowledge Graphs & Structured Knowledge** | Neo4j, Cypher, ontology design, SHACL validation, information extraction |
| **Speech** | Whisper / Faster-Whisper ASR, speech-language model evaluation |
| **Research Infrastructure & Evaluation** | SLURM on NAISS HPC (GPU), pre-registered experiment protocols, learning curves, nDCG / MRR / F1, Wilcoxon & permutation tests, inter-annotator agreement, LLM-as-a-judge |

---

## 🎯 Research Interests

Reliable AI systems · Knowledge-centric AI · Information retrieval & RAG · Knowledge representation · Data-efficient NLP · Agent reliability

---

## 📄 Publications & Research Outputs

- **Published / accepted / under review:** none yet.
- **Ongoing research:** annotation-efficient span NER with active learning (MaintIE); industrial knowledge systems (KTH × AstraZeneca); speech continuation under speaker-identity bias (KTH).

---

<sub>Open to research collaborations, research-engineering roles, and PhD opportunities in NLP, IR, and knowledge-centric AI.</sub>
