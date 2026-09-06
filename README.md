# KTP Stability Analysis
[![Notebook checks](https://github.com/oyetzmedic/ktp-stability-analysis/actions/workflows/notebooks.yml/badge.svg)](https://github.com/oyetzmedic/ktp-stability-analysis/actions/workflows/notebooks.yml)

This repository contains a concise pre-interview data analysis submission for a KTP Associate exercise based on accelerated pharmaceutical stability testing. The analysis compares two prototype formulations, explores degradation behaviour under temperature, humidity and time stress, and uses simple modelling to support a transparent development recommendation.

This repository contains a short Jupyter notebook set responding to the six questions in the stability analysis exercise.

## Repository contents

- `notebooks/ktp_executive_summary.ipynb`
- `notebooks/ktp_question1_dataset_features.ipynb`
- `notebooks/ktp_question2_insights.ipynb`
- `notebooks/ktp_question3_degradation_factors.ipynb`
- `notebooks/ktp_question4_relative_performance.ipynb`
- `notebooks/ktp_question5_modelling_insights.ipynb`
- `notebooks/ktp_question6_limitations_and_improvements.ipynb`
- `requirements.txt`

## Project summary

The notebooks analyse accelerated stability data for two prototype formulations, A014 and B025. The work focuses on dataset structure, exploratory trends, degradation drivers, formulation comparison, simple modelling, and study-design limitations.

The analysis is intentionally compact and aims to demonstrate analytical reasoning, coding clarity, and communication rather than an exhaustive pharmaceutical stability package.

## How to run

### 1. Create and activate an environment

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Then open the notebooks in the `notebooks/` folder in the recommended order below.

## Recommended reading order

### Start here
`ktp_executive_summary.ipynb`

Provides a one-notebook overview of the study, the major findings, the formulation recommendation, and the next-step priorities.

### Question 1
`ktp_question1_dataset_features.ipynb`

Covers the structure and quality of the dataset.

### Question 2
`ktp_question2_insights.ipynb`

Summarises the main visual and quantitative trends in the data.

### Question 3
`ktp_question3_degradation_factors.ipynb`

Examines which variables appear to drive degradation.

### Question 4
`ktp_question4_relative_performance.ipynb`

Compares the relative stability of the two formulations.

### Question 5
`ktp_question5_modelling_insights.ipynb`

Shows what additional value simple modelling adds.

### Question 6
`ktp_question6_limitations_and_improvements.ipynb`

Discusses dataset limitations and proposes improvements for future studies.

## Submission note

The original dataset itself is not included here, in line with the exercise instructions. Each notebook reconstructs the supplied extracted values directly in code so the analysis can still be run end-to-end.

