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

1. **Building large knowledge-based systems: Representation and inference in the Cyc project** `1989`  
   [[paper]](https://www.sciencedirect.com/science/article/pii/000437029390092P)

   *Douglas B. Lenat, R. V. Guha*

2. **EventKG: A Multilingual Event-Centric Temporal Knowledge Graph** `ESWC 2018`  
   [[paper]](https://arxiv.org/abs/1804.04526)

   *Simon Gottschalk, Elena Demidova*

3. **ASER: A Large-scale Eventuality Knowledge Graph** `WWW 2020`  
   [[paper]](https://dl.acm.org/doi/10.1145/3366423.3380107)

   *Hongming Zhang, Xin Liu, Haojie Pan, Yangqiu Song, Cane Wing-Ki Leung*

---

### 🧠 Intuitive Psychology

Commonsense about **mental states**, **emotions**, **intentions**, and **motivations**.

1. **SenticNet 6: Ensemble Application of Symbolic and Subsymbolic AI for Sentiment Analysis** `CIKM 2020`  
   [[paper]](https://www.sciencedirect.com/science/article/pii/S0950705120304262)

   *Erik Cambria, Yang Li, Frank Z. Xing, Soujanya Poria, Kenneth Kwok*

2. **Social Chemistry 101: Learning to Reason about Social and Moral Norms** `EMNLP 2020`  
   [[paper]](https://arxiv.org/abs/2011.00620)

   *Maxwell Forbes, Jena D. Hwang, Vered Shwartz, Maarten Sap, Yejin Choi*

3. **Moral Events: Extracting Moral Narratives from News** `EMNLP 2021`  
   [[paper]](https://aclanthology.org/2021.emnlp-main.350/)

   *Haotian Zhang, et al.*

4. **COKE: A Cognitive Knowledge Graph for Theory of Mind Reasoning** `ACL 2023`  
   [[paper]](https://aclanthology.org/2023.acl-long.815/)

   *Zhongyang Zhang, et al.*

---

### 🌍 General Commonsense  
*(Naive Physics + Intuitive Psychology)*

1. **ConceptNet 5.5: An Open Multilingual Graph of General Knowledge** `AAAI 2017`  
   [[paper]](https://doi.org/10.1609/AAAI.V31I1.11164)

   *Robyn Speer, Joshua Chin, Catherine Havasi*

2. **WebChild 2.0: Fine-Grained Commonsense Knowledge Distillation** `ACL 2017`  
   [[paper]](https://aclanthology.org/P17-4020.pdf)

   *Niket Tandon, Gerard de Melo, Gerhard Weikum*

3. **ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning** `AAAI 2019`  
   [[paper]](https://arxiv.org/abs/1811.00146)

   *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi*

4. **ATOMIC2020: On Symbolic and Neural Commonsense Knowledge Graphs** `AAAI 2020`  
   [[paper]](https://arxiv.org/abs/2010.05953)

   *Jena D. Hwang, Chandra Bhagavatula, Ronan Le Bras, Jeff Da, Keisuke Sakaguchi, Antoine Bosselut, Yejin Choi*

5. **GLUCOSE: Generalized and Contextualized Story Explanations** `EMNLP 2020`  
   [[paper]](https://aclanthology.org/2020.emnlp-main.341/)

   *Keisuke Sakaguchi, et al.*

6. **CSKG: A Unified Commonsense Knowledge Graph** `ACL 2021`  
   [[paper]](https://arxiv.org/abs/2106.08644)

   *Ali Emami, et al.*

7. **MickeyCorpus: A Multilingual Commonsense Reasoning Dataset** `ACL 2021`  
   [[paper]](https://aclanthology.org/2021.acl-long.296/)

   *Hongming Zhang, et al.*

---

### 💬 Dialogue & Social Interaction Commonsense

1. **SocialDial: A Benchmark for Socially-Aware Dialogue Systems** `ACL Findings 2023`  
   [[paper]](https://aclanthology.org/2023.findings-acl.403/)

   *Zhongyang Zhang, et al.*

2. **NormDial: A Bilingual Norm-Aware Dialogue Dataset** `EMNLP 2023`  
   [[paper]](https://aclanthology.org/2023.emnlp-main.504/)

   *Yifan Zhou, et al.*

---

## 📊 Benchmarks

This section summarizes **representative commonsense reasoning benchmarks** reviewed in our survey.

---

### 🧱 Naive Physics

1. **OpenBookQA: A New Challenge for Machine Reading Comprehension** `ACL 2018`  
   [[paper]](https://aclanthology.org/D18-1260/)

   *Peter Clark, Isaac Cowhey, Oren Etzioni, et al.*

2. **PIQA: Reasoning about Physical Commonsense in Natural Language** `AAAI 2020`  
   [[paper]](https://arxiv.org/abs/1911.11641)

   *Yonatan Bisk, Rowan Zellers, Ronan Le Bras, Jianfeng Gao, Yejin Choi*

3. **PROST: Physical Reasoning about Objects through Space and Time** `NAACL 2021`  
   [[paper]](https://aclanthology.org/2021.naacl-main.328/)

   *Ali Farhadi, et al.*

4. **NumerSense: Probing Numerical Commonsense Knowledge of Language Models** `ACL 2021`  
   [[paper]](https://aclanthology.org/2021.acl-long.383/)

   *Shivam Vashishtha, et al.*

---

### 🧠 Intuitive Psychology

1. **Social IQa: Commonsense Reasoning about Social Interactions** `EMNLP 2019`  
   [[paper]](https://aclanthology.org/D19-1454/)

   *Maarten Sap, Hannah Rashkin, Derek Chen, Ronan Le Bras, Yejin Choi*

2. **Story Commonsense: Inferring and Understanding Mental States in Stories** `EMNLP 2020`  
   [[paper]](https://aclanthology.org/2020.emnlp-main.333/)

   *Maarten Sap, et al.*

3. **ETHICS: An Ethical Benchmark for Language Models** `ACL 2021`  
   [[paper]](https://arxiv.org/abs/2008.02275)

   *Dan Hendrycks, et al.*

4. **BigToM: Benchmarking Theory of Mind Reasoning in Large Language Models** `arXiv 2023`  
   [[paper]](https://arxiv.org/abs/2305.09706)

   *Yifan Zhou, et al.*

---

### 💬 Social Commonsense Knowledge

1. **Cosmos QA: Machine Reading Comprehension with Contextual Commonsense Reasoning** `EMNLP 2019`  
   [[paper]](https://arxiv.org/abs/1909.00277)

   *Yejin Choi, et al.*

2. **Possible Stories: Evaluating Situated Commonsense Reasoning** `ACL 2021`  
   [[paper]](https://arxiv.org/abs/2104.05823)

   *Nasrin Mostafazadeh, et al.*

---

### ⏱ Temporal Commonsense Knowledge

1. **McTACO: A Dataset for Temporal Commonsense Reasoning** `EMNLP 2019`  
   [[paper]](https://aclanthology.org/D19-1331/)

   *Ben Zhou, et al.*

2. **TimeDial: Temporal Reasoning in Dialogues** `EMNLP 2021`  
   [[paper]](https://aclanthology.org/2021.emnlp-main.189/)

   *Qingyang Wu, et al.*

3. **TRAM: Temporal Reasoning for Large Language Models** `arXiv 2023`  
   [[paper]](https://arxiv.org/abs/2301.09020)

   *Yuxiang Zhou, et al.*

---

### 🔗 Causal Commonsense Knowledge

1. **COPA: Choice of Plausible Alternatives** `ACL 2011`  
   [[paper]](https://aclanthology.org/W11-0607/)

   *Michael Roemmele, et al.*

2. **Abductive NLI: Explaining Observations with Commonsense Reasoning** `ICLR 2020`  
   [[paper]](https://arxiv.org/abs/1907.11890)

   *Chandra Bhagavatula, et al.*

3. **Defeasible NLI: Evaluating Reasoning under Incomplete Information** `NAACL 2021`  
   [[paper]](https://aclanthology.org/2021.naacl-main.197/)

   *Rowan Zellers, et al.*

---

### 🌍 General Commonsense

1. **CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge** `NAACL 2019`  
   [[paper]](https://arxiv.org/abs/1811.00937)

   *Alon Talmor, Jonathan Berant*

2. **CommonsenseQA 2.0** `arXiv 2023`  
   [[paper]](https://arxiv.org/abs/2305.09706)

   *Yifan Zhou, et al.*

3. **SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference** `EMNLP 2018`  
   [[paper]](https://arxiv.org/abs/1808.05326)

   *Rowan Zellers, Yonatan Bisk, Ali Farhadi, Yejin Choi*

4. **HellaSwag: Can a Machine Really Finish Your Sentence?** `ACL 2019`  
   [[paper]](https://arxiv.org/abs/1905.07830)

   *Rowan Zellers, Ari Holtzman, Yonatan Bisk, Ali Farhadi, Yejin Choi*

5. **CODAH: An Adversarially-Authored Question Answering Dataset for Commonsense Reasoning** `RepEval 2019`  
   [[paper]](https://aclanthology.org/W19-2008/)

   *Michael Chen, Mike D’Arcy, Alisa Liu, Jared Fernandez, Doug Downey*

6. **ROCStories: A Corpus for Story Understanding** `NAACL 2016`  
   [[paper]](https://aclanthology.org/N16-1098/)

   *Nasrin Mostafazadeh, et al.*
   
## 🛠️ Methodologies

1. **Knowledge Editing for Large Language Models: A Survey** `arXiv 2023`  
   [[paper]](https://arxiv.org/abs/2310.16218)

   *Zeyu Jin, Zihan Zhang, Yikang Shen, Dan Roth*

2. **Commonsense Knowledge Aware Conversation Generation with Graph Attention** `IJCAI 2018`  
   [[paper]](https://www.ijcai.org/proceedings/2018/0643.pdf) [[code]](https://github.com/tuxchow/ccm)

   *Hao Zhou, Minlie Huang, Tianyang Zhang, Xiaoyan Zhu*

3. **Diverse and Informative Dialogue Generation with Context-Specific Commonsense Knowledge Awareness** `ACL 2020`  
   [[paper]](https://aclanthology.org/2020.acl-main.515/) [[code]](https://github.com/pku-sixing/ACL2020-ConKADI)

   *Sixing Wu, Ying Li, Dawei Zhang, Zhonghai Wu*

4. **Improving Empathetic Dialogue Generation by Dynamically Infusing Commonsense Knowledge** `ACL Findings 2023`  
   [[paper]](https://aclanthology.org/2023.findings-acl.498/) [[code]](https://github.com/Hanscal/DCKS)

   *Hancheng Cao, Wenqiang Lei, Tat-Seng Chua*

5. **Open-ended Commonsense Reasoning with Unrestricted Answer Scope** `EMNLP 2023`  
   [[paper]](https://arxiv.org/abs/2310.11672) [[code]](https://github.com/lingchen0331/KEEP)

   *Chen Ling, Yang Deng, Wenpeng Yin*

6. **Leveraging Explicit Reasoning for Inference Integration in Commonsense-Augmented Dialogue Models** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2406.09138) [[code]](https://github.com/sfillwo/DialCS-Reasoning)

   *Shengqiang Li, Fillipo Wirth, Yulan He*

7. **Dynamic Heterogeneous-Graph Reasoning with Language Models and Knowledge Representation Learning for Commonsense Question Answering** `ACL 2023`  
   [[paper]](https://aclanthology.org/2023.acl-long.785/)

   *Zheng Cai, Zhihao Fan, Xin Liu, Yangqiu Song*

---

## 🌟 Applications

1. **A Comprehensive Survey of Hallucination Mitigation Techniques in Large Language Models** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2401.01313)

   *Shuo Wang, Jieyu Zhao, Ming Zhou, Tat-Seng Chua*

2. **Right for Right Reasons: Large Language Models for Verifiable Commonsense Knowledge Graph Question Answering** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2403.01390)

   *Yue Zhang, Wenbo Su, Yansong Feng, Dong Yu*

3. **An Enhanced Prompt-Based LLM Reasoning Scheme via Knowledge Graph-Integrated Collaboration** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2402.04978)

   *Zixuan Wang, Hong Wang, Yefeng Zheng*

4. **Self-Alignment for Factuality: Mitigating Hallucinations in LLMs via Self-Evaluation** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2402.09267) [[code]](https://github.com/zhangxy-2019/Self-Alignment-for-Factuality)

   *Xinyu Zhang, Wenhao Liu, Xiaoxin Yin*

5. **DiffuCOMET: Contextual Commonsense Knowledge Diffusion** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2402.17011) [[code]](https://github.com/Silin159/DiffuCOMET)

   *Silin Liu, Yejin Choi*

---

## Future Directions

1. **Evaluating the External and Parametric Knowledge Fusion of Large Language Models** `arXiv 2024`  
   [[paper]](https://arxiv.org/abs/2405.19010)

   *Jiahao Wang, Yuxuan Wang, Lei Li*

2. **DeCoT: Debiasing Chain-of-Thought for Knowledge-Intensive Tasks in Large Language Models via Causal Intervention** `ACL 2024`  
   [[paper]](https://aclanthology.org/2024.acl-long.758/)

   *Zixuan Wang, Yansong Feng, Dong Yu*

3. **Cutting Off the Head Ends the Conflict: A Mechanism for Interpreting and Mitigating Knowledge Conflicts in Language Models** `ACL Findings 2024`  
   [[paper]](https://aclanthology.org/2024.findings-acl.70/)

   *Yuxuan Wang, Yansong Feng, Dong Yu*


## 📌 Reference

If you find our survey useful, please cite:

```bibtex
@article{xie2025commonsense,
  title={Commonsense Knowledge in Natural Language Processing: A Review of Applications and Challenges in the LLM Era},
  author={Xie, Yubo and Liu, Zonghui and Ma, Zongyang and Meng, Fanyuan and Xiao, Yan and Miao, Fahui and Pu, Pearl},
  journal={arXiv preprint},
  year={2025}
}

