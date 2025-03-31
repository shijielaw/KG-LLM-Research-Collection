# 📚 KG-LLM Research Collection

A curated repository for cutting-edge research on **Knowledge Graphs (KGs)** (or **Graphs**) and **Large Language Models (LLMs)** synergy. This collection systematically organizes fundamental advances and practical implementations across two key paradigms:

🔹 **KG-enhanced LLM** (structured knowledge grounding)

🔹 **LLM-powered KG** (dynamic knowledge acquisition and refinement)

</br>

<details>
    <summary><b> 🥳 Good News </b></summary>

- **`2025/01`**  Our demo paper **MMKG-RAG: Retrieval-Augmented Generation with Multi-Modal Knowledge Graph** has been accepted by **DASFAA 2025**. [[📄]()] [[🛠️](https://github.com/wenzhaoabc/mmkg-rag)]

</details>

</br>

# 🔍 Table of Contents

- [**📑 Survey, Evaluation, and Dataset**](#survey-evaluation-and-dataset)

- [**📑 Reasoning**](#reasoning)

- [**📑 Graph RAG**](#graph-rag)

- [**📑 KG Completion**](#kg-completion)

- [**📑 Question Answering**](#question-answering)

- [**📑 Representation Learning**](#representation-learning)

  

</br>

📌 **Note:** Keywords may help to find the target **paper** (📄) and **repository** (🛠️).

</br>



<details open>
    <summary><b>👈 Survey, Evaluation, and Dataset </b></summary>
[**[ Jump to ToC ]**](#🔍-table-of-contents)

# Survey, Evaluation, and Dataset

### 2025

- `[arXiv-2025/03]` **Large Language Model Enhanced Knowledge Representation Learning: A Survey.** [[📄](https://arxiv.org/abs/2407.00936v4)]

  **🕵️Keywords:** KGs · LLMs · Knowledge Representation Learning · Survey

- `[arXiv-2025/03]` **In-depth Analysis of Graph-based RAG in a Unified Framework.** [[📄](https://arxiv.org/pdf/2503.04338v1)] [[🛠️](https://github.com/JayLZhou/GraphRAG)]

  **🕵️Keywords:** Graph-based RAG · LLMs · Evaluation

- `[arXiv-2025/01]` **Graph2text or Graph2token: A Perspective of Large Language Models for Graph Learning.** [[📄](https://arxiv.org/abs/2501.01124v1)]

  **🕵️Keywords:** LLMs · Graph Data · Graph2Text · Graph2Token · Survey

- `[arXiv-2025/01]` **Retrieval-Augmented Generation with Graphs (GraphRAG).** [[📄](https://arxiv.org/abs/2501.00309v2)] [[🛠️](https://github.com/Graph-RAG/GraphRAG/)]

  **🕵️Keywords:**  Graph RAG · KGs · LLMs · Survey

- `[arXiv-2025/01]` **A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models.** [[📄](https://arxiv.org/abs/2501.13958v1)] [[🛠️](https://github.com/DEEP-PolyU/Awesome-GraphRAG)]

  **🕵️Keywords:** Graph RAG · Customized LLMs · Survey

### 2024

- `[Neurocomputing-2024/08]` **A Review of Graph Neural Networks and Pretrained Language Models for Knowledge Graph Reasoning.** [[📄](https://doi.org/10.1016/j.neucom.2024.128490)]

  **🕵️Keywords:** KG Reasoning · GNNs · PLMs · Logic Rules

- `[Word Wide Web-2024/08]` **LLMs for Knowledge Graph Construction and Reasoning: Recent Capabilities and Future Opportunities.** [[📄](https://doi.org/10.1007/s11280-024-01297-w)] [[🛠️](https://github.com/zjunlp/AutoKG)]

  **🕵️Keywords:** KG Construction and Reasoning · Information Extraction · LLMs

- `[ICIC'24-2024/08]` **Large Models and Multimodal: A Survey of Cutting-Edge Approaches to Knowledge Graph Completion.** [[📄](https://link.springer.com/chapter/10.1007/978-981-97-5672-8_14)]

  **🕵️Keywords:** Multi-Modal · KG Completion · LLMs · Representation Learning

- `[arXiv-2024/07]` **Combining Knowledge Graphs and Large Language Models.** [[📄](https://arxiv.org/pdf/2407.06564v1)]

  **🕵️Keywords:** LLMs Empowered by KGs ·KGs Empowered by LLMs · Hybrid Approaches

- `[TKDE-2024/07]` **Unifying Large Language Models and Knowledge Graphs: A Roadmap.**  [[📄](https://doi.org/10.1109/TKDE.2024.3352100)] 

  **🕵️Keywords:** KG-Enhanced LLMs · LLM-Augmented KGs · Synergized LLMs + KGs

- `[arXiv-2024/06]` **MoreHopQA: More Than Multi-hop Reasoning.** [[📄](https://arxiv.org/abs/2406.13397v1)] [[🛠️](https://github.com/Alab-NII/morehopqa)]

  **🕵️Keywords:** Multi-Hop QA · LLMs · Datasets

- `[TPAMI-2024/06]` **A Survey of Knowledge Graph Reasoning on Graph Types: Static, Dynamic, and Multi-Modal.** [[📄](https://doi.org/10.1109/TPAMI.2024.3417451)] [[🛠️](https://github.com/LIANGKE23/Awesome-Knowledge-Graph-Reasoning)]

  **🕵️Keywords:** KG Reasoning · KGs · Temporal KGs · Multi-Modal KGs

- `[arXiv-2024/01]` **A Survey of Reasoning with Foundation Models.** [[📄](https://arxiv.org/abs/2312.11562v5)]

  **🕵️Keywords:** Reasoning · Multimodal · Foundation Models · No KGs

- `[VLDB'24 Workshop: LLM+KG]` **Research Trends for the Interplay between Large Language Models and Knowledge Graphs.** [[📄](https://vldb.org/workshops/2024/proceedings/LLM+KG/LLM+KG-9.pdf)]

  **🕵️Keywords:** Interplay between LLMs and KGs · KG Tasks · LLM Tasks

- `[arXiv-2024/03]` **Retrieval-Augmented Generation for Large Language Models: A Survey.** [[📄](https://arxiv.org/abs/2312.10997v5)] [[🛠️](https://github.com/Tongji-KGLLM/RAG-Survey)]

  **🕵️Keywords:** RAG · LLMs · KGs · Information Retrieval

- `[ACM Computing Surveys-2024/03]` **Knowledge Graph Embedding: A Survey from the Perspective of Representation Spaces.** [[📄](https://dl.acm.org/doi/10.1145/3643806)]

  **🕵️Keywords:** KG embedding · Representation Spaces

- `[IEEE Intelligent Systems-2024/02]` **Integrating Graphs With Large Language Models: Methods and Prospects.** [[📄](https://doi.org/10.1109/MIS.2023.3332242)]

  **🕵️Keywords:** LLMs Enhance Graph Learning · Graphs Enhance LLM Ability

### 2023

- `[ACM Computing Surveys-2023/11]` **A Comprehensive Survey on Automatic Knowledge Graph Construction.** [[📄](https://dl.acm.org/doi/10.1145/3618295)]

  **🕵️Keywords:** Automatic KG Construction · KG Completion

- `[arXiv-2023/08]` **Large Language Models and Knowledge Graphs: Opportunities and Challenges.** [[📄](https://arxiv.org/abs/2308.06374v1)]

  **🕵️Keywords:** LLMs · PLMs · KGs · Retrieval Augmented LMs


### 2022 and Before

- `[EMNLP'21-2021/11]` **Is Multi-Hop Reasoning Really Explainable? Towards Benchmarking Reasoning Interpretability.** [[📄](https://aclanthology.org/2021.emnlp-main.700/)]  [[🛠️](https://github.com/THU-KEG/BIMR)]

  **🕵️Keywords:** KGs · Multi-hop Reasoning · Link Prediction · Benchmark Dataset

- `[arXiv-2021/07]` **A Survey of Knowledge Graph Embedding and Their Applications.** [[📄](https://arxiv.org/abs/2107.07842v1)]

  **🕵️Keywords:** KG Embedding · Structure-Based · Text-Based · Image-Based

- `[TNNLS-2021/04]` **A Survey on Knowledge Graphs: Representation, Acquisition, and Applications.** [[📄](https://doi.org/10.1109/TNNLS.2021.3070843)]

  **🕵️Keywords:** KG Reasoning · Relation Extraction · Representation Learning

- `[TKDD-2021/01]` **Knowledge Graph Embedding for Link Prediction: A Comparative Analysis.** [[📄](https://dl.acm.org/doi/10.1145/3424672)] [[🛠️](https://github.com/merialdo/research.lpca)]

  **🕵️Keywords:** KG Embedding · KG Reasoning · Link Prediction

- `[ACL-IJCNLP'21]` **Are Missing Links Predictable? An Inferential Benchmark for Knowledge Graph Completion.** [[📄](https://aclanthology.org/2021.acl-long.534/)] [[🛠️](https://github.com/TaoMiner/inferwiki)]

  **🕵️Keywords:** Benchmark Dataset · KG Completion

- `[IEEE Access-2020/05]` **Utilizing Textual Information in Knowledge Graph Embedding: A Survey of Methods and Applications.** [[📄](https://doi.org/10.1109/ACCESS.2020.2995074)] 

  **🕵️Keywords:** KG Embedding · Textual Information 

- `[arXiv-2020/05]` **A Survey on Graph Neural Networks for Knowledge Graph Completion.** [[📄](https://arxiv.org/abs/2007.12374v1)] 

  **🕵️Keywords:** KG Completion · GNNs 

- `[TKDE-2017/12]` **Knowledge Graph Embedding: A Survey of Approaches and Applications.** [[📄](https://doi.org/10.1109/TKDE.2017.2754499)] 

  **🕵️Keywords:** KG Embedding · Statistical Relational Learning · Matrix Factorization

​	</details> 

</br>

<details open>
    <summary><b>👈 Reasoning </b></summary>
[**[ Jump to ToC ]**](#🔍-table-of-contents)

# Reasoning

### 2025

- `[arXiv-2025/03]` **KnowPath: Knowledge-enhanced Reasoning via LLM-generated Inference Paths over Knowledge Graphs.** [[📄](https://arxiv.org/pdf/2502.12029v2)]

  **🕵️Keywords:** Knowledge-Enhanced LLMs · Inference Paths · KGQA 

- `[arXiv-2025/03]` **Rewarding Graph Reasoning Process makes LLMs more Generalized Reasoners.** [[📄](https://arxiv.org/pdf/2503.00845v1)]

  **🕵️Keywords:** LLMs · Graph Reasoning · Reinforcement Learning · Process Reward Models 

- `[WWW'25-2025/01]` **Paths-over-Graph: Knowledge Graph Empowered Large Language Model Reasoning.** [[📄](https://openreview.net/forum?id=ICJysB6LdA)] [[🛠️](https://github.com/SteveTANTAN/PoG)]

  **🕵️Keywords:** LLM Reasoning · Multi-Hop Path Exploration · QA 

- `[arXiv-2025/01]` **Grounding LLM Reasoning with Knowledge Graphs.** [[📄](https://arxiv.org/abs/2502.13247v2)]

  **🕵️Keywords:** LLM Reasoning · LLMs · KGs

### 2024

- `[ICLR'24-2024/01]` **Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph.** [[📄](https://openreview.net/forum?id=nnVO1PvbTv)] [[🛠️](https://github.com/IDEA-FinAI/ToG)] 

  **🕵️Keywords:** LLM Reasoning · KGs · ToG

### 2023

- `[EMNLP'23 Findings-2023/12]` **KG-GPT: A general framework for reasoning on knowledge graphs using large language models.** [[📄](https://aclanthology.org/2023.findings-emnlp.631/)] [[🛠️](https://github.com/jiho283/KG-GPT)] 

  **🕵️Keywords:** Reasoning · LLMs · KGQA

​	</details> 

</br>

<details open>
    <summary><b>👈 Graph RAG </b></summary>
[**[ Jump to ToC ]**](#🔍-table-of-contents)

# Graph RAG 

### 2025

- `[arXiv-2025/03]` **PIKE-RAG: Specialized Knowledge and Rationale Augmented Generation.** [[📄](https://arxiv.org/pdf/2501.11551v4)]

  **🕵️Keywords:** RAG · LLMs · Specialized Knowledge · Knowledge Atomizing · Knowledge-Aware Task Decomposition

- `[arXiv-2025/02]` **GFM-RAG: Graph Foundation Model for Retrieval Augmented Generation.** [[📄](https://arxiv.org/pdf/2502.01113v1)] [[🛠️](https://github.com/RManLuo/gfm-rag)]

  **🕵️Keywords:** RAG · LLMs · KGs · Graph Foundation Model

- `[arXiv-2025/02]` **Are Large Language Models In-Context Graph Learners.** [[📄](https://arxiv.org/pdf/2502.13562v1)]

  **🕵️Keywords:** RAG · LLMs · GNNs · In-Context Learning

- `[arXiv-2025/01]` **HopRAG: Multi-Hop Reasoning for Logic-Aware Retrieval-Augmented Generation.** [[📄](https://arxiv.org/abs/2502.12442v1)]

  **🕵️Keywords:** Multi-Hop Reasoning · RAG · Logic-Aware Retrieval

- `[arXiv-2025/01]` **CG-RAG: Research Question Answering by Citation Graph Retrieval-Augmented LLMs.** [[📄](https://arxiv.org/abs/2501.15067v1)]

  **🕵️Keywords:** Citation Graphs · RAG · Question Answering

- `[arXiv-2025/01]` **Fast Think-on-Graph: Wider, Deeper and Faster Reasoning of Large Language Model on Knowledge Graph.** [[📄](https://arxiv.org/pdf/2501.14300v1)] [[🛠️](https://github.com/dosonleung/FastToG)]

  **🕵️Keywords:** Graph RAG · KGs · LLMs · Think-on-Graph

### 2024

- `[arXiv-2024/12]` **HybGRAG: Hybrid Retrieval-Augmented Generation on Textual and Relational Knowledge Bases.** [[📄](https://arxiv.org/abs/2412.16311v1)]

  **🕵️Keywords:** Graph RAG · Semi-Structured Knowledge Base · Hybrid Question Answering

  `[arXiv-2024/03]` **GNN-RAG: Graph Neural Retrieval for Large Language Model Reasoning.** [[📄](https://arxiv.org/pdf/2405.20139v1)] [[🛠️](https://github.com/cmavro/GNN-RAG)]

  **🕵️Keywords:** LLM Reasoning · RAG · KGQA 

- `[AAAI'24-2024/03]` **Graph Neural Prompting with Large Language Models.** [[📄](https://ojs.aaai.org/index.php/AAAI/article/view/29875)] [[🛠️](https://github.com/amazon-science/GNP)]

  **🕵️Keywords:** RAG · LLMs · KGs · Graph Neural Prompting

​	</details> 

<br/>

<details open>
    <summary><b>👈 KG Completion </b></summary>
[**[ Jump to ToC ]**](#🔍-table-of-contents)

# KG Completion

### 2024

- `[MM'24-2024/10]` **Making Large Language Models Perform Better in Knowledge Graph Completion.** [[📄](https://dl.acm.org/doi/abs/10.1145/3664647.3681327)] [[🛠️](https://github.com/zjukg/KoPA)]

  **🕵️Keywords:** KG Completion · LLMs · Structure-Text · Knowledge Adaption

​	</details> 

</br>

<details open>
    <summary><b>👈 Question Answering </b></summary>
[**Jump to ToC**](#🔍-table-of-contents)

# Question Answering 

### 2024

- `[ACL'24 Findings-2024/08]` **Knowledgeable Preference Alignment for LLMs in Domain-specific Question Answering.** [[📄](https://aclanthology.org/2024.findings-acl.52/)] [[🛠️](https://github.com/zjukg/KnowPAT)]

  **🕵️Keywords:**  Knowledgeable Preference Alignment · LLMs · KGs · Question Answering

- `[arXiv-2024/12]` **TrustUQA: A Trustful Framework for Unified Structured Data Question Answering.** [[📄](https://arxiv.org/abs/2406.18916v2)] [[🛠️](https://github.com/zjukg/TrustUQA)]

  **🕵️Keywords:** Knowledge Representation · KGQA · LLMs · Condition Graph

### 2023

- `[ICLR'23-2023/02]` **UniKGQA: Unified Retrieval and Reasoning for Solving Multi-hop Question Answering Over Knowledge Graph.** [[📄](https://openreview.net/forum?id=Z63RvyAZ2Vh)] [[🛠️](https://github.com/RUCAIBox/UniKGQA)]

  **🕵️Keywords:** Retrieval and Reasoning · Multi-Hop QA · KGs 

​	</details> 

<br/>

[**Jump to ToC **](#🔍-table-of-contents)



<details open>
    <summary><b>👈 Representation Learning </b></summary>
# Representation Learning

### 2025

- `[arXiv-2025/03]` **LLM as GNN: Graph Vocabulary Learning for Text-Attributed Graph Foundation Models.** [[📄](https://arxiv.org/abs/2503.03313v1)] [[❌](https://github.com/agiresearch/PromptGFM)]

  **🕵️Keywords:** Text-Attributed Graphs · GNNs · LLMs · Graph Foundation Models

- `[arXiv-2025/03]` **Graph-Augmented Reasoning: Evolving Step-by-Step Knowledge Graph Retrieval for LLM Reasoning.** [[📄](https://arxiv.org/abs/2503.01642v1)]

  **🕵️Keywords:** LLM Reasoning · KGs Enhanced Reasoning · Post-Retrieval Processing and Reward Model

### 2024

- `[EACL'24 Findings-2024/03]` **Language is All a Graph Need.** [[📄](https://aclanthology.org/2024.findings-eacl.132/)] [[🛠️](https://github.com/agiresearch/InstructGLM)]

  **🕵️Keywords:** LLMs · Graph Representation Learning · Prompt Instruction

​	</details> 

<br/>



