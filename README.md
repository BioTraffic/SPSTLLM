SPSTLLM: A statistical prior-enhanced spatio-temporal large language model for traffic prediction

SPSTLLM is an end-to-end framework that integrates prior-enhanced spatiotemporal representation learning with prompt-based large language models (LLMs) for robust and accurate time-series forecasting.

SPSTLLM/
│── data/                # Datasets (PeMS03, PeMS04, etc.)
│── models/              # Core model components
│   ├── tokenizer.py
│   ├── prior_module.py
│   ├── llm_adapter.py
│── configs/             # Experiment configurations
│── scripts/             # Training & evaluation scripts
│── utils/               # Utility functions
│── experiments/         # Logs and results
│── README.md

git clone https://github.com/yourname/SPSTLLM.git
cd SPSTLLM

conda create -n spstllm python=3.10
conda activate spstllm

pip install -r requirements.txt

Datasets
We evaluate SPSTLLM on four widely used traffic benchmarks:

PeMS03

PeMS04

PeMS07

PeMS08.
