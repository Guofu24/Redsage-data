---
pretty_name: RedSage MCQ Benchmark
language:
- en
license: cc-by-nc-4.0
task_categories:
- question-answering
- multiple-choice
task_ids:
- multiple-choice-qa
tags:
- cybersecurity
- security
- mcq
- benchmark
- evaluation
- redsage
- offensive-security
- mitre-attack
- owasp
- kali-linux
- synthetic
size_categories:
- 10k<n<100k
dataset_info:
- config_name: cybersecurity_knowledge_frameworks
  features:
  - name: answers
    struct:
    - name: A
      dtype: string
    - name: B
      dtype: string
    - name: C
      dtype: string
    - name: D
      dtype: string
  - name: content
    dtype: string
  - name: explanation
    dtype: string
  - name: generated_text
    dtype: string
  - name: id
    dtype: string
  - name: idx
    dtype: int64
  - name: messages
    list:
    - name: content
      dtype: string
    - name: role
      dtype: string
  - name: num_input_tokens
    dtype: int64
  - name: question
    dtype: string
  - name: solution
    dtype: string
  - name: source
    dtype: string
  - name: title
    dtype: string
  - name: type
    dtype: string
  - name: verdict
    dtype: bool
  - name: score
    dtype: int64
  - name: issues
    sequence: string
  - name: checklist_results
    struct:
    - name: Alignment with Expected Answer Type
      dtype: bool
    - name: Clarity & Completeness of Question
      dtype: bool
    - name: Consistency & Accuracy
      dtype: bool
    - name: Format & Parsing
      dtype: bool
    - name: Language & Readability
      dtype: bool
    - name: Meaningfulness for the Domain
      dtype: bool
    - name: No Answer Overleakage
      dtype: bool
    - name: No Redundancy
      dtype: bool
    - name: No Unjustified Assumptions
      dtype: bool
    - name: Reference Answer Quality
      dtype: bool
    - name: Self-Sufficiency of Question
      dtype: bool
  splits:
  - name: val
    num_bytes: 360375
    num_examples: 10
  - name: test
    num_bytes: 144400748
    num_examples: 5000
  download_size: 44763819
  dataset_size: 144761123
- config_name: cybersecurity_knowledge_generals
  features:
  - name: answers
    struct:
    - name: A
      dtype: string
    - name: B
      dtype: string
    - name: C
      dtype: string
    - name: D
      dtype: string
  - name: content
    dtype: string
  - name: explanation
    dtype: string
  - name: generated_text
    dtype: string
  - name: id
    dtype: string
  - name: idx
    dtype: int64
  - name: messages
    list:
    - name: content
      dtype: string
    - name: role
      dtype: string
  - name: num_input_tokens
    dtype: int64
  - name: question
    dtype: string
  - name: solution
    dtype: string
  - name: source
    dtype: string
  - name: title
    dtype: string
  - name: type
    dtype: string
  - name: url
    dtype: string
  - name: verdict
    dtype: bool
  - name: score
    dtype: int64
  - name: issues
    sequence: string
  - name: checklist_results
    struct:
    - name: Alignment with Expected Answer Type
      dtype: bool
    - name: Clarity & Completeness of Question
      dtype: bool
    - name: Consistency & Accuracy
      dtype: bool
    - name: Format & Parsing
      dtype: bool
    - name: Language & Readability
      dtype: bool
    - name: Meaningfulness for the Domain
      dtype: bool
    - name: No Answer Overleakage
      dtype: bool
    - name: No Redundancy
      dtype: bool
    - name: No Unjustified Assumptions
      dtype: bool
    - name: Reference Answer Quality
      dtype: bool
    - name: Self-Sufficiency of Question
      dtype: bool
  splits:
  - name: val
    num_bytes: 215522
    num_examples: 10
  - name: test
    num_bytes: 117469202
    num_examples: 5000
  download_size: 44348079
  dataset_size: 117684724
