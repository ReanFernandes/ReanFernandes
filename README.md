# Hi, I'm Rean!

I'm a PhD candidate at TU Dortmund / Lamarr Institute, working with [JProf. Dr. Matthias Feurer](https://automl.cs.tu-dortmund.de/team/matthias-feurer/) and [Prof. Dr. Katharina Eggensperger](https://keggensperger.github.io/) on making LLM agents smarter, without touching the model weights.

Outside research, I'm a member of the [Young AI Leaders Dortmund Chapter](https://aiforgood.itu.int/speaker/rean-clive-fernandes/).

---

- **Automated prompt optimisation for LLM agents:** building frameworks that decompose agentic pipelines and iteratively refine prompts using environment feedback. Think evolutionary search, but driven by what the agent actually did wrong.
- **Automated agentic topology search:** figuring out how to automatically induce the right agent architecture for a given task, rather than hand-designing it every time.

---

## What I've worked on before

At the ML Lab in Freiburg (2024–2026), I built agentic LLM pipelines for autonomous tabular data augmentation and explored multi-armed bandit methods for feature engineering decisions. Before that I spent time building data distillation and benchmarking pipelines for LLM training on legal text, which eventually turned into a paper.

---

## Projects

**[Environment-Grounded Automated Prompt Optimization for LLM Game Agents](https://arxiv.org/abs/2606.17838)** ([code](https://github.com/ReanFernandes/rapoa))
An automated prompt optimisation framework for LLM agents that decomposes the observation-to-action pipeline into a descriptor and action agent, and iteratively refines each module's prompts via an LLM-driven evolutionary loop guided by environment returns. Evaluated on the BALROG benchmark: on PutNext, a multi-step coordination task where the baseline scores 0%, the framework reaches 72.5% using the same underlying model.

**[A Llama Walks into the Bar: LLM Fine-Tuning for Legal Reasoning](https://arxiv.org/abs/2504.04945)** ([code](https://github.com/ReanFernandes/bar-llama))
Fine-tuned Llama 2 7B (Q-LoRA) on US Bar Exam questions using automated data distillation via Llama 3 70B, achieving 3–4x performance gains over the base model. Includes full training and evaluation pipelines on HPC infrastructure.

**[Smart SLURM Job Handler](https://github.com/ReanFernandes/bar-llama/tree/master/SLURM-related-scripts)**
A Python + SQLite tool for automated job management on HPC SLURM clusters. Handles job queuing, retries, and status tracking without manual intervention. Built out of practical necessity while running large-scale experiments.

**[Model Performance Analysis Dashboard](https://github.com/ReanFernandes/model-accuracy-analyser)** ([live](https://model-accuracy-analyser-9rjrrn7fnmpnngw9jxx7re.streamlit.app/))
Interactive Streamlit app for visualising model performance metrics and learning curves. Built as a companion tool for the bar-llama paper.

**[MCQ Bias Analyzer](https://github.com/ReanFernandes/mcq-bias-analyzer-app)**
Streamlit dashboard for analysing answer selection biases in multiple-choice tasks. Compares predicted vs. ground truth label distributions and visualises confusion patterns. Used to analyse fine-tuning effects in the bar exam paper.

---

## Find me elsewhere

[Website](https://reanfds.com/about) · [Google Scholar](https://scholar.google.com/citations?user=VmAT7VkAAAAJ&hl=en) · [LinkedIn](https://www.linkedin.com/in/reanfernandes/) · [Email](mailto:rean.fernandes@tu-dortmund.de)
