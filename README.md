# Udacity Agentic AI ND900: Prompting for Effective LLM Reasoning and Planning

Personal study repository for the **Agentic AI ND900 Nanodegree** section **Prompting for Effective LLM Reasoning and Planning**. It organizes the available course notebooks, exercises, and project materials.

This is a learner-maintained repository, not an official Udacity repository.

## Contents

- [`introduction-to-prompting-for-llm-reasoning-and-planning/`](./introduction-to-prompting-for-llm-reasoning-and-planning/) — Introduction and model-selection notebooks.
- [`lesson-1-role-based-prompting/`](./lesson-1-role-based-prompting/) — Role-based prompting exercises.
- [`lesson-2-chain-of-thought-and-react-prompting/`](./lesson-2-chain-of-thought-and-react-prompting/) — Chain-of-thought and ReAct prompting exercises.
- [`lesson-3-prompt-instruction-refinement/`](./lesson-3-prompt-instruction-refinement/) — Prompt and instruction refinement exercises.
- [`lesson-4-chaining-prompts-for-agentic-reasoning/`](./lesson-4-chaining-prompts-for-agentic-reasoning/) — Chaining prompts for agentic reasoning.
- [`lesson-5-implementing-llm-feedback-loops/`](./lesson-5-implementing-llm-feedback-loops/) — LLM feedback-loop exercises.
- [`project/`](./project/) — Course project materials.

Lessons generally include starter notebooks and, where provided, solution notebooks.

## Local setup

Python 3 and `venv` are required. From the repository root:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install ipykernel
python -m ipykernel install --user \
  --name udacity-agentic-ai-nd900 \
  --display-name "Python (Udacity Agentic AI ND900)"
```

In VS Code, open a notebook and select the **Python (Udacity Agentic AI ND900)** kernel. On Windows PowerShell, activate the environment with:

```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m pip install ipykernel
```

Some exercises call an OpenAI-compatible API and require course-provided credentials. Follow the relevant notebook instructions and keep API keys in environment variables or another local secret store; never commit credentials.

## Attribution and usage

Udacity course materials remain subject to the copyright and license terms in [`LICENSE.md`](./LICENSE.md). Retain the applicable notices and follow those terms and any separate permissions when using or sharing the materials. This repository is not affiliated with or endorsed by Udacity.
