# Agentic-AI-in-Biomedical-and-Healthcare
Agentic AI in Biomedicine and Healthcare: A Modality-Centric Systematic Review of Frameworks, Challenges, and Future Directions

A systematic review of emerging agentic AI frameworks, architectures, enabling technologies, evaluation strategies, and research directions across biomedical and healthcare applications (2024–2026).

This work is currently **under review** for publication. Please do not distribute, reproduce, or cite any part of this manuscript without the authors' permission.

## Novelty and Scope

Most existing reviews discuss agentic AI in healthcare broadly, organize the literature around general applications or technical capabilities, or cover selected clinical domains. In contrast, this review adopts a **modality-centric perspective**, systematically organizing agentic AI research across six biomedical data modalities: **time series, clinical text, medical imaging, clinical video, multimodal data, and bioinformatics**. This organization helps researchers quickly identify, explore, and compare modern agentic AI frameworks relevant to their modality of interest, while revealing modality-specific methods, application patterns, limitations, and research opportunities.


## Review Contributions

1. **Six-modality coverage:** A modality-centric taxonomy and systematic review of agentic AI across time series, clinical text, medical imaging, clinical video, multimodal data, and bioinformatics.
2. **Five key aspects:** A structured analysis of (i) concepts, (ii) agentic frameworks, (iii) enabling technologies, (iv) risks and challenges, and (v) future directions.
3. **Quantitative synthesis:** A descriptive quantitative analysis of the reviewed studies, including backbone models, agent architectures, datasets, and evaluation practices.

<p align="center">
  <img width="100%" alt="Scope of the review" src="https://github.com/user-attachments/assets/2eb89793-7525-44cb-8a64-ef9548841253" />
</p>

<p align="center">
  <em><strong>Figure 1.</strong> Scope of the review: (a) key distinctions over existing reviews, (b) six clinical and healthcare data modalities covered, and (c) five key aspects, including agentic AI concepts, representative frameworks, enabling technologies, associated risks and challenges, and future research directions with recommendations.</em>
</p>


## Key Findings

- **53 studies** systematically reviewed following PRISMA 2020 guidelines, selected from 479 identified records.
- **Six biomedical modalities** covered: time series (5), clinical text (11), medical imaging (6), clinical video (4), multimodal data (14), and bioinformatics (13).
- **Multi-agent architectures** adopted in 36 studies (67.9%), highlighting the growing use of collaborative agent systems.
- **Backbone models:** GPT-based models were most frequently reported (30 occurrences), followed by LLaMA (13), Claude (11), and Qwen (11).
- **Dataset landscape:** 168 dataset occurrences across 53 studies, including 141 public and 27 private dataset occurrences.
- **Evaluation practices:** 191 evaluation metric occurrences across 52 studies, with accuracy (33 studies), F1-score (13), and AUROC (10) being the most frequently reported.
- **Evidence landscape:** 25 studies (47.2%) reported benchmark or experimental evidence, 16 (30.2%) retrospective clinical validation, and 12 (22.6%) prototype or clinician evaluation.
- **Reproducibility:** 26 studies (49.1%) released publicly accessible source code.


## Quantitative Synthesis of Reviewed 53 Agentic Studies

<p align="center">
  <img width="4320" height="3420" alt="Fig_quantitative_synthesis" src="https://github.com/user-attachments/assets/59b37a92-0773-4932-9493-c3e86487ec1f" />
</p>

<p align="center">
  <em><strong>Figure 2.</strong> (a) Distribution of studies by data modality. (b) Publication status (PR, peer-reviewed; PP, preprint) and public code availability (counted only when code was released in a public repository). (c) Single- versus multi-agent architectures within each modality. (d) Evidence level within each modality.</em>
</p>




## Major Challenges and Research Directions

- Hallucination propagation and error accumulation across multi-step agent workflows.
- Reliable planning, tool utilization, and multi-agent coordination.
- Patient privacy, data security, and prompt-injection vulnerabilities.
- Automation bias, clinical accountability, and human oversight.
- Limited external validation and real-world clinical effectiveness.
- Standardized agent-specific evaluation and safety assessment.

## Future Levels of Agentic Intelligence

