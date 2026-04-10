---
layout: page
title: cv
---

**[Download CV (PDF)](https://lfelipesv.github.io/assets/CV_Luiz_Felipe_Vecchietti.pdf)**  
*felipe.vecchietti at mpi-sp.org*

---

## General Information

I am currently a **Postdoctoral Researcher** at the **Max Planck Institute for Security and Privacy (MPI-SP), Bochum, Germany**, with Director [Meeyoung Cha](https://scholar.google.com/citations?user=iFlnVCoAAAAJ&hl=en).

## Research Interests

- **Reinforcement Learning** *(Credit Assignment, Exploration, Goal-conditioned RL, Continual Learning)*
- **Multi-Agent Systems** *(Collaborative, Collaborative-Competitive)*
- **Robotics** *(Foundation Models, End-to-End Control, Safety and Risks)*
- **AI for Science** *(Generative AI, Protein and Antibody Design, Drug Discovery, Graph Neural Networks, Diffusion Models)*

## Positions

**2024.11–Present** — *Max Planck Institute for Security and Privacy (MPI-SP), Germany*
Postdoctoral Researcher. Advisor: [Meeyoung Cha](https://scholar.google.com/citations?user=iFlnVCoAAAAJ&hl=en)

**2021.10–2024.9** — *Data Science Group, Institute for Basic Science (IBS), South Korea*
Senior Researcher. Advisor: [Meeyoung Cha](https://scholar.google.com/citations?user=iFlnVCoAAAAJ&hl=en)

**2021.3–2021.9** — *Mechanical Engineering Research Institute, KAIST, South Korea*
Postdoctoral Researcher. Advisor: Dongsoo Har

## Education

**2017–2021** — *Korea Advanced Institute of Science and Technology (KAIST)*
PhD in Green Transportation. Thesis: *Performance Enhancement in Multigoal Reinforcement Learning using Hindsight Experience Replay*. Advisor: Dongsoo Har

**2015–2017** — *Federal University of Rio de Janeiro (UFRJ)*
Master's Degree in Electrical Engineering. Dissertation: *Comparison between rule-based and data-driven NLP algorithms for Brazilian Portuguese speech synthesis*. Advisor: [Fernando Gil Vianna Resende Junior](http://pee.ufrj.br/prof/?ID=gil)

**2013** — *Korea Advanced Institute of Science and Technology (KAIST)*
Exchange Student, Electrical Engineering Department

**2009–2015** — *Federal University of Rio de Janeiro (UFRJ)*
Bachelor's Degree in Electronic and Computer Engineering

## Internships

**Summer 2013** — *Hyundai Motor Company, Namyang R&D Center*
Eco Vehicle Control System Development Team

## Publications

*The <sup>†</sup> symbol denotes a mentored student.*

### International Conferences

{% bibliography --query @inproceedings[venue_type=conference] %}

### Journals

{% bibliography --query @article %}

### Domestic Conferences and Workshops

{% bibliography --query @inproceedings[venue_type=workshop] %}

### Preprints

{% bibliography --query @misc %}

## Academic Services

**Reviewer — Journals:** IEEE Transactions on Cybernetics, IEEE Transactions on Games, IEEE Sensors, Frontiers in Robotics and AI

**Program Committee — Conferences:** AAAI ICWSM 2022, NeurIPS 2024, ACM WSDM 2025, ICLR 2025, AISTATS 2025, ICML 2025, NeurIPS 2025, AAAI 2026, ICLR 2026, ICML 2026

**Program Committee — Workshops:** ICML LatinX 2021, ICLR Reincarnating RL 2023, NeurIPS MLSB 2023, ICML ML4LMS 2024, NeurIPS MLSB 2024, NeurIPS MLSB 2025, ICLR MALGAI 2026

**Board Member:** Diversity Board Member at the Max Planck Institute for Security and Privacy (MPI-SP)

## Invited Talks

{% for talk in site.data.talks %}
**[{{ talk.key }}]** *{{ talk.title }}*
{{ talk.venue }}, {{ talk.date }}.{% if talk.note %} *{{ talk.note }}*{% endif %}

{% endfor %}

## Mentored Students

It is a great pleasure to work with very talented and hardworking students.

I am very thankful for the support and trust given from my advisors throughout my career: Prof. Fernando Gil Vianna Resende Junior (MsC), Prof. Dongsoo Har (PhD), and currently Prof. Ho Min Kim and Prof. Meeyoung Cha.

### Current

**Bryan Nathanael Wijaya** (2023–present) — MsC Candidate, KAIST.
Topic: Antigen-conditioned Antibody Design. *Published a first-author paper in mAbs.*

**Begench Hangeldiyev** (2022–present) — MsC Candidate, KAIST.
Topic: Antibody Sequence Design with Graph-Based Methods. *Published first paper on antibody design at KSC 2023.*

**Niklas Koeppe** (2025–present) — PhD Candidate, KAIST.
Topic: Continual Learning. *Submitted first author paper to ICML 2026.*

### Alumni

**Jiseon Kim** (2024–2025) — PhD Candidate, KAIST. Topic: Human-AI Alignment.
*Published first-author paper at ACL Findings.*

**Hyunkyu Jung** (2021–2025, now PhD Candidate at KAIST) — PhD Candidate, KAIST.
Topic: Protein-Protein Interactions using Equivariant Point Cloud Transformers.

**Anar Rzayev** (2022–2025, now Intern at ISTA) — CS Undergraduate, KAIST.
Topic: Antibody Structure Representation Learning.

**Sangmin Lee** (2023) — CS Undergraduate, KAIST.
Topic: AI-based methods for thermostable protein design.

**Maxim Krassimirov Mintchev** (2022, now Research Associate at TU Berlin) — ME Master's Candidate, KIT/KAIST (Double Degree).
Topic: Recommendation Systems for Logistics. *Successfully defended master's thesis.*

**Minji Lee** (2022, now PhD Candidate at Columbia University) — CS Undergraduate, KAIST.
Topic: Protein Optimization using Deep RL. *First-author paper at ICML 2024 (Spotlight). Papers at KCC and NeurIPS MLSB Workshop 2022.*

**Lucas Santiago Peixoto** (2022) — Computer Engineering Undergraduate, UFRJ.
Topic: Sentence-level Text Analysis using Transformers. *Successfully defended undergraduate thesis.*

**Matheus Tymburiba Elian** (2021–2022, now Faculty at UFMG) — Industrial Design PhD Candidate, University of Tsukuba.
Topic: Gender-Ambiguous Voice Agents. *Published first-author paper in Estudos em Design 2025.*

**Kien Hoang** (2021–2022, now MsC Candidate at EPFL) — Mathematics Undergraduate, KAIST.
Topic: Graph structure optimization with Deep RL.

**Sumit Mishra** (2020–2022, now PhD Candidate at KAIST) — Robotics Master's Candidate, KAIST.
Topic: Intelligent Transportation Systems. *First-author paper in IEEE Transactions on ITS.*

**Praveen Kumar Rajendran** (2020–2022, now CV Engineer at Neubility) — Future Vehicle Master's Candidate, KAIST.
Topic: Camera Pose Estimation. *First-author paper at ECCV IWDSC Workshop 2022.*

**Taeyoung Kim** (2019–2021, now PhD Candidate at KAIST) — Green Transportation Master's Candidate, KAIST.
Topic: Deep RL, Cooperative-Competitive Multi-agent Systems. *First-author review paper in IEEE Sensors Journal; first-author paper in PeerJ Computer Science.*

**Kyujin Choi** (2019–2020, now ML Engineer at KT) — Green Transportation Master's Candidate, KAIST.
Topic: Deep RL, Cooperative-Competitive Multi-agent Systems.

**Minah Seo** (2018–2019, now ML Engineer at KT) — Green Transportation Master's Candidate, KAIST.
Topic: Credit Assignment in Deep RL. *First-author paper in IEEE Access.*
