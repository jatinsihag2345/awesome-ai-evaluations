# Contamination Detection in Frontier Models

Techniques for identifying training data memorization:
1. **Perplexity Probing:** Check if perplexity drops abnormally on benchmark prompt suffixes.
2. **Perturbation Testing:** Permute variable names and numeric constants; models that degrade sharply demonstrate overfitting.
3. **Canary String Searching:** Embed nonces (e.g. `BENCHMARK_CANARY_26b5c67b`) in problem instances.
