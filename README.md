# DL Project

Deep Learning team project with two workstreams: Image Neural Network and Sentiment Analysis.

## Project structure

```text
image_neural_network/
    preprocess.ipynb
    neural_model.ipynb
sentiment_analysis/
    task_1.ipynb
    task_2.ipynb
    task_3.ipynb
data/
src/
models/
reports/
docs/
tests/
```

The five Jupyter notebooks are intentionally empty and use the Python 3 kernel.

- `data/`: local datasets and processed data.
- `src/`: reusable Python modules.
- `models/`: trained model artifacts.
- `reports/`: evaluation results and figures.
- `docs/`: project documentation.
- `tests/`: project tests.

## Setup

```bash
python -m venv .venv
# Activate the environment, then:
python -m pip install -r requirements.txt
jupyter lab
```

Add the chosen deep learning framework and project-specific dependencies when implementation starts.

## Collaboration

See [CONTRIBUTING.md](CONTRIBUTING.md). Keep datasets, credentials, model weights, and notebook outputs out of Git.
