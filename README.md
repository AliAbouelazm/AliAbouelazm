# Ali Abouelazm

I build machine learning systems, from model training and evaluation to the data pipelines and applications around them. My work spans language models, computer vision, and time-series prediction.

Currently a **Data Engineering co-op on Tesla's Fleet Analytics team**. Previously at **Cloudflare**. Studying **Data Engineering at Texas A&M University**, with expected graduation in **2028**.

[Portfolio](https://aliabouelazm.com) · [LinkedIn](https://www.linkedin.com/in/ali-abouelazm/) · [Email](mailto:aliazm419@gmail.com)

## Selected ML projects

### [Trace Check: agent trace inspection](https://trace-check.aliazm419.chatgpt.site)

Browser-based inspection of agent execution traces, with JSON import, a timeline, evidence-linked findings, redaction, and export. Uses rules by default; optional trained TF-IDF suggestions support manual review. Scores are uncalibrated and evaluation is development-only.

**Try:** [live demo](https://trace-check.aliazm419.chatgpt.site)

### [Drift: sentiment analysis and trend detection](https://github.com/AliAbouelazm/drift)

DistilBERT fine-tuning for three-class sentiment classification, connected to a FastAPI and React application for analyzing Reddit posts. Includes trend aggregation, anomaly detection, and token-level SHAP explanations.

**Inspect:** [training and model selection](https://github.com/AliAbouelazm/drift/blob/main/backend/app/model/train.py) · [evaluation](https://github.com/AliAbouelazm/drift/blob/main/backend/app/model/evaluate.py)

### [Isora: diffusion fine-tuning for image stylization](https://github.com/AliAbouelazm/isora)

Photo-to-isometric illustration pipeline combining Stable Diffusion 1.5, a LoRA adapter, and Canny ControlNet. Includes synthetic-data generation, an Apple Silicon-compatible training loop, and a FastAPI and React interface.

**Inspect:** [LoRA training implementation](https://github.com/AliAbouelazm/isora/blob/main/backend/app/model/train.py) · [setup and architecture](https://github.com/AliAbouelazm/isora#readme)

### [Foresight: sports trajectory prediction](https://github.com/AliAbouelazm/foresight)

Work in progress comparing temporal convolutional and sequence-to-sequence Transformer models for predicting player trajectories. Includes ADE/FDE evaluation in normalized image coordinates and Monte Carlo dropout for uncertainty estimates.

**Inspect:** [evaluation implementation](https://github.com/AliAbouelazm/foresight/blob/main/backend/app/model/evaluate.py) · [models and setup](https://github.com/AliAbouelazm/foresight#readme)

## Experience

- **Tesla, Fleet Analytics:** Data Engineering co-op, fall 2026.
- **Cloudflare, Marketing: AI Discoverability & Optimization Intern:** Built a Narrative Mismatch Engine using NLP and embedding-based analysis to identify gaps between AI-generated product descriptions and intended positioning, May-August 2026.
- **Texas A&M AgriLife:** Machine learning research on livestock biosensor data and AWS data pipelines.
- **TCG Digital Solutions:** Computer vision work on automated soccer highlight extraction, summer 2025.

## Research experiments

[Physics experiment](https://github.com/AliAbouelazm/physics-experiment): completed comparison of a frozen learned model, two-probe adaptation, and a simple response estimator, with recorded trajectories and failure analysis. In this experiment, adaptation improved predictions over the frozen model but remained worse than the simple estimator and worsened decisions. No learned-adaptation advantage was demonstrated.

## Tools

**Modeling:** Python, PyTorch, scikit-learn, XGBoost, Hugging Face Transformers, OpenCV  
**Data and systems:** SQL, pandas, NumPy, AWS, PostgreSQL, Docker, FastAPI  
**Applications:** TypeScript, JavaScript, React
