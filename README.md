# BBL In-Play Match Prediction

This repository contains the code and processed dataset for my Data Science Research Project Part B.

## Project Overview

This project predicts Big Bash League (BBL) match outcomes using partial first-innings information. The task is to predict whether the team batting first eventually wins the match.

The first innings is analysed at four fixed checkpoints:

- 6 overs
- 10 overs
- 15 overs
- 20 overs

The final models use cricket-aware features such as run rate, wickets, recent momentum, venue and season scoring patterns, resource-based information, and Elo-based team strength.

## Main Research Question

How accurately can BBL match outcomes be predicted from partial first-innings data at fixed checkpoints using machine-learning models?

## Repository Structure

```text
data/processed/
    bbl_model_dataset_with_elo.csv

notebooks/
    01_data_audit.ipynb
    05_valid_model_improvement_pipeline.ipynb

notebooks_archive/
    Earlier exploratory notebooks retained for project history.

figures/
    Final report figures.
