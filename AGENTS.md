# AGENTS.md

## Code Philosophy

> Do one thing and do it well. Favor simplicity over cleverness. Write code for readability and long‑term maintainability.

**Principles**

1. **Single responsibility**

   * Each function/module should have one clear purpose.
   * Prefer composition over inheritance. Small, pure functions > giant God objects.
2. **Simplicity over engineered**

   * Choose the simplest solution that solves the problem today.
   * Avoid speculative abstractions, premature optimization, and unnecessary indirection.
3. **Readable & maintainable first**

   * Optimize for the next reader (your future self). Clear names, small files, consistent patterns.
   * Prefer explicit over magic. Comments explain *why*, not *what*.
4. **Fail loud, test early**

   * Surface errors fast with types, assertions, and tests. Keep error messages actionable.
5. **Consistency beats brilliance**

   * Follow the existing style and conventions of this repo. If you must diverge, document why.
