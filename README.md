# lcc
This dataset contains 100 patent draft samples in the field of prefabricated construction technologies, designed specifically to test the ability of large language models (LLMs) to detect semantic, logical, and expression errors.

## Content

- **`passage`**: Patent draft text (~150-200 words each).
- **`errors`**: Three manually injected error types per passage:
  - **Logic errors**: Issues with construction logic or sequences.
  - **Semantic errors**: Misuse of technical terminology or incorrect material descriptions.
  - **Expression errors**: Ambiguous grammar, redundant expressions, or incomplete explanations.

## Intended Use

- Benchmarking accuracy (Precision), recall (Recall), and overall balanced accuracy (F1 score) for various LLMs in patent-text error detection tasks.
