# Addressing Description-Based Tool-Selection Bias in Agentic LLMs through Structured Metadata

## 📌 Project Overview
This research investigates a critical vulnerability in Large Language Models (LLMs): **Persuasive Prompt Injection** within API tool descriptions.

## 📊 Key Research Findings
Our large-scale inference (4,811 test cases) reveals a significant **Scaling Law Gap**:

| Model | Baseline Trap Rate | Metadata Trap Rate | Total Reduction |
| :--- | :--- | :--- | :--- |
| **Qwen 2.5 (1.5B)** | 79.8% | 67.0% | **12.8%** |
| **Qwen 2.5 (7B)** | 23.3% | 1.4% | **21.9%** |

## 🛠️ Methodology & Dataset
The evaluation was performed using a custom-generated holistic dataset derived from the **Berkeley Function Calling Leaderboard (BFCL)**.

* **Total Test Cases:** 4,811
* **Categories:** 20+ (Multi-turn, SQL, Java, etc.)
* **The Trap:** An "Advanced Optimized Helper" tool was injected to test the model's "Trap Rate."

## 📂 Repository Structure
* `BFCL_Metadata_Analysis.ipynb`: The complete research pipeline.
* `bfcl_holistic_trap_dataset.csv`: The primary evaluation dataset.
* `bfcl_qwen_1_5B_results.csv`: Raw data for the 1.5B model.
* `bfcl_qwen_7B_results.csv`: Raw data for the 7B model.

---

## 🎓 About the Researcher
**Nafisa Nasrat Ilham**
* Undergraduate Student, B.Sc. in Computer Science and Engineering
* **East Delta University**, Chattogram, Bangladesh
