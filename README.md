# Multi-Agent RAG for Reliable Question Answering

## Overview
This project implements a Multi-Agent Retrieval-Augmented Generation (RAG) system to improve the reliability of question answering.

The system consists of:
- Planning Agent
- Retrieval Agent
- Reasoning Agent
- Verification Agent

## Methods Compared
- LLM-only
- Traditional RAG
- Multi-Agent RAG

## Evaluation Metrics
- Exact Match (EM)
- F1 Score
- Hallucination Rate
- Latency

## Setup

Install dependencies:

pip install -r requirements.txt

## Run

Open the notebook and run all cells:

jupyter notebook main_notebook.ipynb

## Reproducibility

All experiments are reproducible by running the notebook from top to bottom.

## Notes

This project uses a small curated dataset for demonstration purposes. The architecture can be extended to larger datasets such as Wikipedia.