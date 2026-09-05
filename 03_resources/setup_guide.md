# Setup Guide — JAWNVION AI Engineer's Workbook

## Option A: Google Colab (Easiest — No Installation)

1. Click any "Open in Colab" button in the main README
2. Sign in with your Google account
3. Click **Runtime → Change runtime type → T4 GPU** (free tier)
4. Click **Run All** or run cells one at a time

That's it. No installation needed.

---

## Option B: Local Jupyter (Your Own Computer)

### Step 1 — Make sure Python is installed
Open a terminal and run:
```bash
python --version
```
You need Python 3.10 or higher. If not installed, download from python.org.

### Step 2 — Clone this repo
```bash
git clone https://github.com/petefenko-byte/jawnvion-ai-workbook.git
cd jawnvion-ai-workbook
```

### Step 3 — Install dependencies
```bash
pip install -r 03_resources/requirements.txt
```

### Step 4 — Launch Jupyter
```bash
jupyter notebook
```
Your browser will open. Navigate to `01_notebooks/` and open any chapter.

---

## Option C: Interactive Labs (No Python at All)

Open any `.html` file in `02_interactive_labs/` directly in Chrome, Firefox, or Safari.
No installation. No account. Just open and read.

---

## Tips

- **GPU matters for Ch06 (QLoRA) and Ch07 (DPO)** — use Colab with a T4 GPU for those chapters
- **Save your work in Colab** — File → Save a copy in Drive so you keep your notes
- **HuggingFace account** — Create a free account at huggingface.co for Ch05 and beyond
- **Stuck?** — Email peter@jawnvion.com

---

*JAWNVION — That AI Jawn.*
