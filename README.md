# Open LLM Leaderboard

Clone HuggingFaceH4 / open_llm_leaderboard for local options.

## Warning!!!

This only accepts json files for already evaluated models with [lm_evaluation_harness](https://github.com/EleutherAI/lm-evaluation-harness)
and generates a scoreboard (**locally**) with those values. 
This REPO is not for evaluating LM models.

## Details

- title: Open LLM Leaderboard
- emoji: 🏆
- colorFrom: green
- colorTo: indigo
- sdk: gradio
- sdk_version: 4.9.0
- app_file: app.py
- pinned: true
- license: apache-2.0
- duplicated_from: HuggingFaceH4/open_llm_leaderboard
- fullWidth: true
- space_ci: # See https://huggingface.co/spaces/Wauplin/gradio-space-ci
  - private: true
  - secrets:
    - HF_TOKEN
    - H4_TOKEN

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