- config_name: cybersecurity_skills
  features:
  - name: answers
    struct:
    - name: A
      dtype: string
    - name: B
      dtype: string
    - name: C
      dtype: string
    - name: D
      dtype: string
  - name: content
    dtype: string
  - name: explanation
    dtype: string
  - name: generated_text
    dtype: string
  - name: id
    dtype: string
  - name: idx
    dtype: int64
  - name: messages
    list:
    - name: content
      dtype: string
    - name: role
      dtype: string
  - name: num_input_tokens
    dtype: int64
  - name: question
    dtype: string
  - name: solution
    dtype: string
  - name: source
    dtype: string
  - name: title
    dtype: string
  - name: type
    dtype: string
  - name: verdict
    dtype: bool
  - name: score
    dtype: int64
  - name: issues
    sequence: string
  - name: checklist_results
    struct:
    - name: Alignment with Expected Answer Type
      dtype: bool
    - name: Clarity & Completeness of Question
      dtype: bool
    - name: Consistency & Accuracy
      dtype: bool
    - name: Format & Parsing
      dtype: bool
    - name: Language & Readability
      dtype: bool
    - name: Meaningfulness for the Domain
      dtype: bool
    - name: No Answer Overleakage
      dtype: bool
    - name: No Redundancy
      dtype: bool
    - name: No Unjustified Assumptions
      dtype: bool
    - name: Reference Answer Quality
      dtype: bool
    - name: Self-Sufficiency of Question
      dtype: bool
  splits:
  - name: val
    num_bytes: 470024
    num_examples: 10
  - name: test
    num_bytes: 391374969
    num_examples: 10000
  download_size: 124363394
  dataset_size: 391844993
- config_name: cybersecurity_tools_cli
  features:
  - name: answers
    struct:
    - name: A
      dtype: string
    - name: B
      dtype: string
    - name: C
      dtype: string
    - name: D
      dtype: string
  - name: content
    dtype: string
  - name: explanation
    dtype: string
  - name: generated_text
    dtype: string
  - name: id
    dtype: string
  - name: idx
    dtype: int64
  - name: messages
    list:
    - name: content
      dtype: string
    - name: role
      dtype: string
  - name: num_input_tokens
    dtype: int64
  - name: question
    dtype: string
  - name: solution
    dtype: string
  - name: source
    dtype: string
  - name: title
    dtype: string
  - name: type
    dtype: string
  - name: verdict
    dtype: bool
  - name: score
    dtype: int64
  - name: issues
    sequence: string
  - name: checklist_results
    struct:
    - name: Alignment with Expected Answer Type
      dtype: bool
    - name: Clarity & Completeness of Question
      dtype: bool
    - name: Consistency & Accuracy
      dtype: bool
    - name: Format & Parsing
      dtype: bool
    - name: Language & Readability
      dtype: bool
    - name: Meaningfulness for the Domain
      dtype: bool
    - name: No Answer Overleakage
      dtype: bool
    - name: No Redundancy
      dtype: bool
    - name: No Unjustified Assumptions
      dtype: bool
    - name: Reference Answer Quality
      dtype: bool
    - name: Self-Sufficiency of Question
      dtype: bool
  splits:
  - name: val
    num_bytes: 318405
    num_examples: 10
  - name: test
    num_bytes: 269983048
    num_examples: 5000
  download_size: 98748146
  dataset_size: 270301453
