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

The 53 reviewed studies are organized by six modalities, with details on frameworks, authors, tasks, architectures, publications, and available code.


### Time-Series (5 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [ECG-Agent](https://doi.org/10.48550/arXiv.2601.20323) | Hyunseung Chung | ECG-Agent: On-Device Tool-Calling Agent for ECG Multi-Turn Dialogue | Signal classification | Single-agent | arXiv | NA |
| [Stress Agentic Crew](https://doi.org/10.1007/s44196-026-01215-0) | Talha Iqbal | Agentic AI System for Stress Monitoring: A Multi-agent Healthcare Crew | Stress monitoring | Multi-agent | Int. J. Comput. Intell. Syst. | [Code](https://github.com/italha-d/StressAgenticCrew) |
| [Organ-Agents](https://doi.org/10.48550/arXiv.2508.14357) | Rihao Chang | Organ-Agents: Virtual Human Physiology Simulator via LLMs | Physiology simulation | Multi-agent | arXiv | NA |
| [ICVision](https://doi.org/10.1109/ICMI68585.2026.11539774) | Zag ElSayed | "AutocleanEEG - ICVision: Automated ICA Artifact Classification Using Vision-Language AI" | Signal classification | Single-agent | IEEE ICMI 2026 | [Code](https://github.com/cincibrainlab/autocleaneeg_pipeline) |
| [SpikeAgent](https://pmc.ncbi.nlm.nih.gov/articles/PMC11844495/) | Zuwan Lin | SpikeAgent: a multimodal LLM-based AI agent for automated spike sorting | Signal analysis | Single-agent | bioRxiv | [Code](http://github.com/LiuLab-Bioelectronics-Harvard/SpikeAgent) |

### Text (11 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [RETROSUM (Framework)](https://doi.org/10.48550/arXiv.2601.13918) | Yusheng Liao | AGENTEHR: Advancing Autonomous Clinical Decision-Making via Retrospective Summarization | Clinical decision-making | Multi-agent | arXiv | NA |
| [Modular Multi-Agent Pipeline](https://doi.org/10.48550/arXiv.2602.14158) | Naeimeh Nourmohammadi | A Multi-Agent Framework for Medical AI: Leveraging Fine-Tuned GPT, LLaMA, and DeepSeek R1... | Question answering | Multi-agent | arXiv | NA |
| [AgenticSum](https://doi.org/10.48550/arXiv.2602.20040) | Fahmida Liza Piya | AgenticSum: An Agentic Inference-Time Framework for Faithful Clinical Text Summarization | Text summarisation | Multi-agent | arXiv | NA |
| [OpenMedCalc (Agentic Toolkit)](https://doi.org/10.1038/s41746-025-01475-8) | Alex J. Goodell | Large language model agents can use tools to perform clinical calculations | Clinical calculation | Multi-agent | npj Digit. Med. | NA |
| [ChatRWD](https://doi.org/10.1177/20552076251348850) | Yen Sia Low | Answering real-world clinical questions using large language model, retrieval-augmented generation, and agentic systems | Question answering | Single-agent | Digital Health | NA |
| [MedAgentBench (Benchmark)](https://doi.org/10.1056/AIdbp2500144) | Yixing Jiang | MedAgentBench: A Realistic Virtual EHR Environment to Benchmark Medical LLM Agents | EHR task execution | Single-agent | NEJM AI | NA |
| [AKI-Detector](https://pmc.ncbi.nlm.nih.gov/articles/PMC12919426/) | Tongyue Shi | AKI-Detector: A Multi-Agent Framework by Integrating Machine Learning and Large Language Models for Early Prediction of Acute Kidney Injury in ICU | Clinical diagnosis | Multi-agent | AMIA Annu. Symp. Proc. | NA |
| [Y-KNOT (Y-KNOT-med-base, Y-KNOT-MD)](https://doi.org/10.2196/76848) | Hanjae Kim | A Bilingual On-Premises AI Agent for Clinical Drafting: Implementation Report of Seamless Electronic Health Records Integration in the Y-KNOT Project | Clinical document drafting | Single-agent | JMIR Med. Inform. | NA |
| [CARE-AD](https://doi.org/10.1038/s41746-025-01940-4) | Rumeng Li | CARE-AD: a multi-agent large language model framework for Alzheimer’s disease prediction using longitudinal clinical notes | Risk prediction | Multi-agent | npj Digit. Med. | NA |
| [MRAgent](https://doi.org/10.1093/bib/bbaf140) | Wei Xu | MRAgent: an LLM-based automated agent for causal knowledge discovery in disease via Mendelian randomization | Knowledge discovery | Single-agent | Brief. Bioinform. | [Code](https://github.com/xuwei1997/MRAgent) |
| [ESCARGOT](https://doi.org/10.1093/bioinformatics/btaf031) | Nicholas Matsumoto | ESCARGOT: an AI agent leveraging large language models, dynamic graph of thoughts, and biomedical knowledge graphs for enhanced reasoning | Biomedical reasoning | Single-agent | Bioinformatics | [Code](https://github.com/EpistasisLab/ESCARGOT) |

### Image (6 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [LAMMI-Pathology](https://doi.org/10.48550/arXiv.2602.18773) | Haoyang Su | LAMMI-Pathology: A Tool-Centric Bottom-Up LVLM-Agent Framework for Molecularly Informed Medical Intelligence in Pathology | Clinical diagnosis | Multi-agent | arXiv | [Code](https://github.com/Hoyant-Su/LAMMI) |
| [M3Builder](https://doi.org/10.1007/978-3-032-06004-4_12) | Jinghao Feng | M3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging | Model development | Multi-agent | MICCAI 2025 Workshop | NA |
| [mAIstro](https://doi.org/10.1016/j.ejrai.2025.100044) | Eleftherios Tzanis | mAIstro: An open-source multi-agent system for automated end-to-end development of radiomics and deep learning models for medical imaging | Model development | Multi-agent | Eur. J. Radiol. AI | [Code](https://github.com/eltzanis/mAIstro) |
| [TissueLab (TLAgent)](https://doi.org/10.48550/arXiv.2509.20279) | Songhao Li | A co-evolving agentic AI system for medical imaging analysis | Medical image analysis | Multi-agent | arXiv | [Code](https://tissuelab.org) |
| [RadFabric](https://doi.org/10.48550/arXiv.2506.14142) | Wenting Chen | RadFabric: Agentic AI System with Reasoning Capability for Radiology | Medical image analysis | Multi-agent | arXiv | NA |
| [Agent-MIRA](https://doi.org/10.1016/j.compmedimag.2026.102725) | Rajat Vashistha | Agent-MIRA: AI-orchestrated medical imaging agent for PET image retrieval and assistance | Clinical decision-making | Single-agent | Comput. Med. Imaging Graph. | NA |

### Video (4 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [SurgRAW](https://doi.org/10.1109/LRA.2026.3665443) | Chang Han Low | SurgRAW: Multi-Agent Workflow with Chain of Thought Reasoning for Robotic Surgical Video Analysis | Surgical video reasoning | Multi-agent | IEEE Robot. Autom. Lett. | [Code](https://github.com/jinlab-imvr/SurgRAW.git) |
| [Discrete Diffusion VLA](https://doi.org/10.1007/978-3-032-06004-4_2) | Huixin Zhan | Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk Quantification via Discrete Diffusion in a Vision-Language-Action Framework | Surgical gesture prediction | Single-agent | MICCAI 2025 Workshop | [Code](https://github.com/huixin-zhan-ai/Surgeon_style_fingerprinting) |
| [VISA](https://doi.org/10.48550/arXiv.2511.07392) | Hyeryun Park | Voice-Interactive Surgical Agent for Multimodal Patient Data Control | Intraoperative assistance | Multi-agent | arXiv | [Code](https://github.com/helena-lena/SAOP) |
| [ORDiRS-Agent](https://doi.org/10.1007/978-3-032-05114-1_40) | Yiqing Shen | Operating Room Workflow Analysis via Reasoning Segmentation over Digital Twins | Surgical workflow analysis | Single-agent | MICCAI 2025 | NA |

### Multimodal (14 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [AutoHealth](https://doi.org/10.48550/arXiv.2602.01078) | Tong Xia | AutoHealth: An Uncertainty-Aware Multi-Agent System for Autonomous Health Data Modeling | Health data modelling | Multi-agent | arXiv | [Code](https://anonymous.4open.science/r/AutoHealth-46E0) |
| [MedChat](https://doi.org/10.1109/MIPR67560.2025.00078) | Philip R. Liu | MedChat: A Multi-Agent Framework for Multimodal Diagnosis with Large Language Models | Clinical diagnosis | NA | IEEE MIPR 2025 | [Code](https://github.com/Purdue-M2/MedChat) |
| [MedMMV](https://doi.org/10.48550/arXiv.2509.24314) | Hongjun Liu | MedMMV: A Controllable Multimodal Multi-Agent Framework for Reliable and Verifiable Clinical Reasoning | Clinical decision-making | Multi-agent | arXiv | NA |
| [AURA](https://link.springer.com/chapter/10.1007/978-3-032-06004-4_11) | Nima Fathi | AURA: A Multi-Modal Medical Agent for Understanding, Reasoning & Annotation | Medical image analysis | Single-agent | MICCAI 2025 Workshop | [Code](https://nimafathi.github.io/AURA/) |
| [MultiMedRes](https://doi.org/10.1002/aisy.202400840) | Zishan Gu | A Proactive Agent Collaborative Framework for Zero-Shot Multimodal Medical Reasoning | Visual question answering | NA | Adv. Intell. Syst. | NA |
| [TAP-GPT](https://doi.org/10.48550/arXiv.2603.17191) | Sophie Kearney | Tabular LLMs for Interpretable Few-Shot Alzheimer’s Disease Prediction with Multimodal Biomedical Data | Clinical diagnosis | Single-agent | arXiv | [Code](https://github.com/sophie-kearney/TAP-GPT) |
| [DeepRare](https://doi.org/10.1038/s41586-025-10097-9) | Weike Zhao | An agentic system for rare disease diagnosis with traceable reasoning | Clinical diagnosis | NA | Nature | [Code](https://github.com/MAGIC-AI4Med/DeepRare) |
| [MELLMA (Multi-Expert LLM Arbitrated Framework)](https://doi.org/10.1016/j.compmedimag.2026.102704) | Shyam Sundar Debsarkar | A multi-expert deep learning framework with LLM-guided arbitration for multimodal histopathology prediction | Clinical diagnosis | Multi-agent | Comput. Med. Imaging Graph. | NA |
| [Agentic Lab](https://doi.org/10.1101/2025.11.11.686354) | Wenbo Wang | Agentic Lab: An Agentic-physical AI system for cell and organoid experimentation and manufacturing | Multimodal data analysis | NA | bioRxiv | [Code](https://github.com/LiuLab-Bioelectronics-Harvard/Agentic_lab) |
| [Talk2Biomodels (T2B)](https://doi.org/10.1186/s12859-025-06310-1) | Lilija Wehling | Talk2Biomodels: AI agent-based open-source LLM initiative for kinetic biological models | Biological model analysis | Single-agent | BMC Bioinform. | [Code](https://github.com/VirtualPatientEngine/AIAgents4Pharma) |
| [Unnamed (LLM-based AutoML agent)](https://doi.org/10.3389/frai.2025.1680845) | Rong Huang | A human-centered automated machine learning agent with large language models for multimodal data management and analysis | Multimodal data analysis | Single-agent | Front. Artif. Intell. | NA |
| [Unnamed (LLM-based Multi-Agent System)](https://doi.org/10.3389/fnins.2025.1688509) | Wenmiao Wang | LLM-based multi-agent system for neuro-ophthalmic diagnosis and personalized treatment planning | Diagnosis and treatment planning | Multi-agent | Front. Neurosci. | NA |
| [ADAM-1 (ADAM)](https://doi.org/10.1109/ACCESS.2025.3599857) | Ziyuan Huang | ADAM-1: An AI Reasoning and Bioinformatics Model for Alzheimer’s Disease Detection and Microbiome-Clinical Data Integration | Clinical diagnosis | Multi-agent | IEEE Access | [Code](https://github.com/melhzy/ADAM) |
| [RadAgents](https://proceedings.mlr.press/v315/zhang26b.html) | Kai Zhang | RadAgents: Multimodal Agentic Reasoning for Chest X-ray Interpretation with Radiologist-like Workflows | Medical image analysis | Multi-agent | MIDL 2026 (PMLR) | NA |

### Bioinformatics (13 studies)

| Framework | First Author | Title | Task | Architecture | Publication | Code |
|---|---|---|---|---|---|---|
| [AgentGC](https://doi.org/10.18653/v1/2026.findings-acl.131) | Hui Sun | AgentGC: Evolutionary Learning-based Lossless Compression for Genomics Data with LLM-driven Multiple Agent | Genomic data compression | Multi-agent | Findings of ACL 2026 | [Code](https://anonymous.4open.science/r/AgentGC-C0F7) |
| [Agentomics](https://doi.org/10.64898/2026.01.27.702049) | Vlastimil Martinek | Agentomics: An Agentic System that Autonomously Develops Novel State-of-the-art Solutions for Biomedical Machine Learning Tasks | Model design | Multi-agent | bioRxiv | [Code](https://github.com/BioGeMT/Agentomics-ML) |
| [MARBLE](https://doi.org/10.48550/arXiv.2601.14349) | Sunghyun Kim | MARBLE: Multi-Agent Reasoning for Bioinformatics Learning and Evolution | Model refinement | Multi-agent | arXiv | [Code](https://github.com/PRISM-DGU/MARBLE) |
| [Nano Bio-Agent (NBA)](https://doi.org/10.48550/arXiv.2509.19566) | George Hong | Nano Bio-Agents (NBA): Small Language Model Agents for Genomics | Question answering | Multi-agent | arXiv | [Code](https://github.com/georgesshong/nanobioagent) |
| [BioAgents](https://doi.org/10.1038/s41598-025-25919-z) | Nikita Mehandru | BioAgents: Bridging the gap in bioinformatics analysis with multi-agent systems | Bioinformatics pipeline development | Multi-agent | Sci. Rep. | [Code](https://github.com/microsoft/bioinformagus) |
| [GenoMAS](https://doi.org/10.48550/arXiv.2507.21035) | Haoyang Liu | GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis | Gene expression analysis | Multi-agent | arXiv | [Code](https://github.com/Liu-Hy/GenoMAS) |
| [BioDiscoveryAgent](https://proceedings.iclr.cc/paper_files/paper/2025/hash/4252dc94531833029000f85dc5fac792-Abstract-Conference.html) | Yusuf Roohani | BioDiscoveryAgent: An AI Agent for Designing Genetic Perturbation Experiments | Research automation | Multi-agent | ICLR 2025 | NA |
| [CellAgent](https://doi.org/10.1101/2024.05.13.593861) | Yihang Xiao | CellAgent: An LLM-driven Multi-Agent Framework for Automated Single-cell Data Analysis | Single-cell analysis | Multi-agent | bioRxiv | [Code](http://cell.agent4science.cn/) |
| [BioMedAgent](https://doi.org/10.1038/s41551-026-01634-6) | Dechao Bu | Empowering AI data scientists using a multi-agent LLM framework with self-evolving capabilities for autonomous, tool-aware biomedical data analyses | Biomedical data analysis | Multi-agent | Nat. Biomed. Eng. | [Code](https://github.com/BOBQWERA/BioMedAgent) |
| [Qimai](https://doi.org/10.1101/2025.09.30.679628) | Cong Liu | Qimai: a multi-agent framework for zero-shot DNA-protein interaction prediction | Protein–DNA interaction prediction | Multi-agent | bioRxiv | NA |
| [Biomni (with components Biomni-A1, Biomni-E1)](https://doi.org/10.1101/2025.05.30.656746) | Kexin Huang | Biomni: A General-Purpose Biomedical AI Agent | Research automation | Multi-agent | bioRxiv | [Code](https://biomni.stanford.edu) |
| [AutoBA](https://doi.org/10.1002/advs.202407094) | Juexiao Zhou | An AI Agent for Fully Automated Multi-Omic Analyses | Omics data analysis | Single-agent | Adv. Sci. | [Code](https://github.com/JoshuaChou2018/AutoBA) |
| [AI-HOPE-WNT](https://doi.org/10.3389/frai.2025.1624797) | Ei-Wen Yang | Conversational AI agent for precision oncology: AI-HOPE-WNT integrates clinical and genomic data to investigate WNT pathway dysregulation in colorectal cancer | Genomic analysis | Single-agent | Front. Artif. Intell. | [Code](https://github.com/Velazquez-Villarreal-Lab/AI-HOPE-WNT) |


ay dysregulation in colorectal cancer; **Task:** Genomic analysis.

