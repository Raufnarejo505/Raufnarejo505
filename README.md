# Abdul Rauf

AI/ML engineer at Invisible Technologies. I work on fine-tuning, preference optimization, and
the data and evaluation work that decides whether a model improvement is real.

[Website](https://rauf-ai.vercel.app/) · [Hugging Face](https://huggingface.co/abdulrauf5121) · [Kaggle](https://www.kaggle.com/abdulraufghulamnabi) · [LinkedIn](https://www.linkedin.com/in/abdul-r-254241168/) · [Medium](https://medium.com/@raufpokemon00)

---

## Research

I'm interested in how cheaply a model's behaviour can be changed, and how often the evidence
that it changed is wrong. Four threads:

**Weight-space editing.** Whether closed-form, gradient-free edits to a checkpoint change what
the model represents, and, separately, whether they change what it does. In
[llm-directed-weight-space-programming](https://github.com/Raufnarejo505/llm-directed-weight-space-programming)
the representation geometry moves while the nearest-centroid decisions stay put. That gap is
the part I want to understand properly.

**Fine-tuning on a small budget.** QLoRA runs sized for one free GPU, with benchmark leakage
removed before training rather than confessed after.
[boxed](https://github.com/Raufnarejo505/boxed) drops the 7,345 GSM8K rows that ship inside
NuminaMath-CoT, because otherwise the post-training score measures recall of the test set.

**Tokenizer fairness.** Urdu costs noticeably more tokens than English for the same content,
which quietly shrinks the usable context and inflates the bill. I published a small
[token fairness report](https://huggingface.co/spaces/abdulrauf5121/urdu-token-fairness) and
the [parallel corpus](https://huggingface.co/datasets/abdulrauf5121/urdu-english-parallel)
behind it.

**Retrieval and access control.**
[PolicyPilot](https://github.com/Raufnarejo505/PolicyPilot-Permission-Aware-HR-Policy-Assistant)
treats authorization as part of retrieval instead of a filter applied afterwards, so the same
question abstains for an employee and answers for HR. Most of the difficulty sits in the
evaluation, not in the retrieval.

## Earlier work

[AgriMatch](https://github.com/Raufnarejo505/AgriMatch---A-Web-Based-Farmer-Buyer-Marketplace)
is a marketplace I built for my final year project: farmers list crops, buyers post
requirements, and the two sides negotiate over WebSockets with a tracked order lifecycle.
Next.js, FastAPI, PostgreSQL. It is the only project here that is a product rather than an
experiment, and it taught me more about state machines than any paper did.

## Writing

Occasional notes on experiments and evaluation on
[Medium](https://medium.com/@raufpokemon00).

## Contact

arauf.bscsses21@iba-suk.edu.pk

Open to research collaborations and ML engineering roles, particularly on evaluation,
interpretability, or multilingual work.
