## Experimental Setup
All runs were performed using the same model and task.
The only difference between the two conditions was the presence
of an example in the few-shot prompt.

## Evaluation Criteria
- Structural consistency
- Clarity
- Completeness
- Repeatability

## Observations
- Zero-shot outputs contained high informational detail but varied
  in structure and formatting across runs.
- The model independently selected list-based formatting in
  zero-shot responses without explicit instruction.
- Few-shot outputs consistently followed the narrative structure,
  length, and tone demonstrated in the example.
- A single example was sufficient to significantly reduce
  structural variability.
- Content relevance was preserved across both prompting strategies.

## Conclusion
Few-shot prompting improved output consistency and predictability
by implicitly providing a response template. Even a single example
was enough to guide structure and tone compared to zero-shot
prompting, which showed higher variability.
