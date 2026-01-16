Layer-5 (current)

What it monitors:
Token-level entropy derived from internal logits at each block

Where it acts:
Deep layers only (currently ≥3, empirically strongest at 4–5)

When it acts:
Only when entropy collapses below ε

How it acts:
Conservative residual re-centering (no parameter change, no decoding hack)

What it proves:
Transformer failure under semantic stress is representational overconfidence, not numerical instability