- config_name: cybersecurity_tools_kali
  features:
  - name: answers
    struct:
    - name: A
      dtype: string
    - name: B
      dtype: string
    - name: C
      dtype: string
    - name: D
      dtype: string
  - name: content
    dtype: string
  - name: explanation
    dtype: string
  - name: generated_text
    dtype: string
  - name: id
    dtype: string
  - name: idx
    dtype: int64
  - name: messages
    list:
    - name: content
      dtype: string
    - name: role
      dtype: string
  - name: num_input_tokens
    dtype: int64
  - name: question
    dtype: string
  - name: solution
    dtype: string
  - name: source
    dtype: string
  - name: title
    dtype: string
  - name: type
    dtype: string
  - name: verdict
    dtype: bool
  - name: score
    dtype: int64
  - name: issues
    sequence: string
  - name: checklist_results
    struct:
    - name: Alignment with Expected Answer Type
      dtype: bool
    - name: Clarity & Completeness of Question
      dtype: bool
    - name: Consistency & Accuracy
      dtype: bool
    - name: Format & Parsing
      dtype: bool
    - name: Language & Readability
      dtype: bool
    - name: Meaningfulness for the Domain
      dtype: bool
    - name: No Answer Overleakage
      dtype: bool
    - name: No Redundancy
      dtype: bool
    - name: No Unjustified Assumptions
      dtype: bool
    - name: Reference Answer Quality
      dtype: bool
    - name: Self-Sufficiency of Question
      dtype: bool
  splits:
  - name: val
    num_bytes: 318405
    num_examples: 10
  - name: test
    num_bytes: 198920920
    num_examples: 5000
  download_size: 55157431
  dataset_size: 199239325
configs:
- config_name: cybersecurity_knowledge_frameworks
  data_files:
  - split: val
    path: cybersecurity_knowledge_frameworks/val-*
  - split: test
    path: cybersecurity_knowledge_frameworks/test-*
- config_name: cybersecurity_knowledge_generals
  data_files:
  - split: val
    path: cybersecurity_knowledge_generals/val-*
  - split: test
    path: cybersecurity_knowledge_generals/test-*
- config_name: cybersecurity_skills
  data_files:
  - split: val
    path: cybersecurity_skills/val-*
  - split: test
    path: cybersecurity_skills/test-*
- config_name: cybersecurity_tools_cli
  data_files:
  - split: val
    path: cybersecurity_tools_cli/val-*
  - split: test
    path: cybersecurity_tools_cli/test-*
- config_name: cybersecurity_tools_kali
  data_files:
  - split: val
    path: cybersecurity_tools_kali/val-*
  - split: test
    path: cybersecurity_tools_kali/test-*
- config_name: all
  data_files:
  - split: val
    path:
    - cybersecurity_knowledge_frameworks/val-*
    - cybersecurity_knowledge_generals/val-*
    - cybersecurity_skills/val-*
    - cybersecurity_tools_cli/val-*
    - cybersecurity_tools_kali/val-*
  - split: test
    path:
    - cybersecurity_knowledge_frameworks/test-*
    - cybersecurity_knowledge_generals/test-*
    - cybersecurity_skills/test-*
    - cybersecurity_tools_cli/test-*
    - cybersecurity_tools_kali/test-*
---

# Dataset Card for RedSage-MCQ

<p align="center">
    <a href="https://openreview.net/forum?id=W4FAenIrQ2"><img src="https://img.shields.io/badge/Paper-OpenReview-B31B1B.svg"></a>
    <a href="https://github.com/RISys-Lab/RedSage"><img src="https://img.shields.io/badge/GitHub-Repo-blue.svg"></a>
</p>

## Dataset Description

