---
language:
- en
license: mit
size_categories:
- 10K<n<100K
task_categories:
- token-classification
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: dev
    path: data/dev-*
  - split: test
    path: data/test-*
dataset_info:
  features:
  - name: annotations
    list:
    - name: result
      list:
      - name: from_name
        dtype: string
      - name: id
        dtype: string
      - name: to_name
        dtype: string
      - name: type
        dtype: string
      - name: value
        struct:
        - name: end
          dtype: int64
        - name: labels
          sequence: string
        - name: start
          dtype: int64
        - name: text
          dtype: string
  - name: meta
    struct:
    - name: source
      dtype: string
  - name: id
    dtype: string
  - name: data
    struct:
    - name: text
      dtype: string
  splits:
  - name: train
    num_bytes: 7672312
    num_examples: 10995
  - name: dev
    num_bytes: 815588
    num_examples: 1074
  - name: test
    num_bytes: 3376945
    num_examples: 4501
  download_size: 5441938
  dataset_size: 11864845
tags:
- legal
---

Dataset for training and evaluating Indian Legal Named Entity Recognition model.

# Paper details
[Named Entity Recognition in Indian court judgments](https://aclanthology.org/2022.nllp-1.15/)
[Arxiv](https://arxiv.org/abs/2211.03442)


### Label Scheme

<details>

<summary>View label scheme (14 labels for 1 components)</summary>

| ENTITY | BELONGS TO |
| --- | --- |
| `LAWYER` | PREAMBLE |
| `COURT` | PREAMBLE, JUDGEMENT |
| `JUDGE` | PREAMBLE, JUDGEMENT |
| `PETITIONER` | PREAMBLE, JUDGEMENT |
| `RESPONDENT` | PREAMBLE, JUDGEMENT |
| `CASE_NUMBER` | JUDGEMENT | 
| `GPE` | JUDGEMENT |
| `DATE` | JUDGEMENT |
| `ORG` | JUDGEMENT |
| `STATUTE` | JUDGEMENT |
| `WITNESS` | JUDGEMENT |
| `PRECEDENT` | JUDGEMENT |
| `PROVISION` | JUDGEMENT |
| `OTHER_PERSON` | JUDGEMENT |

</details>

## Author - Publication

```
@inproceedings{kalamkar-etal-2022-named,
    title = "Named Entity Recognition in {I}ndian court judgments",
    author = "Kalamkar, Prathamesh  and
      Agarwal, Astha  and
      Tiwari, Aman  and
      Gupta, Smita  and
      Karn, Saurabh  and
      Raghavan, Vivek",
    booktitle = "Proceedings of the Natural Legal Language Processing Workshop 2022",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.nllp-1.15",
    doi = "10.18653/v1/2022.nllp-1.15",
    pages = "184--193",
    abstract = "Identification of named entities from legal texts is an essential building block for developing other legal Artificial Intelligence applications. Named Entities in legal texts are slightly different and more fine-grained than commonly used named entities like Person, Organization, Location etc. In this paper, we introduce a new corpus of 46545 annotated legal named entities mapped to 14 legal entity types. The Baseline model for extracting legal named entities from judgment text is also developed.",
}
```