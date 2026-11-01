<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Tianle (Leo) Huang — AI Researcher & Engineer, MSc AI & Language, Stockholm University" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/tianle-huang-9066883a8/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tianleeleo@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Stockholm,_Sweden-30363D?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Stockholm, Sweden">
</p>

<p align="center">
  I build <b>reliable AI systems</b> across NLP, information retrieval, LLM agents,<br>
  speech, and machine learning — from research experiments to working prototypes.
</p>

<br>

## 🔬 Research & Experience

<table>
<tr>
<td width="34%" valign="top">

**🏭 Industrial Knowledge Systems**<br>
<sub>KTH × AstraZeneca · research collaboration</sub>

</td>
<td valign="top">

Retrieval and knowledge systems for industrial maintenance data.
- Retrieval-augmented generation with dense, structured, and hybrid retrieval
- Information extraction and knowledge graphs (Neo4j / Cypher)
- Evaluation of retrieval and answer quality

</td>
</tr>
<tr>
<td valign="top">

**🧪 Span-NER & Active Learning**<br>
<sub>MaintIE · public data</sub>

</td>
<td valign="top">

How much annotation does nested NER on maintenance text really need? → [`ae-ner-maintenance`](https://github.com/leoohuang/ae-ner-maintenance)
- Span-classification model on a Transformer encoder (PyTorch, Hugging Face)
- Pre-registered encoder pilot: BERT / RoBERTa / ModernBERT
- 10-seed learning curves: random vs. uncertainty vs. uncertainty + diversity, with paired significance tests

</td>
</tr>
<tr>
<td valign="top">

**🎙️ Speech Technology**<br>
<sub>KTH</sub>

</td>
<td valign="top">

Speech continuation under speaker-identity bias.
- Evaluating speech-language model continuations across speaker conditions
- Whisper transcription and an automated evaluation pipeline, incl. LLM-as-a-judge

</td>
</tr>
</table>

<br>

## 🧩 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [ae-ner-maintenance](https://github.com/leoohuang/ae-ner-maintenance)
<sub><i>How much labelled data does nested NER need?</i></sub>

Span-based NER with an active-learning loop, token-budget grid, frozen protocols tagged in Git, and unit tests.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![SLURM](https://img.shields.io/badge/SLURM-30363D?style=flat-square)

</td>
<td width="50%" valign="top">

### [maintenance-mind](https://github.com/leoohuang/maintenance-mind)
<sub><i>Does the agent have enough evidence to answer?</i></sub>

ReAct agent over work orders, manuals, and the web, with a self-reflection step after each tool round. Synthetic demo data.

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Agents](https://img.shields.io/badge/LLM_agents-6E40C9?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [game-review-ir](https://github.com/leoohuang/game-review-ir)
<sub><i>Does a retrieved review discuss the aspect asked for?</i></sub>

Team project: BM25 + LLM aspect classification + aspect-aware reranking. **My part:** the evaluation module — aspect-level nDCG@10, qrels, permutation tests.

![BM25](https://img.shields.io/badge/BM25-30363D?style=flat-square)
![nDCG](https://img.shields.io/badge/IR_evaluation-2da44e?style=flat-square)

</td>
<td width="50%" valign="top">

### [Podsearch](https://github.com/leoohuang/Podsearch)
<sub><i>Find the exact moment a podcast discusses a topic.</i></sub>

Faster-Whisper transcription, BGE-M3 embeddings in ChromaDB, two-stage reranking (ZH / EN), playable audio clips.

![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5B47FB?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [spoiler-detector](https://github.com/leoohuang/spoiler-detector)
<sub><i>Safe, mild, or major spoiler?</i></sub>

LLM-assisted labelling checked on a manual sample, sentence embeddings, four classical classifiers. [**Live demo →**](https://huggingface.co/spaces/leoole/spoiler-detector)

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HF_Space-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

</td>
<td width="50%" valign="top">

### [swedish-vocab-trainer](https://github.com/leoohuang/swedish-vocab-trainer)
<sub><i>Turn messy Swedish notes into practice.</i></sub>

Local-first web app: file parsing, optional AI extraction that marks AI-added content, unit + end-to-end tests.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>📚 More — NLP foundations, implemented from scratch</b></summary>
<br>

| Project | What it covers |
|---|---|
| [postagging](https://github.com/leoohuang/postagging) | HMM vs. BiLSTM POS tagging on UD English-EWT, incl. OOV analysis |
| [statistical-nlp](https://github.com/leoohuang/statistical-nlp) | N-gram LM, HMM tagger, Viterbi, word segmentation |
| [multilingual-text-search](https://github.com/leoohuang/multilingual-text-search) | Cross-lingual word embeddings from parallel text via truncated SVD |
| [essay-score-regression](https://github.com/leoohuang/essay-score-regression) | Linear regression with manual backpropagation vs. scikit-learn |
| [obsidian-knowledge-ingest](https://github.com/leoohuang/obsidian-knowledge-ingest) | Agent skill that turns course material into a linked Obsidian knowledge base |
| [naiss-sbatch](https://github.com/leoohuang/naiss-sbatch) | SLURM job templates and GPU checks for the NAISS Arrhenius cluster |

</details>

<br>

## 🛠️ Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,ts,react,r,bash,linux,docker,git,github&perline=11" alt="Python, PyTorch, scikit-learn, TypeScript, React, R, Bash, Linux, Docker, Git, GitHub">
</p>

| | |
|---|---|
| 🧠 **ML & Deep Learning** | PyTorch · Hugging Face Transformers · scikit-learn · NumPy · pandas · active learning |
| 🔎 **NLP & Retrieval** | nested / span NER · POS tagging · sentence embeddings · BM25 · FAISS · ChromaDB · BGE-M3 · reranking · RAG · LLM agents |
| 🎙️ **Speech** | Whisper / Faster-Whisper ASR · speech-language model evaluation |
| 🕸️ **Knowledge & Data** | information extraction · Neo4j / Cypher · ontologies · data cleaning & splitting |
| 📐 **Research & Evaluation** | SLURM on NAISS HPC (GPU) · pre-registered protocols · learning curves · nDCG / MRR / F1 · Wilcoxon & permutation tests · inter-annotator agreement · LLM-as-a-judge |
| ⚙️ **Engineering** | Python · TypeScript · R · Bash · Git · Linux · Docker · pytest · Vitest · Playwright |

<br>

## 🎯 Research Interests

<p align="center">
  <code>Natural language processing</code>&nbsp;
  <code>Information retrieval & RAG</code>&nbsp;
  <code>LLM agents & evaluation</code><br>
  <code>Speech & language</code>&nbsp;
  <code>Data-efficient learning</code>&nbsp;
  <code>Reliable AI systems</code>
</p>

<br>

<p align="center">
  <sub>Open to research collaborations, research-engineering roles, and PhD opportunities in NLP, IR, and applied ML.</sub>
</p>
