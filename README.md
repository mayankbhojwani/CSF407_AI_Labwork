# 🤖 CS F407: Artificial Intelligence, Lab Solutions

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-neural%20nets-EE4C2C?logo=pytorch&logoColor=white)
![Prolog](https://img.shields.io/badge/Prolog-logic-8B0000)

From neurons to A* to Bayesian networks. Five labs from **CS F407 (Artificial Intelligence)** at BITS Pilani, K K Birla Goa Campus (Sem I, 2026–27). Each one is a notebook with the code, test results and written reflections.

## 🧪 What's inside

| | Lab | What it's about | Handout | Solution |
|---|---|---|---|---|
| 🧠 | **Neural Models** | How learning, depth, activations and output layers change what a network can do | `Neural Models.pdf` | `neural_models.ipynb` |
| 📦 | **Agents** | A goal-based agent finding its way around a warehouse | `Agents.pdf` | `agents.ipynb` |
| 🗺️ | **Search & A\*** | Getting from A to B without exploring the whole map | `Search.pdf` | `search.ipynb` |
| 🧩 | **Logical Reasoning** | Planning with propositional logic, plus a Prolog planner | `Logic.pdf` | `logic.ipynb`, `planner.pl` |
| 🎲 | **Bayesian Networks & Language Models** | Reasoning under uncertainty, then a tiny autoregressive text generator | `BN_lab.pdf` | `bn_lab.ipynb`, `generated_sentences.txt` |

Bonus: `llm_bn.ipynb` is the course demo on building and learning a Bayesian network (the classic Sprinkler example) with an LLM and `pgmpy`. It also needs `pgmpy` and `transformers`.

## 🚀 Run it yourself

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

For the Prolog cells in `logic.ipynb`, install [SWI-Prolog](https://www.swi-prolog.org/). Without it, paste `planner.pl` into [SWISH](https://swish.swi-prolog.org/) and it runs in your browser.

## 🤝 Use of LLMs

The labs required using an LLM (Claude). The code was generated from the prompts recorded in each notebook, then reviewed, modified and tested. Every notebook says which parts were generated and what was changed.
