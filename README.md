## Model Configuration

- Model: GPT-4–class LLM
- Interaction mode: Chat-based interaction
- Temperature: default
- Top-p: default

# Zero-shot vs Few-shot Prompting Case Study (Platypus Domain)

This repository compares zero-shot and few-shot prompting
to evaluate how example-based guidance affects output
structure, clarity, and consistency.

The same task and input domain (platypus biology) were used
to isolate the effect of including an example in the prompt.

## Goal
Assess how few-shot prompting influences response structure
and repeatability compared to zero-shot prompting.

## Method
- Same task
- Same model
- Zero-shot vs few-shot prompts
- 3 runs per prompt
- Qualitative comparison

## Structure
- `prompts/` – zero-shot and few-shot prompts
- `results/` – real model outputs
- `evaluation.md` – analysis and conclusion

## Key Result
Few-shot prompting significantly reduced structural variability
by implicitly guiding the model’s response pattern, while
zero-shot prompting produced more diverse but less predictable
outputs.