<img width="1808" height="804" alt="aai future revised" src="https://github.com/user-attachments/assets/4a8dcc81-99a1-4d4b-a822-e184a7ac5d6b" />



## Agentic Technologies

- Core Technologies for Agentic AI
- Agentic AI Orchestration Frameworks
- Selecting Frameworks for Biomedical and Healthcare Applications
- Evaluation Metrics of Agentic Models


## Study-Level Data Extraction

The accompanying Excel file contains the extracted information for all 53 included studies, allowing researchers to explore the study characteristics, modalities, agentic frameworks, models, datasets, tasks, and evaluation details.

- **Full study extraction table:** `AAI Review 53S Full Data by Rabiul Islam.xlsx`

*The complete Excel file is available for download in the repository's Files section.*

## Citation

If you find this review useful, please cite:

*Citation details will be updated upon publication.*

---

**Keywords:** Agentic AI · Biomedical AI · Healthcare · Large Language Models · Multi-Agent Systems · Multimodal AI · Clinical Decision Support · Systematic Review



---

## Contact

**Md Rabiul Islam**  
Ph.D. Researcher, Department of Electrical and Computer Engineering  
**Texas A&M University**

**Research Interests:** Agentic AI, Biomedical AI, Medical Imaging, Multimodal Learning, Large Language Models, and Interpretable Clinical AI.

