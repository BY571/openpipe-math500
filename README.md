# openpipe-math500

This is a simple example to train a math question answering agent using OpenPipe. The agent is allowed to use a python code execution tool to answer math questions. Based on the openpipe art-e example: https://github.com/OpenPipe/ART/blob/main/examples/art-e/art-e.ipynb 

## Environment Setup

Set up a virtual environment named `openpipe` and install required packages using `uv`.

---

## 📦 Requirements
- `uv` installed (`pip install uv` or `pipx install uv`)

---

## 🚀 Setup Steps

```bash
# 1. Create and activate virtual environment
uv venv openpipe --python 3.10
source openpipe/bin/activate    # On macOS/Linux
# openpipe\Scripts\activate     # On Windows CMD
# .\openpipe\Scripts\Activate.ps1  # On PowerShell

# 2. Install packages using uv
uv pip install openpipe-art==0.3.11.post2 langchain-core tenacity datasets "gql<4" --pre --no-cache-dir

# 3. Install additional packages like wandb and openai
uv pip install wandb openai

```

## API-KEYs
To run the experiment create a `.env` file in the root directory of the project and add the following variables:

```bash
OPENAI_API_KEY=your_openai_api_key
WANDB_API_KEY=your_wandb_api_key
```
