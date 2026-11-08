<div align="center">

# Abdul Rauf

**Machine learning engineer — I build, evaluate and document LLM systems end-to-end.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-r-254241168/)
[![Medium](https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@raufpokemon00)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/rauf9903/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Raufnarejo505?tab=repositories)

</div>

---

I'm a Computer Science graduate working on **deep learning, model fine-tuning, inference,
and evaluation**. My interest is less in demo screenshots than in the parts that decide
whether a result is real: leak-free data splits, honest baselines, and tests that fail before
a GPU run wastes an hour.

Most repositories here follow the same pattern — pick a concrete claim, measure it, and
report the number even when it is unflattering.

## Featured work

| Project | What it is | Stack |
| --- | --- | --- |
| **[llm-directed-weight-space-programming](https://github.com/Raufnarejo505/llm-directed-weight-space-programming)** | Closed-form, gradient-free weight-space interventions on `snlucsb/netFound-small`. Shows that representation geometry moves while nearest-centroid decisions do not. | Python, PyTorch, safetensors |
| **[PolicyPilot](https://github.com/Raufnarejo505/PolicyPilot-Permission-Aware-HR-Policy-Assistant)** | Permission-aware HR policy assistant. Authorization is part of retrieval, not a post-processing step — the same question abstains for an Employee and answers for HR. | FastAPI, SQLite, Streamlit |
| **[boxed](https://github.com/Raufnarejo505/boxed)** | QLoRA fine-tune of Qwen2.5-1.5B on NuminaMath-CoT, with the 7,345 GSM8K rows stripped out before training so the benchmark measures reasoning, not recall. | PyTorch, TRL, PEFT |
| **[AgriMatch](https://github.com/Raufnarejo505/AgriMatch---A-Web-Based-Farmer-Buyer-Marketplace)** | Real-time farmer–buyer marketplace with WebSocket negotiation, offers and a tracked order lifecycle. Final Year Project. | Next.js, FastAPI, PostgreSQL |

## What I work with

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## How I approach a project

- **Baseline first.** A fine-tune without a pre-training number is an advertisement, not a result.
- **Check the split.** Training data that leaks into the eval set will produce a good number
  and teach you nothing.
- **Write the failure cases down.** Every repo here has a limitations section, because the
  boundary of a result matters as much as the result.
- **Pin the dependencies.** Library APIs move; a run that cannot be reproduced is not evidence.

## Currently

- Extending the weight-space programming work with more capabilities and larger checkpoints.
- Turning PolicyPilot's extractive baseline into a grounded generative model with a
  faithfulness evaluation.
- Writing short notes on ML experiments on [Medium](https://medium.com/@raufpokemon00).

## Get in touch

Open to research collaborations, ML engineering roles, and open-source work in model
interpretability or evaluation.

- 💼 [LinkedIn](https://www.linkedin.com/in/abdul-r-254241168/)
- ✍️ [Medium](https://medium.com/@raufpokemon00)
- 🧩 [LeetCode](https://leetcode.com/u/rauf9903/)

<div align="center">
<sub>Thanks for stopping by — pick a repo above and read the limitations section first.</sub>
</div>
