# ARC-AGI-3 Notebook Agent

Competition page:
https://www.kaggle.com/competitions/arc-prize-2026-arc-agi-3

## Overview
This repository contains a practical notebook pipeline for ARC-AGI-3 that is compatible with Kaggle constraints and local development.

Main implementation file:
- `arc-prize-2026-arc-agi-3.ipynb`

## Notebook Pipeline
The notebook is organized into the following phases:
1. setup and shared imports
2. metadata overview and tag statistics
3. run context initialization and metrics logger
4. baseline policy simulation
5. offline generative policy
6. memory/reflection layer
7. aggregate evaluation tables
8. submission packaging

## Submission Output
Final submission schema:
- `row_id`
- `game_id`
- `end_of_game`
- `score`

## Contributors
- Anatolii Kandiuk
- Daniil Nakushnov