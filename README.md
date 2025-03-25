# Instruction-Fine-Tuned Language Model for Indian Legal Domain

This repository contains the resources for building an instruction fine-tuned language model specifically for the Indian legal domain. It includes datasets, pre-trained models, and other relevant resources that can be useful in training / fine-tuning a language model to understand and generate legal text in the context of Indian law.

## Resources

### Legal Domain-specific Tasks

#### Evaluation Benchmark
1. [**IL-TUR**](https://aclanthology.org/2024.acl-long.618/) - Dataset: [IL-TUR](https://huggingface.co/datasets/Exploration-Lab/IL-TUR) - Language(s): English

#### Task 1: Summarization
##### Monolingual Summarization (English-to-English)
1. [**Legal Case Document Summarization: Extractive and Abstractive Methods and their Evaluation**](https://aclanthology.org/2022.aacl-main.77/) - Dataset: [IN-Abs](https://zenodo.org/records/7152317#.Yz6mJ9JByC0) - Language(s): English
##### Cross-lingual Summarization (English-to-Hindi)
1. [**MILDSum: A Novel Benchmark Dataset for Multilingual Summarization of Indian Legal Case Judgments**](https://aclanthology.org/2023.emnlp-main.321/) - Dataset: [MILDSum](https://github.com/Law-AI/MILDSum/tree/main) - Language(s): English, Hindi

#### Task 2: Semantic Segmentation (Rhetorical Role Labeling)
1. [**Identification of Rhetorical Roles of Sentences in Indian Legal Judgments**](https://arxiv.org/pdf/1911.05405) - Dataset: [Link](https://github.com/Law-AI/semantic-segmentation/tree/master) - Language(s): English
2. [**Semantic Segmentation of Legal Documents via Rhetorical Roles**](https://aclanthology.org/2022.nllp-1.13/) - Dataset: [Link](https://github.com/Exploration-Lab/Rhetorical-Roles) - Language(s): English
3. [**LegalSeg: Unlocking the Structure of Indian Legal Judgments Through Rhetorical Role Classification**](https://arxiv.org/abs/2502.05836) - Dataset: [LegalSeg](https://github.com/ShubhamKumarNigam/LegalSeg) - Language(s): English 


#### Task 3: Court Judgment Prediction and Explanation 
1. [**NYAYAANUMANA and INLEGALLLAMA: The Largest Indian Legal Judgment Prediction Dataset and Specialized Language Model for Enhanced Decision Analysis**](https://aclanthology.org/2025.coling-main.738.pdf) - Dataset: [Link](https://github.com/ShubhamKumarNigam/NyayaAnumana-and-INLegalLlama)
2. [**Legal Judgment Reimagined: PredEx and the Rise of Intelligent AI Interpretation in Indian Courts**](https://aclanthology.org/2024.findings-acl.255.pdf) - Dataset: [Link](https://github.com/ShubhamKumarNigam/PredEx)
3. [**LLMs – the Good, the Bad or the Indispensable?: A Use Case on Legal Statute Prediction and Legal Judgment Prediction on Indian Court Cases**](https://aclanthology.org/2023.findings-emnlp.831.pdf) - Dataset: [Link](https://github.com/somsubhra04/LLM_Legal_Prompt_Generation/)

#### Task 4: Bail Prediction


#### Task 5: Legal Statute Identification
1. [**LLMs – the Good, the Bad or the Indispensable?: A Use Case on Legal Statute Prediction and Legal Judgment Prediction on Indian Court Cases**](https://aclanthology.org/2023.findings-emnlp.831.pdf) - Dataset: [Link](https://github.com/somsubhra04/LLM_Legal_Prompt_Generation/)

#### Task 6: Prior Case Retrieval


#### Task 7: Legal Named Entity Recognition


#### Task 8: Legal Text Translation 


### Research Papers

#### Legal domain specific
1. **LawInstruct** - [LawInstruct paper and FLawN-T5](https://arxiv.org/pdf/2404.02127)
2. **Aalap Model** - [AI Assistant for Legal & Paralegal Functions in India](https://arxiv.org/abs/2402.01758)
3. **Pile of Law** - [256GB Open-Source Legal Dataset](https://arxiv.org/pdf/2207.00220)

#### Other works
1. **IFT in BERT** - [Instruction Fine-Tuning using modernBERT](https://arxiv.org/pdf/2502.03793)
2. **Framework for Adapting General LLM to Finance Domain** - [Domain-adaptive Post-training for Financial LLMs](https://arxiv.org/pdf/2501.04961)
3. **Tulu 3** - [Tulu 3: Pushing Frontiers in Open Language Model Post-Training](https://arxiv.org/abs/2411.15124)
4. **How Useful is CPT** - [How Useful is Continued Pre-Training](https://aclanthology.org/2024.repl4nlp-1.9.pdf)
5. **CPT of LLMs** - [Continual Pre-Training of Large Language Models](https://arxiv.org/pdf/2308.04014)
6. **Instruct-SkillMix** - [Pipeline for LLM Instruction Tuning](https://arxiv.org/pdf/2408.14774)

### Other Resources

1. **General Reading on Post-Training** - [Awesome-LLM-Post-training](https://github.com/mbzuai-oryx/Awesome-LLM-Post-training?tab=readme-ov-file#survey)
3. **Indian Legal Glossary** - [Indian Legal Glossary](https://legislative.gov.in/legal-glossary/)

## License
The resources in this repository are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. To view a copy of this license, visit [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
