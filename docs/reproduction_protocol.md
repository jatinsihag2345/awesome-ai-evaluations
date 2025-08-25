# Benchmark Reproduction Protocol

To ensure evaluation rigor when assessing frontier LLMs:
1. **Container Isolation:** Always execute benchmarks in fresh Docker containers with deterministic seeding.
2. **Temperature Control:** Use temperature=0.0 for deterministic evaluation or sample 5 passes (pass@5) for creative code generation.
3. **Prompt Leakage Prevention:** Verify that eval splits are excluded from training pre-corpus via canary tokens.
