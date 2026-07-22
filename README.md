i'ts bascially a small Stockfish fork that adds an optional root-level “Aggressive Mode” rather than changing the core search or NNUE evaluation.

When enabled, it forces MultiPV analysis of several candidate moves and reranks them using handcrafted signals such as material investment, king pressure, piece activity, and avoidance of simplifying exchanges.



The current implementation may sacrifice substantial objective evaluation for style, particularly because its default admissibility threshold is based on an absolute −3.00 floor instead of a consistently relative evaluation loss.
