# RLVR (Reinforcement Learning with Verifiable Rewards)

Key principles for stable reward modeling in reasoning models:
- **Binary Zero-Tolerance Rewards:** Prefer discrete binary reward (1/0) based on deterministic checks rather than subjective heuristics.
- **AST Normalization:** Strip formatting variance, docstrings, and comments before evaluation.
- **Symbolic Equivalence:** Use symbolic algebra verifiers (e.g. SymPy) rather than floating point equality.
