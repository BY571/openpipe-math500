# openpipe-math500

## Environment Setup

Set up a virtual environment named `openpipe` and install required packages using `uv`.

---

## 📦 Requirements

- Python 3.8+
- `uv` installed (`pip install uv` or `pipx install uv`)

---

## 🚀 Setup Steps

```bash
# 1. Create and activate virtual environment
python -m venv openpipe
source openpipe/bin/activate    # On macOS/Linux
# openpipe\Scripts\activate     # On Windows CMD
# .\openpipe\Scripts\Activate.ps1  # On PowerShell

# 2. Install packages using uv
uv pip install openpipe-art==0.3.11.post2 langchain-core tenacity datasets "gql<4" --pre --no-cache-dir

```