- **Email:** [rabiul.kuet.bd@gmail.com](mailto:rabiul.kuet.bd@gmail.com)
- **Google Scholar:** [Google Scholar Profile](https://scholar.google.com/citations?user=GfveUqIAAAAJ&hl=en)
- **ORCID:** [ORCID Profile](https://orcid.org/0000-0002-5840-5882)
- **Personal Website:** [Personal Website Link](https://sites.google.com/view/rabiuleeekuet/home?pli=1&authuser=0)

---



# 53 Reviewed Agentic AI Studies by Modality

The following studies are organized by the six modalities used in this review. Each entry identifies the framework or paper name, first author, article title, and reported task. Paper names link to the DOI or article URL recorded in the study-extraction table.

### Time-Series Data (5 studies)

- [ECG-Agent](https://doi.org/10.48550/arXiv.2601.20323) — **First author:** Hyunseung Chung; **Title:** ECG-AGENT: ON-DEVICE TOOL-CALLING AGENT FOR ECG MULTI-TURN DIALOGUE; **Task:** Signal classification.
- [Stress Agentic Crew](https://doi.org/10.1007/s44196-026-01215-0) — **First author:** Talha Iqbal; **Title:** Agentic AI System for Stress Monitoring: A Multi-agent Healthcare Crew; **Task:** Stress monitoring.
- [Organ-Agents](https://doi.org/10.48550/arXiv.2508.14357) — **First author:** Rihao Chang; **Title:** Organ-Agents: Virtual Human Physiology Simulator via LLMs; **Task:** Physiology simulation.
- [ICVision](https://doi.org/10.1109/ICMI68585.2026.11539774) — **First author:** Zag ElSayed; **Title:** AutocleanEEG - ICVision: Automated ICA Artifact Classification Using Vision-Language AI; **Task:** Signal classification.
- [SpikeAgent](https://pmc.ncbi.nlm.nih.gov/articles/PMC11844495/) — **First author:** Zuwan Lin; **Title:** SpikeAgent: a multimodal LLM-based AI agent for automated spike sorting; **Task:** Signal analysis.

### Clinical Text (11 studies)

- [RETROSUM (Framework)](https://doi.org/10.48550/arXiv.2601.13918) — **First author:** Yusheng Liao; **Title:** AGENTEHR: Advancing Autonomous Clinical Decision-Making via Retrospective Summarization; **Task:** Clinical decision-making.
- [Modular Multi-Agent Pipeline](https://doi.org/10.48550/arXiv.2602.14158) — **First author:** Naeimeh Nourmohammadi; **Title:** A Multi-Agent Framework for Medical AI: Leveraging Fine-Tuned GPT, LLaMA, and DeepSeek R1...; **Task:** Question answering.
- [AgenticSum](https://doi.org/10.48550/arXiv.2602.20040) — **First author:** Fahmida Liza Piya; **Title:** AgenticSum: An Agentic Inference-Time Framework for Faithful Clinical Text Summarization; **Task:** Text summarisation.
- [OpenMedCalc (Agentic Toolkit)](https://doi.org/10.1038/s41746-025-01475-8) — **First author:** Alex J. Goodell; **Title:** Large language model agents can use tools to perform clinical calculations; **Task:** Clinical calculation.
- [ChatRWD](https://doi.org/10.1177/20552076251348850) — **First author:** Yen Sia Low; **Title:** Answering real-world clinical questions using large language model, retrieval-augmented generation, and agentic systems; **Task:** Question answering.
- [MedAgentBench (Benchmark)](https://doi.org/10.1056/AIdbp2500144) — **First author:** Yixing Jiang; **Title:** MedAgentBench: A Realistic Virtual EHR Environment to Benchmark Medical LLM Agents; **Task:** EHR task execution.
- [AKI-Detector](https://pmc.ncbi.nlm.nih.gov/articles/PMC12919426/) — **First author:** Tongyue Shi; **Title:** AKI-Detector: A Multi-Agent Framework by Integrating Machine Learning and Large Language Models for Early Prediction of Acute Kidney Injury in ICU; **Task:** Clinical diagnosis.
- [Y-KNOT (Y-KNOT-med-base, Y-KNOT-MD)](https://doi.org/10.2196/76848) — **First author:** Hanjae Kim; **Title:** A Bilingual On-Premises AI Agent for Clinical Drafting: Implementation Report of Seamless Electronic Health Records Integration in the Y-KNOT Project; **Task:** Clinical document drafting.
- [CARE-AD](https://doi.org/10.1038/s41746-025-01940-4) — **First author:** Rumeng Li; **Title:** CARE-AD: a multi-agent large language model framework for Alzheimer’s disease prediction using longitudinal clinical notes; **Task:** Risk prediction.
- [MRAgent](https://doi.org/10.1093/bib/bbaf140) — **First author:** Wei Xu; **Title:** MRAgent: an LLM-based automated agent for causal knowledge discovery in disease via Mendelian randomization; **Task:** Knowledge discovery.
- [ESCARGOT](https://doi.org/10.1093/bioinformatics/btaf031) — **First author:** Nicholas Matsumoto; **Title:** ESCARGOT: an AI agent leveraging large language models, dynamic graph of thoughts, and biomedical knowledge graphs for enhanced reasoning; **Task:** Biomedical reasoning.

### Medical Imaging (6 studies)

- [LAMMI-Pathology](https://doi.org/10.48550/arXiv.2602.18773) — **First author:** Haoyang Su; **Title:** LAMMI-Pathology: A Tool-Centric Bottom-Up LVLM-Agent Framework for Molecularly Informed Medical Intelligence in Pathology; **Task:** Clinical diagnosis.
- [M3Builder](https://doi.org/10.1007/978-3-032-06004-4_12) — **First author:** Jinghao Feng; **Title:** M3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging; **Task:** Model development.
- [mAIstro](https://doi.org/10.1016/j.ejrai.2025.100044) — **First author:** Eleftherios Tzanis; **Title:** mAIstro: An open-source multi-agent system for automated end-to-end development of radiomics and deep learning models for medical imaging; **Task:** Model development.
- [TissueLab (TLAgent)](https://doi.org/10.48550/arXiv.2509.20279) — **First author:** Songhao Li; **Title:** A co-evolving agentic AI system for medical imaging analysis; **Task:** Medical image analysis.
- [RadFabric](https://doi.org/10.48550/arXiv.2506.14142) — **First author:** Wenting Chen; **Title:** RadFabric: Agentic AI System with Reasoning Capability for Radiology; **Task:** Medical image analysis.
- [Agent-MIRA](https://doi.org/10.1016/j.compmedimag.2026.102725) — **First author:** Rajat Vashistha; **Title:** Agent-MIRA: AI-orchestrated medical imaging agent for PET image retrieval and assistance; **Task:** Clinical decision-making.

### Clinical Video (4 studies)

- [SurgRAW](https://doi.org/10.1109/LRA.2026.3665443) — **First author:** Chang Han Low; **Title:** SurgRAW: Multi-Agent Workflow with Chain of Thought Reasoning for Robotic Surgical Video Analysis; **Task:** Surgical video reasoning.
- [Discrete Diffusion VLA](https://doi.org/10.1007/978-3-032-06004-4_2) — **First author:** Huixin Zhan; **Title:** Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk Quantification via Discrete Diffusion in a Vision-Language-Action Framework; **Task:** Surgical gesture prediction.
- [VISA](https://doi.org/10.48550/arXiv.2511.07392) — **First author:** Hyeryun Park; **Title:** Voice-Interactive Surgical Agent for Multimodal Patient Data Control; **Task:** Intraoperative assistance.
- [ORDiRS-Agent](https://doi.org/10.1007/978-3-032-05114-1_40) — **First author:** Yiqing Shen; **Title:** Operating Room Workflow Analysis via Reasoning Segmentation over Digital Twins; **Task:** Surgical workflow analysis.

### Multimodal Data (14 studies)

- [AutoHealth](https://doi.org/10.48550/arXiv.2602.01078) — **First author:** Tong Xia; **Title:** AutoHealth: An Uncertainty-Aware Multi-Agent System for Autonomous Health Data Modeling; **Task:** Health data modelling.
- [MedChat](https://doi.org/10.1109/MIPR67560.2025.00078) — **First author:** Philip R. Liu; **Title:** MedChat: A Multi-Agent Framework for Multimodal Diagnosis with Large Language Models; **Task:** Clinical diagnosis.
- [MedMMV](https://doi.org/10.48550/arXiv.2509.24314) — **First author:** Hongjun Liu; **Title:** MEDMMV: A CONTROLLABLE MULTIMODAL MULTI-AGENT FRAMEWORK FOR RELIABLE AND VERIFIABLE CLINICAL REASONING; **Task:** Clinical decision-making.
- [AURA](https://link.springer.com/chapter/10.1007/978-3-032-06004-4_11) — **First author:** Nima Fathi; **Title:** AURA: A Multi-Modal Medical Agent for Understanding, Reasoning & Annotation; **Task:** Medical image analysis.
- [MultiMedRes](https://doi.org/10.1002/aisy.202400840) — **First author:** Zishan Gu; **Title:** A Proactive Agent Collaborative Framework for Zero-Shot Multimodal Medical Reasoning; **Task:** Visual question answering.
- [TAP-GPT](https://doi.org/10.48550/arXiv.2603.17191) — **First author:** Sophie Kearney; **Title:** Tabular LLMs for Interpretable Few-Shot Alzheimer’s Disease Prediction with Multimodal Biomedical Data; **Task:** Clinical diagnosis.
- [DeepRare](https://doi.org/10.1038/s41586-025-10097-9) — **First author:** Weike Zhao; **Title:** An agentic system for rare disease diagnosis with traceable reasoning; **Task:** Clinical diagnosis.
- [MELLMA (Multi-Expert LLM Arbitrated framework)](https://doi.org/10.1016/j.compmedimag.2026.102704) — **First author:** Shyam Sundar Debsarkar; **Title:** A multi-expert deep learning framework with LLM-guided arbitration for multimodal histopathology prediction; **Task:** Clinical diagnosis.
- [Agentic Lab](https://doi.org/10.1101/2025.11.11.686354) — **First author:** Wenbo Wang; **Title:** Agentic Lab: An Agentic-physical AI system for cell and organoid experimentation and manufacturing; **Task:** Multimodal data analysis.
- [Talk2Biomodels (T2B)](https://doi.org/10.1186/s12859-025-06310-1) — **First author:** Lilija Wehling; **Title:** Talk2Biomodels: AI agent-based open-source LLM initiative for kinetic biological models; **Task:** Biological model analysis.
- [Unnamed (LLM-based AutoML agent)](https://doi.org/10.3389/frai.2025.1680845) — **First author:** Rong Huang; **Title:** A human-centered automated machine learning agent with large language models for multimodal data management and analysis; **Task:** Multimodal data analysis.
- [NR](https://doi.org/10.3389/fnins.2025.1688509) — **First author:** Wenmiao Wang; **Title:** LLM-based multi-agent system for neuro-ophthalmic diagnosis and personalized treatment planning; **Task:** Diagnosis and treatment planning.
- [ADAM-1 (ADAM)](https://doi.org/10.1109/ACCESS.2025.3599857) — **First author:** Ziyuan Huang; **Title:** ADAM-1: An AI Reasoning and Bioinformatics Model for Alzheimer’s Disease Detection and Microbiome-Clinical Data Integration; **Task:** Clinical diagnosis.
- [RadAgents](https://proceedings.mlr.press/v315/zhang26b.html) — **First author:** Kai Zhang; **Title:** RadAgents: Multimodal Agentic Reasoning for Chest X-ray Interpretation with Radiologist-like Workflows; **Task:** Medical image analysis.

### Bioinformatics (13 studies)

- [AgentGC](https://doi.org/10.18653/v1/2026.findings-acl.131) — **First author:** Hui Sun; **Title:** AgentGC: Evolutionary Learning-based Lossless Compression for Genomics Data with LLM-driven Multiple Agent; **Task:** Genomic data compression.
- [Agentomics](https://doi.org/10.64898/2026.01.27.702049) — **First author:** Vlastimil Martinek; **Title:** Agentomics: An Agentic System that Autonomously Develops Novel State-of-the-art Solutions for Biomedical Machine Learning Tasks; **Task:** Model design.
- [MARBLE](https://doi.org/10.48550/arXiv.2601.14349) — **First author:** Sunghyun Kim; **Title:** MARBLE: Multi-Agent Reasoning for Bioinformatics Learning and Evolution; **Task:** Model refinement.
- [Nano Bio-Agent (NBA)](https://doi.org/10.48550/arXiv.2509.19566) — **First author:** George Hong; **Title:** Nano Bio-Agents (NBA): Small Language Model Agents for Genomics; **Task:** Question answering.
- [BioAgents](https://doi.org/10.1038/s41598-025-25919-z) — **First author:** Nikita Mehandru; **Title:** BioAgents: Bridging the gap in bioinformatics analysis with multi-agent systems; **Task:** Bioinformatics pipeline development.
- [GenoMAS](https://doi.org/10.48550/arXiv.2507.21035) — **First author:** Haoyang Liu; **Title:** GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis; **Task:** Gene expression analysis.
- [BioDiscoveryAgent](https://proceedings.iclr.cc/paper_files/paper/2025/hash/4252dc94531833029000f85dc5fac792-Abstract-Conference.html) — **First author:** Yusuf Roohani; **Title:** BioDiscoveryAgent: An AI Agent for Designing Genetic Perturbation Experiments; **Task:** Research automation.
- [CellAgent](https://doi.org/10.1101/2024.05.13.593861) — **First author:** Yihang Xiao; **Title:** CellAgent: An LLM-driven Multi-Agent Framework for Automated Single-cell Data Analysis; **Task:** Single-cell analysis.
- [BioMedAgent](https://doi.org/10.1038/s41551-026-01634-6) — **First author:** Dechao Bu; **Title:** Empowering AI data scientists using a multi-agent LLM framework with self-evolving capabilities for autonomous, tool-aware biomedical data analyses; **Task:** Biomedical data analysis.
- [Qimai](https://doi.org/10.1101/2025.09.30.679628) — **First author:** Cong Liu; **Title:** Qimai: a multi-agent framework for zero-shot DNA-protein interaction prediction; **Task:** Protein–DNA interaction prediction.
- [Biomni (with components Biomni-A1, Biomni-E1)](https://doi.org/10.1101/2025.05.30.656746) — **First author:** Kexin Huang; **Title:** Biomni: A General-Purpose Biomedical AI Agent; **Task:** Research automation.
- [AutoBA](https://doi.org/10.1002/advs.202407094) — **First author:** Juexiao Zhou; **Title:** An AI Agent for Fully Automated Multi-Omic Analyses; **Task:** Omics data analysis.
- [AI-HOPE-WNT](https://doi.org/10.3389/frai.2025.1624797) — **First author:** Ei-Wen Yang; **Title:** Conversational AI agent for precision oncology: AI-HOPE-WNT integrates clinical and genomic data to investigate WNT pathway dysregulation in colorectal cancer; **Task:** Genomic analysis.

