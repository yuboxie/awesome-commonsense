<div align="center">
<h2>
Natural Language Processing with Commonsense Knowledge: A Survey
</h2>
</div>

This repository collects the **commonsense knowledge resources** summarized in our survey paper  
*Commonsense Knowledge in Natural Language Processing: A Review of Applications and Challenges in the LLM Era*.  
We will continue to update this repository.

---

## 📂 Knowledge Resources

Our survey **does NOT cover** lexical resources (e.g., WordNet) or factual KBs (e.g., Wikidata).  
Instead, we focus on **commonsense knowledge resources**, which encode implicit, everyday knowledge that humans typically take for granted.

---

### 🧱 Naive Physics

Commonsense about the **physical world**, including object properties, events, and causal/temporal regularities.

1. **OpenCyc** `Manual`  
   *239K concepts, 2.0M facts, English*  
   [[paper]](https://www.sciencedirect.com/science/article/pii/000437029390092P)  
   [[website]](https://www.cyc.com/platform/opencyc/)

2. **EventKG: A Multilingual Event-Centric Temporal Knowledge Graph** `ESWC 2018`  
   *690K events, 2.3M relations, Multilingual*  
   [[paper]](https://arxiv.org/abs/1804.04526)  
   [[website]](https://eventkg.l3s.uni-hannover.de/)

3. **ASER: A Large-scale Eventuality Knowledge Graph** `WWW 2020`  
   *194M nodes, 64M relations, English*  
   [[paper]](https://dl.acm.org/doi/10.1145/3366423.3380107)  
   [[website]](https://hkust-knowcomp.github.io/ASER/html/index.html)

---

### 🧠 Intuitive Psychology

Commonsense about **mental states**, **emotions**, **intentions**, and **motivations**.

1. **SenticNet**  
   *200K concepts, Multilingual*  
   [[paper]](https://www.sciencedirect.com/science/article/pii/S0950705120304262)  
   [[website]](https://sentic.net/)

2. **Social-Chem-101: Learning to Reason about Social and Moral Norms** `EMNLP 2020`  
   *292K rules, English*  
   [[paper]](https://arxiv.org/abs/2011.00620)  
   [[website]](https://github.com/allenai/social-chemistry-101)

3. **Moral Events**  
   *5,494 annotations, English*  
   [[paper]](https://aclanthology.org/2021.emnlp-main.350/)  

4. **COKE: Cognitive Knowledge Graph for Theory of Mind**  
   *62K nodes, 45K cognitive chains, English*  
   [[paper]](https://aclanthology.org/2023.acl-long.815/)  

---

### 🌍 General Commonsense  
*(Naive Physics + Intuitive Psychology)*

Resources covering **both physical and psychological commonsense**, often in graph or semi-structured form.

1. **ConceptNet 5.8** `AAAI 2017`  
   *8M nodes, 21M edges, Multilingual*  
   [[paper]](https://doi.org/10.1609/aaai.v31i1.11164)  
   [[website]](https://conceptnet.io/)

2. **WebChild 2.0: Fine-Grained Commonsense Knowledge Distillation** `ACL 2017`  
   *2M concepts, 18M assertions, English*  
   [[paper]](https://aclanthology.org/P17-4020.pdf)

3. **ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning** `AAAI 2019`  
   *309K nodes, 877K triples, English*  
   [[paper]](https://arxiv.org/abs/1811.00146)  
   [[website]](https://allenai.org/data/atomic)

4. **ATOMIC20<sub>20</sub>**  
   *1.33M tuples, 23 relations, English*  
   [[paper]](https://arxiv.org/abs/2010.05953)  
   [[code]](https://github.com/allenai/comet-atomic-2020)

5. **GLUCOSE: Generalized and Contextualized Story Explanations**  
   *670K annotations, English*  
   [[paper]](https://aclanthology.org/2020.emnlp-main.341/)  
   [[website]](https://github.com/ElementalCognition/glucose)

6. **CSKG: CommonSense Knowledge Graph**  
   *2.16M nodes, 6.0M edges, English*  
   [[paper]](https://arxiv.org/abs/2106.08644)  
   [[website]](https://github.com/usc-isi-i2/cskg)

7. **MickeyCorpus: Multilingual Commonsense Reasoning Dataset**  
   *561K sentences, 11 languages*  
   [[paper]](https://aclanthology.org/2021.acl-long.296/)  
   [[code]](https://github.com/HKUST-KnowComp/MickeyCorpus)

---

### 💬 Dialogue & Social Interaction Commonsense

Commonsense grounded in **dialogues**, **social norms**, and **interactional contexts**.

1. **SocialDial**  
   *6,433 dialogues, Chinese*  
   [[paper]](https://aclanthology.org/2023.findings-acl.403/)  

2. **NormDial**  
   *4,231 dialogues, Chinese & English*  
   [[paper]](https://aclanthology.org/2023.emnlp-main.504/)

## 📊 Benchmarks

This section summarizes **representative commonsense reasoning benchmarks** reviewed in our survey.  
Benchmarks are grouped by the **dominant type of commonsense knowledge** they evaluate.  
Many datasets probe multiple types; we list them under their **primary focus**, following Table 2.

---

### 🧱 Naive Physics

Benchmarks requiring reasoning about **physical objects**, **feasibility**, **spatial relations**, and **temporal regularities**.

1. **OpenBookQA** `ACL 2018`  
   *~6K questions, English*  
   [[paper]](https://aclanthology.org/D18-1260/)  
   Focuses on combining elementary science facts with physical commonsense reasoning.

2. **PIQA: Physical Interaction Question Answering** `AAAI 2020`  
   *16K questions, English*  
   [[paper]](https://arxiv.org/abs/1911.11641)  
   Evaluates physical interaction reasoning in everyday scenarios.

3. **PROST: Physical Reasoning about Objects through Space and Time**  
   *18,736 questions, English*  
   [[paper]](https://aclanthology.org/2021.naacl-main.328/)  
   Template-based probing benchmark for physical commonsense.

4. **NumerSense**  
   *13.6K examples, English*  
   [[paper]](https://aclanthology.org/2021.acl-long.383/)  
   Tests numerical commonsense consistency (e.g., typical quantities).

---

### 🧠 Intuitive Psychology

Benchmarks emphasizing **mental states**, **intentions**, **emotions**, and **social reasoning**.

1. **Social IQa** `EMNLP 2019`  
   *38K questions, English*  
   [[paper]](https://aclanthology.org/D19-1454/)  
   Reasoning about motivations, reactions, and social outcomes.

2. **Story Commonsense**  
   *15K stories, 300K annotations, English*  
   [[paper]](https://aclanthology.org/2020.emnlp-main.333/)  
   Large-scale mental-state annotations grounded in narratives.

3. **ETHICS**  
   *Multiple sub-datasets, English*  
   [[paper]](https://arxiv.org/abs/2008.02275)  
   Evaluates ethical and moral commonsense across normative frameworks.

4. **BigToM**  
   *5,000 procedurally generated evaluations, English*  
   [[paper]](https://arxiv.org/abs/2305.09706)  
   A Theory-of-Mind benchmark with human-rated reliability.

---

### 💬 Social Commonsense Knowledge

Benchmarks focusing on **social norms**, **dialogue**, and **interpersonal reasoning**.

1. **Cosmos QA**  
   *35,588 questions, English*  
   [[paper]](https://arxiv.org/abs/1909.00277)  
   Contextual commonsense reasoning from everyday narratives.

2. **Possible Stories**  
   *4,533 questions, English*  
   [[paper]](https://arxiv.org/abs/2104.05823)  
   Outcome reasoning over plausible story continuations.

3. **SocialDial**  
   *Dialogue-based evaluation, Chinese*  
   [[paper]](https://aclanthology.org/2023.findings-acl.403/)  
   Social-norm-aware dialogue reasoning benchmark.

---

### ⏱ Temporal Commonsense Knowledge

Benchmarks requiring understanding of **event order**, **duration**, **frequency**, and **temporal causality**.

1. **McTACO: Multiple Choice Temporal Commonsense**  
   *Temporal QA, English*  
   [[paper]](https://aclanthology.org/D19-1331/)  
   Evaluates duration, ordering, and frequency reasoning.

2. **TimeDial**  
   *~1,100 dialogues, English*  
   [[paper]](https://aclanthology.org/2021.emnlp-main.189/)  
   Temporal reasoning in multi-turn dialogue contexts.

3. **TRAM: Temporal Reasoning for Large Language Models**  
   *526K questions, English*  
   [[paper]](https://arxiv.org/abs/2301.09020)  
   Large-scale temporal stress test across 10 task families.

---

### 🔗 Causal Commonsense Knowledge

Benchmarks focusing on **cause–effect reasoning**, **counterfactuals**, and **abductive inference**.

1. **COPA: Choice of Plausible Alternatives**  
   *1,000 examples, English*  
   [[paper]](https://aclanthology.org/W11-0607/)  
   Binary causal reasoning with carefully controlled distractors.

2. **Triangle-COPA**  
   *100 examples, English (multimodal)*  
   [[paper]](https://aclanthology.org/2022.naacl-main.131/)  
   Extends COPA with video-based causal and emotional reasoning.

3. **XCOPA**  
   *11 languages*  
   [[paper]](https://aclanthology.org/2020.emnlp-main.531/)  
   Multilingual causal commonsense benchmark.

4. **Abductive NLI (ART)**  
   *20K contexts, 200K hypotheses, English*  
   [[paper]](https://arxiv.org/abs/1907.11890)  
   Tests explanation-based commonsense inference.

5. **Defeasible NLI**  
   *Classification + generation tasks, English*  
   [[paper]](https://aclanthology.org/2021.naacl-main.197/)  
   Evaluates how inferences change with new contextual information.

---

### 🌍 General Commonsense

Benchmarks probing **mixed commonsense phenomena** across physical, social, and temporal dimensions.

1. **CommonsenseQA**  
   *12,247 questions, English*  
   [[paper]](https://arxiv.org/abs/1811.00937)  
   ConceptNet-derived multiple-choice QA.

2. **CommonsenseQA 2.0**  
   *14,343 yes/no questions, English*  
   [[paper]](https://arxiv.org/abs/2305.09706)  
   Gamified data creation with strong human–model gaps.

3. **SWAG**  
   *113K examples, English*  
   [[paper]](https://arxiv.org/abs/1808.05326)  
   Adversarially filtered situation completion benchmark.

4. **HellaSwag**  
   *70K examples, English*  
   [[paper]](https://arxiv.org/abs/1905.07830)  
   A harder, more diverse continuation benchmark.

5. **CODAH**  
   *2,801 adversarial questions, English*  
   [[paper]](https://aclanthology.org/W19-2008/)  
   Targets commonsense failure modes via human adversarial authoring.

6. **ROCStories**  
   *50K stories, English*  
   [[paper]](https://aclanthology.org/N16-1098/)  
   Narrative causal and temporal reasoning via story completion.


---

## 📌 Reference

If you find our survey useful, please cite:

```bibtex
@article{xie2025commonsense,
  title={Commonsense Knowledge in Natural Language Processing: A Review of Applications and Challenges in the LLM Era},
  author={Xie, Yubo and Liu, Zonghui and Ma, Zongyang and Meng, Fanyuan and Xiao, Yan and Miao, Fahui and Pu, Pearl},
  journal={arXiv preprint},
  year={2025}
}
