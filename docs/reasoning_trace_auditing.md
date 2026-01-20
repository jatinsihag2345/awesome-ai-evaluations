# Reasoning Trace Auditing for Thinking Models

Evaluating Chain-of-Thought (CoT) traces in reasoning models (o1, DeepSeek-R1, QwQ):
- **Circular Reasoning Detection:** Identify infinite loops in problem reformulation.
- **Overthinking Penalty:** Measure reasoning token length against ground truth complexity.
- **Premise Hallucination:** Verify that intermediate arithmetic steps follow logically from antecedents.
