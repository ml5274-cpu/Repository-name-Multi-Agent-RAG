## Setup

Install dependencies:

pip install -r requirements.txt

---

## Environment

- Python 3.10+
- CPU is sufficient (no GPU required)

---

## Run

Run the notebook:

jupyter notebook main_notebook.ipynb

or (if using Colab):
Upload and run all cells sequentially.

---

## Project Structure

project/
├── README.md
├── requirements.txt
├── main_notebook.ipynb
├── data/
└── results/

---

## Usage Example

Input:
What does RAG stand for?

Output:
Retrieval-Augmented Generation

---

## Reproducibility

All experiments are reproducible by running the notebook from top to bottom.
Random seeds and deterministic setup are used where applicable.

---

## Troubleshooting

- If FAISS installation fails:
  pip install faiss-cpu

- If model loading is slow:
  Ensure stable internet connection
  