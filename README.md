<div align="center">

# Mohamed Amine Kerkouri

<a href="https://github.com/kmamine">
<img alt="Mohamed Amine Kerkouri — AI/ML Researcher, PhD in Computer Vision" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3200&pause=900&color=1E90FF&center=true&vCenter=true&width=820&lines=AI+%2F+ML+Researcher+%C2%B7+PhD%2C+Computer+Vision;Modeling+how+eyes+move+%E2%80%94+scanpaths+%26+gaze;Foveated+MLLMs+%C2%B7+RAG+faithfulness;Trustworthy+AI%3A+the+process%2C+not+just+the+answer;Studying+the+path%2C+not+only+the+destination"/>
</a>

[![Profile Views](https://komarev.com/ghpvc/?username=kmamine&color=1E90FF&style=for-the-badge&label=Profile+Views)](https://github.com/kmamine)
[![Followers](https://img.shields.io/github/followers/kmamine?style=for-the-badge&color=1E90FF&labelColor=0E4D92&logo=github)](https://github.com/kmamine?tab=followers)

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en)
[![Citations](https://img.shields.io/badge/Citations-190%2B-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en)
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

<!--
  RESEARCH FIGURE SLOT — your scanpath / saliency overlays are your most striking visual.
  Drop one here for an instant "this is my research" banner, e.g.:
  <div align="center"><img src="https://raw.githubusercontent.com/kmamine/<repo>/main/<path-to-figure>.png" width="720"/></div>
-->

> **What I work on:** how a system arrives at an answer — and how faithful that process is to the evidence behind it. I study it across human gaze (scanpaths), model reasoning traces, and retrieval-grounded systems, and I build the measurement harness that *checks* the answer rather than trusting it.

I'm an AI/ML researcher in Paris — **AI Researcher at F.initiatives** and **AIOps Architect at NeoPhi**.

🔭 **Currently:** foveated multimodal models and the faithfulness of machine vs. human gaze · retrieval and systematic-review agents at NeoPhi
&nbsp;&nbsp;•&nbsp;&nbsp; 🌱 **Interests:** visual attention · trustworthy & interpretable AI · LLM post-training
&nbsp;&nbsp;•&nbsp;&nbsp; 💬 **Ask me about** scanpath modeling, RAG faithfulness, and model merging

## 👁️ Visual attention & gaze

- **[SP_Gen](https://github.com/kmamine/SP_Gen)** — domain-adaptive generative model for scanpath prediction on paintings · *CBMI 2022*
- **[SSLArtScanpath](https://github.com/kmamine/SSLArtScanpath)** — self-supervised (Barlow Twins) scanpath prediction · *CVPR Workshops 2022*
- **[FDISS](https://github.com/kmamine/FDISS)** — Foveal Disc IoU Scanpath Score, a biologically grounded scanpath metric · `pip install fdiss`
- **[scanpath_nlp_metrics](https://github.com/kmamine/scanpath-semantic-similarity)** — compare scanpaths via VLM descriptions + the classical spatial & MultiMatch suite · `pip install scanpath_nlp_metrics`
- **[AVAtt](https://github.com/kmamine/AVAtt---Art-Visual-Attention)** — visual-attention dataset for paintings (scanpaths + saliency)

## 🧠 LLMs, reasoning & trustworthy AI

- **[ThinkBench](https://github.com/kmamine/ThinkProb)** — profiles LLM reasoning by turning Chain-of-Thought into Thought Graphs (non-generative) and scoring a 22-dimensional cognitive profile
- **[G-JEPA](https://github.com/kmamine/CVPR2026W-G-JEPA)** — energy-based JEPA for token-level multimodal grounding, evidence provenance, and hallucination detection
- **[HeReFaNMi](https://github.com/kmamine/herefanmi-redo)** — *Health-Related Fake News Mitigation*: tackles online health-news misinformation by retrieving evidence and triaging claims as trustworthy / doubtful / fake, with source validation · *EU NGI Search–funded*
- **[Enlighten-AI](https://github.com/kmamine/Enlighten-AI)** — a mental-health & life-coaching assistant grounded in Dr. K's (HealthyGamer.gg) video transcripts: citation-grounded RAG answering with timestamped sources, safety guardrails, and a red-team report

## 🛠️ LLM post-training & agentic systems

- **[llm-tuning-lab](https://github.com/kmamine/llm-tuning-lab)** — 11-skill toolkit for post-training LLMs as controlled experiments (SFT, LoRA/QLoRA, CPT, preference optimization, merging) with a significance backbone
- **[merge-corrected SFT distillation](https://github.com/kmamine/merge-corrected-sft-distillation-Qwen-Mythos-0.8B)** — reasoning distillation into Qwen3.5-0.8B with per-epoch, benchmark-gated merge correction · [model on 🤗 Hub](https://huggingface.co/Amine-CV/Qwen3.5-0.8B-Mythos-Distill)
- **[APEX](https://github.com/kmamine/APEX_New)** — agentic portrait editing where an MLLM plans & judges each edit and an ArcFace identity gate must agree before an edit is accepted

## 📄 Selected publications

- M. Tliba, **M. A. Kerkouri**, A. Chetouani, A. Bruno. *Self-Supervised Scanpath Prediction Framework for Painting Images.* **CVPR Workshops, 2022.** — [paper](https://openaccess.thecvf.com/content/CVPR2022W/Ego4D-EPIC/html/Tliba_Self_Supervised_Scanpath_Prediction_Framework_for_Painting_Images_CVPRW_2022_paper.html)
- **M. A. Kerkouri**, M. Tliba, A. Chetouani, A. Bruno. *A Domain-Adaptive Deep Learning Solution for Scanpath Prediction of Paintings.* **CBMI, 2022.** — [paper](https://doi.org/10.1145/3549555.3549597)

<sub>Full list on [Google Scholar](https://scholar.google.com/citations?user=vpWieeAAAAAJ&hl=en) and [ResearchGate](https://www.researchgate.net/profile/Mohamed-Kerkouri-2).</sub>

---

<div align="center">

<img alt="Dev quote" src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>

### 📊 GitHub activity

<img alt="Streak" src="https://streak-stats.demolab.com/?user=kmamine&theme=tokyonight&hide_border=true"/>

<!-- <img width="95%" alt="Contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=kmamine&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph"/> -->

</div>

<img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:1E90FF,100:0E4D92&height=120&section=footer"/>