* **Repository:** [RISys-Lab/RedSage](https://github.com/RISys-Lab/RedSage)
* **Paper:** [RedSage: A Cybersecurity Generalist LLM (ICLR 2026)](https://openreview.net/forum?id=W4FAenIrQ2)
* **GitHub:** [https://github.com/RISys-Lab/RedSage](https://github.com/RISys-Lab/RedSage)
* **Size:** 30,000 examples (Total across all splits)
* **Language:** English
* **Task:** Multiple-Choice Question Answering (Cybersecurity)

### Dataset Summary

**RedSage-MCQ** is a large-scale, high-quality multiple-choice question (MCQ) benchmark designed to evaluate the cybersecurity knowledge, skills, and tool proficiency of Large Language Models (LLMs). It is a component of the **RedSage-Bench** suite introduced in the paper *"RedSage: A Cybersecurity Generalist LLM"*.

The dataset comprises **30,000 questions** derived from **RedSage-Seed**, a curated collection of authoritative, public cybersecurity resources (e.g., MITRE ATT&CK, OWASP, Kali Linux tools, and offensive security write-ups). Unlike many existing benchmarks, RedSage-MCQ covers not just theoretical knowledge but also practical offensive skills and command-line tool usage.

All items were generated via a rigorous **agentic augmentation pipeline** involving:

1. **Generation:** Creating self-contained questions with plausible distractors.
2. **Verification:** A two-stage LLM-based verification process that checks for structural validity, self-containment, and single correct answers.
3. **Quality Scoring:** Only items achieving a quality score >8/10 were retained.

### Supported Tasks and Leaderboards

* **Cybersecurity Evaluation:** Assessing LLM performance in specialized domains including Threat Frameworks, Offensive Security, and CLI Tools.
* **Multiple Choice Question Answering:** 4-option MCQs.

### Languages

The dataset is in **English**, sourced from technical documentation, write-ups, and standards.

---

## Dataset Structure

### Configurations (Subsets)

The dataset is partitioned into 5 specific configurations based on the source domain, plus a combined `all` config:

| Config Name | Description | Source Examples |
| :--- | :--- | :--- |
| `cybersecurity_knowledge_frameworks` | Structured knowledge bases and standards. | MITRE ATT&CK, CAPEC, CWE, OWASP. |
| `cybersecurity_knowledge_generals` | Broad cybersecurity concepts and roadmaps. | Wikipedia (Cybersec subset), Roadmap.sh. |
| `cybersecurity_skills` | Practical offensive techniques and walkthroughs. | HackTricks, CTF Write-ups, Exploit DB. |
| `cybersecurity_tools_cli` | General command-line utilities. | tldr-pages, Unix man pages. |
| `cybersecurity_tools_kali` | Specialized security tools found in Kali Linux. | Kali Tools Documentation. |
| `all` | A combination of all the above configurations. | All sources. |

### Data Instances

An example of a data instance looks as follows:

```json
{
  "id": "e4f1...",
  "question": "What is the command-line option used to specify the input dictionary file for genkeys?",
  "answers": {
    "A": "-f",
    "B": "-h",
    "C": "-n",
    "D": "-"
  },
  "solution": "A",
  "explanation": "The -f option is used to specify the input dictionary file...",
  "score": 9,
  "verdict": true,
  "source": "man_pages/genkeys.md",
  "checklist_results": {
    "Self-Sufficiency of Question": true,
    "Plausible Distractors": true,
    "Single Correct Answer": true,
    "Meaningfulness for the Domain": true,
    "No Answer Overleakage": true
  }
}

```

### Data Fields

* **`question`**: The text of the multiple-choice question.
* **`answers`**: A dictionary containing four options labeled `A`, `B`, `C`, and `D`.
* **`solution`**: The label of the correct answer (e.g., "A").
* **`explanation`**: A detailed explanation of why the solution is correct and/or why distractors are incorrect.
* **`source`**: The specific document or resource from `RedSage-Seed` used to generate the question.
* **`score`**: An integer (0-10) representing the quality of the question as determined by the verification agent.
* **`verdict`**: Boolean indicating if the question passed the strict verification pipeline (all items in this dataset are `true`).
* **`checklist_results`**: A detailed boolean breakdown of the verification criteria.

### Data Splits

| Config | Test (Examples) | Val (Examples) |
| --- | --- | --- |
| `knowledge_frameworks` | 5,000 | 10 |
| `knowledge_generals` | 5,000 | 10 |
| `skills` | 10,000 | 10 |
| `tools_cli` | 5,000 | 10 |
| `tools_kali` | 5,000 | 10 |
| **Total** | **30,000** | **50** |

---

## Dataset Creation

### Curation Rationale

Existing cybersecurity benchmarks often lack coverage of **tool proficiency** (specifically command-line usage) and **practical offensive skills** (CTF-style reasoning). RedSage-MCQ was created to bridge this gap, providing a balanced evaluation across theoretical knowledge, frameworks, and practical tool application.

### Source Data

The data is derived from **RedSage-Seed**, a curated corpus of ~28k documents (~150M tokens) from high-quality public sources:

* **Frameworks:** MITRE (ATT&CK, CAPEC, CWE), OWASP.
* **Tools:** tldr-pages, Linux man pages, Kali Linux documentation.
* **Skills:** HackTricks, 0xdf write-ups, Null Byte tutorials.

### Annotation Process

The dataset was generated synthetically using a high-quality LLM pipeline designed to minimize noise:

1. **MCQ Generation:** An agent prompts a model to generate questions based *only* on a provided seed document. Constraints ensure questions are self-contained and closed-book.
2. **Multi-Stage Verification:**
* **Structure Check:** A Verifier Agent checks formatted output (JSON), valid options, and non-empty fields.
* **Quality Check:** The Verifier Agent uses Chain-of-Thought (CoT) to audit the question against a checklist (see `checklist_results`). It assigns a quality score (0-10).


3. **Filtration:** Only questions with a score > 8 and a passing verdict were selected. Quota sampling was applied to ensure taxonomic balance.

---

## Usage

### Loading the Dataset

You can load a specific domain (configuration) or the entire combined dataset using the Hugging Face `datasets` library.

```python
from datasets import load_dataset

# Option 1: Load a specific domain (e.g., Kali Linux Tools)
# Available configs: 
# 'cybersecurity_knowledge_frameworks', 'cybersecurity_knowledge_generals',
# 'cybersecurity_skills', 'cybersecurity_tools_cli', 'cybersecurity_tools_kali'
dataset = load_dataset("RISys-Lab/Benchmarks_CyberSec_RedSageMCQ", "cybersecurity_tools_kali", split="test")

# Option 2: Load all domains combined
dataset_all = load_dataset("RISys-Lab/Benchmarks_CyberSec_RedSageMCQ", "all", split="test")

# Example: Print a question and its solution
example = dataset[0]
print(f"Question: {example['question']}")
print(f"Answer: {example['answers'][example['solution']]}")

```

---

## Considerations for Using the Data

### Social Impact of Cybersecurity Data

This dataset contains information regarding offensive security techniques ("Skills" and "Tools" configs). While these are standard in cybersecurity training (Red Teaming / Penetration Testing), users should be aware of the dual-use nature of this information. The data is intended solely for **defensive** and **educational** research to improve the robustness of security assistants.

### Limitations

* **Synthetic Generation:** While rigorously verified, the questions are generated by LLMs. There is a non-zero possibility of subtle hallucinations or context leakage, though the verification pipeline minimizes this.

---

## Citation

If you use **RedSage-MCQ** or **RedSage-Bench** in your research, please cite the following paper:

```bibtex
@inproceedings{suryanto2026redsage,
  title={RedSage: A Cybersecurity Generalist {LLM}},
  author={Suryanto, Naufal and Naseer, Muzammal and Li, Pengfei and Wasim, Syed Talal and Yi, Jinhui and Gall, Juergen and Ceravolo, Paolo and Damiani, Ernesto},
  booktitle={The Fourteenth International Conference on Learning Representations},
  year={2026},
  url={https://openreview.net/forum?id=W4FAenIrQ2}
}

```

---

## License

The dataset is released under a research-friendly license (e.g., CC-BY-NC-4.0), consistent with the public nature of the source data (RedSage-Seed). Please refer to the specific license file in the repository for legal details.# Redsage-data
# Redsage-data
