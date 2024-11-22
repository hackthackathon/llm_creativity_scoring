## Description

This repository contains a Jupyter Notebook and Python scripts designed to evaluate project descriptions based on specific criteria using a Large Language Model (LLM). The evaluation focuses on assessing Innovation and Curiosity, aligned with predefined rubrics, and produces structured outputs for alignment, misalignment, and scoring.

The repository shows our attempts at automating the evaluation process for scalability.

## How It Works
Input: 
- projects.csv: Contains public project descriptions from devpost. The dataset was collected from Alex,N.
- rubric.csv: Contains the evaluation rubrics for Innovation and Curiosity.

Processing:
- The notebook processes the projects and criteria using LLM-based queries.
- Structured prompts are provided to provide the best possible response from the LLM.
- Outputs include alignment evidence, misalignment evidence, and scoring for each project-criterion pair.

Results:
- The folder will contain processed evaluations with columns for alignment, misalignment, and scores.

### Some Notes
The creativity notebook was created while running codespaces, so you might need additional package requirements and environment setups if you are running outside of codespaces.
- Navigate to your Github account and get the Github Personal Access Token https://github.com/settings/tokens
- Add an environment variable by running the following on bash `export GITHUB_TOKEN="<your-github-token-goes-here>"`.
- Ensure the necessary requirements needed are setup. Requirements differ per model used.

## Contributing
We welcome contributions to improve prompts or our automation attempts! Please fork the repository, create a feature branch, and submit a pull request.
