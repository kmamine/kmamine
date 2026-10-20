<div align="center">

# Mohamed Amine Kerkouri

<a href="https://github.com/kmamine">
<img alt="Mohamed Amine Kerkouri, AI Research Scientist" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=1E90FF&center=true&vCenter=true&width=820&lines=AI+Research+Scientist+%C2%B7+PhD;LLM+evaluation+%26+model+behaviour;Reasoning+traces%2C+not+just+answers;Foveated+MLLMs+vs.+human+gaze;Studying+the+path%2C+not+only+the+destination"/>
</a>

[![Profile Views](https://komarev.com/ghpvc/?username=kmamine&color=1E90FF&style=for-the-badge&label=Profile+Views)](https://github.com/kmamine)
[![Followers](https://img.shields.io/github/followers/kmamine?style=for-the-badge&color=1E90FF&labelColor=0E4D92&logo=github)](https://github.com/kmamine?tab=followers)

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en)
[![Citations](https://img.shields.io/badge/Citations-220%2B-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en)
![h-index](https://img.shields.io/badge/h--index-8-4285F4?style=for-the-badge)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Mohamed-Kerkouri-2)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamed-amine-kerkouri)
[![Website](https://img.shields.io/badge/Website-1E90FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kmamine.github.io)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kerkourima@gmail.com)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

</div>

> **What I work on:** how a system arrives at an answer, and whether that process is faithful to the evidence. I study it in model reasoning traces, in multimodal models that search images the way people do, and in retrieval-grounded systems. I build the measurement that checks the answer instead of trusting it.

I'm an AI researcher in Paris: **AI Research Scientist at F.initiatives** and **AIOps Architect at NeoPhi**.

🔭 **Currently:** reasoning-trace analysis and LLM behaviour evaluation · hallucination detection in scientific RAG at NeoPhi
&nbsp;&nbsp;•&nbsp;&nbsp; 🏆 **Recent:** Outstanding Paper Award, ECCV 2026 Human-Inspired Computer Vision Workshop
&nbsp;&nbsp;•&nbsp;&nbsp; 💬 **Ask me about** LLM evaluation, reasoning traces, scanpath modelling, model merging

## 🧠 Model behaviour & evaluation

- **[whitecircle_killbench_anlaysis](https://github.com/kmamine/whitecircle_killbench_anlaysis)**: independent reasoning-trace analysis of White Circle's KillBench (552,973 choices, 15 models, 69,867 traces). Finds strong position bias (gemini-3.1-pro picks the first-listed person 84.8% of the time) and low decision repeatability, plus a controlled null linking trace structure to bias · [data on 🤗 Hub](https://huggingface.co/datasets/Amine-CV/whitecircle_killbench_analysis)
- **[ThinkProb](https://github.com/kmamine/ThinkProb)**: turns chain-of-thought into thought graphs without any generative calls and scores a 22-metric reasoning profile; 4,200 traces from 7 LLMs · [arXiv:2606.29067](https://arxiv.org/abs/2606.29067) · [data](https://huggingface.co/datasets/Amine-CV/thinkprob)
- **[MODG](https://github.com/kmamine/MODG)**: an agentic harness where multimodal LLMs search scenes one foveated glimpse at a time. Models match humans on the answer but not on the search process · *ECCV 2026 Workshop, Outstanding Paper* · [arXiv:2608.16514](https://arxiv.org/abs/2608.16514) · [data](https://huggingface.co/datasets/Amine-CV/MODG)
- **[CAM_Quant](https://github.com/kmamine/CAM_Quant)**: how int16/int8 quantization shifts the class activation maps of six CNN architectures, measured against visual saliency · *IPTA 2024*

## 🛡️ Trustworthy & retrieval-grounded AI

- **[HeReFaNMi](https://github.com/kmamine/herefanmi-redo)**: *Health-Related Fake News Mitigation*. Retrieves evidence and triages health claims as trustworthy / doubtful / fake with source grounding · *EU NGI Search funded* · chunking-strategy paper at *AIxIA*
- **[Enlighten-AI](https://github.com/kmamine/Enlighten-AI)**: citation-grounded RAG assistant with safety guardrails and a [red-team report](https://github.com/kmamine/Enlighten-AI/blob/main/RED_TEAM_REPORT.md) (OWASP LLM Top 10, MITRE ATLAS; two vulnerabilities found and fixed)

## 🛠️ LLM post-training & agents

- **[llm-tuning-lab](https://github.com/kmamine/llm-tuning-lab)**: Claude Code plugin of 11 skills for post-training LLMs as controlled experiments (SFT, LoRA/QLoRA, continual pretraining, DPO/ORPO/KTO, merging) with error bars and significance tests
- **[merge-corrected SFT distillation](https://github.com/kmamine/merge-corrected-sft-distillation-Qwen-Mythos-0.8B)**: reasoning distillation into Qwen3.5-0.8B with per-epoch, benchmark-gated model merging; +3.7 pts GSM8K over the base model · [model on 🤗 Hub](https://huggingface.co/Amine-CV/Qwen3.5-0.8B-Mythos-Distill)
- **[APEX](https://github.com/kmamine/APEX_New)**: agentic portrait editing where an MLLM plans and judges each edit and an ArcFace identity gate must agree before it is accepted

## 👁️ Visual attention & gaze

- **[FDISS](https://github.com/kmamine/FDISS)**: Foveal Disc IoU Scanpath Score, a perceptually grounded scanpath metric · *ETRA 2026* · `pip install fdiss`
- **[scanpath_nlp_metrics](https://github.com/kmamine/scanpath-semantic-similarity)**: compares scanpaths through VLM descriptions plus the classical spatial and MultiMatch suite · *ETRA 2026* · `pip install scanpath_nlp_metrics`
- **[Artism_ASD_dirvergent_gaze](https://github.com/kmamine/Artism_ASD_dirvergent_gaze)**: spatial and temporal gaze signatures of autistic adults, artists and neurotypical viewers on paintings (2,091 scanpaths)
- **[AVAtt](https://github.com/kmamine/AVAtt---Art-Visual-Attention)**: visual-attention dataset for paintings (scanpaths and saliency) · *ETRA 2024*
- **[SSLArtScanpath](https://github.com/kmamine/SSLArtScanpath)** · *CVPR Workshops 2022* and **[SP_Gen](https://github.com/kmamine/SP_Gen)** · *CBMI 2022*: scanpath prediction on paintings
- **[GBVS_Pytorch](https://github.com/kmamine/GBVS_Pytorch)**: PyTorch port of Graph-Based Visual Saliency (Harel, Koch & Perona, 2006)

## 📄 Selected publications

- **M. A. Kerkouri**, M. Tliba, A. Chetouani, U. Bagci, A. Bruno. *Matched Outcomes, Divergent Gaze: How Foveated MLLMs Search Compared to Humans.* **ECCV 2026 Workshops (HCV), Outstanding Paper Award.** [arXiv](https://arxiv.org/abs/2608.16514)
- **M. A. Kerkouri** et al. *ThinkProbe: Beyond Accuracy, Structural Profiling of Open-Ended LLM Reasoning Traces via Non-Generative Thought Graphs.* **Preprint, 2026.** [arXiv](https://arxiv.org/abs/2606.29067)
- **M. A. Kerkouri**, M. Tliba, B. Wang, A. Chetouani, U. Bagci, A. Bruno. *What They Saw, Not Just Where They Looked: Semantic Scanpath Similarity via VLMs and NLP Metrics.* **ETRA 2026.**
- **M. A. Kerkouri**, M. Tliba, Z. Sellam, C. Distante, A. Bruno, A. Chetouani. *Closing the Foveal Gap: Perceptually Grounded Scanpath Comparison with Disc IoU.* **ETRA 2026.**
- **M. A. Kerkouri**, M. Tliba, A. Chetouani, A. Bruno. *Quantization Effects on Neural Networks Perception.* **IPTA 2024.** [arXiv](https://arxiv.org/abs/2403.09939)
- M. Tliba, **M. A. Kerkouri**, A. Chetouani, A. Bruno. *Self-Supervised Scanpath Prediction Framework for Painting Images.* **CVPR Workshops 2022** (equal contribution). [paper](https://openaccess.thecvf.com/content/CVPR2022W/Ego4D-EPIC/html/Tliba_Self_Supervised_Scanpath_Prediction_Framework_for_Painting_Images_CVPRW_2022_paper.html)

<sub>Full list on [Google Scholar](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en) and [ResearchGate](https://www.researchgate.net/profile/Mohamed-Kerkouri-2).</sub>

---

<div align="center">

### 📊 GitHub activity

<img alt="Streak" src="https://streak-stats.demolab.com/?user=kmamine&theme=tokyonight&hide_border=true"/>

<!-- <img width="95%" alt="Contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=kmamine&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph"/> -->

</div>

<img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E90FF,100:0E4D92&height=120&section=footer"/>
