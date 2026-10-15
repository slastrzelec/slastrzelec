# Sławomir Strzelec

**AI/ML Engineer & Data Scientist** · Kraków, Poland

Chemistry and biophysics background (PhD in progress, AGH University of Kraków), now building machine-learning systems that are measured honestly: written specification before code, leakage-controlled evaluation, automated tests in CI, and limitations documented next to the results.

## Selected work

- **[Carbon Nanotubes RAG](https://github.com/slastrzelec/carbon-nanotubes-rag)** · Retrieval-augmented Q&A over 24 scientific papers. Hybrid dense + BM25 retrieval, answers only from retrieved passages with citations, faithfulness measured with RAGAs (about 0.80-0.82 on 14 domain questions). FastAPI, Streamlit, Docker, 31 tests in CI. [Live demo](https://carbon-nanotubes-raman-rag.streamlit.app/)
- **[ML Data Guard](https://github.com/slastrzelec/ml-data-guard)** · Library and CLI that validates data going into ML pipelines, benchmarked by fault injection: which drift and skew checks catch real faults, and at what false-alarm rate. 780 tests plus 104 hand-written mutants, published on PyPI.
- **[Scientific Research Agent](https://github.com/slastrzelec/research-agent-langchain)** · LangChain/LangGraph agent choosing between Wikipedia, ArXiv, PubMed and a safe calculator. Token budgets, per-session isolation, evaluation harness with separate dev and test splits, 95 tests that need no API key.
- **[SEM Nanostructure Classifier](https://github.com/slastrzelec/sem-nanostructure-classifier)** · Image classifier built to measure how much accuracy survives once near-duplicate leakage is controlled: macro-F1 0.956 on a group-aware split, calibrated confidence, negative results reported.
- **[Drug Solubility Predictor](https://github.com/slastrzelec/drug-solubility-prediction)** · XGBoost on Morgan fingerprints and RDKit descriptors: R² 0.91 on ESOL and 0.64 on 8,881 unseen AqSolDB compounds, with prediction intervals and an applicability-domain warning. FastAPI + Docker.

More projects are in the pinned repositories below and on the [portfolio site](https://slastrzelec.github.io/portfolio/).

## Stack

**AI/ML:** Python · PyTorch · scikit-learn · XGBoost · LangChain · LangGraph · RAG · FAISS
**Backend & MLOps:** FastAPI · Docker · GitHub Actions · pytest · PostgreSQL · AWS · GCP

## Contact

[LinkedIn](https://www.linkedin.com/in/s%C5%82awomir-strzelec) · [Portfolio](https://slastrzelec.github.io/portfolio/)
