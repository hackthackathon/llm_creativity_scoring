## Description

This repo contains our attempts at automating out prompts to LLMs for scoring creativity.


### Some notes if you are using Github models in some notebooks
The creativity notebook was created while running codespaces, so you might need additional package requirements and environment setups if you are running outside of codespaces.

- Navigate to your Github account and get the Github Personal Access Token https://github.com/settings/tokens
- Add an environment variable by running the following on bash `export GITHUB_TOKEN="<your-github-token-goes-here>"`.
- Ensure the necessary requirements needed are setup. Requirements differ per model used.
