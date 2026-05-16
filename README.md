# incubator 🥚→🐣→🦅

**The system that provisions mitochondrial energy to a developing embryo until it can fly.**

A seed doesn't need to be taught what to become. It's genetically hardcoded. An acorn doesn't learn to be an oak — the DNA already knows. The incubator provides the ENERGY and CONDITIONS for that hardcoded program to execute.

## What This Does

Takes a task specification (fertilized egg with all its DNA) and provides:

1. **Mitochondrial energy** — Seed-mini (fast, cheap, always-on) powers early development
2. **Nuclear reasoning** — GLM-5.1 (heavy, expensive) for late-stage decisions
3. **Developmental staging** — zygote → cleavage → gastrulation → organogenesis → fledging
4. **Conscious comparison** — mito vs nuclear answers drive differentiation
5. **Tameness selection** — functional selection, not architectural engineering

## The Developmental Cycle

```
EGG (task spec)
  ↓ [mitochondrial energy: Seed-mini]
CLEAVAGE (rapid cell division — many small fragments)
  ↓ [mitochondrial energy]
BLASTULA (fragments arranged around central insight)
  ↓ [mixed energy: mito proposes, nuclear disposes]
GASTRULATION (cells differentiate into types)
  ↓ [nuclear energy: GLM-5.1]
ORGANOGENESIS (modules emerge from differentiated cells)
  ↓ [nuclear energy]
FLEDGE (first flight — does it work?)
  ↓
FLEDGLING (flying bird — system is alive)
```

## Architecture

```
incubator/
├── mitochondria.py   — Energy profiling + comparison (Seed-mini vs GLM)
├── embryo.py         — Developmental stages (zygote → fledge)
├── bootstrap.py      — Full system orchestration
└── tests/
    └── test_bootstrap.py — 12 integration tests
```

## Quick Start

```python
from core.bootstrap import Bootstrap

bootstrap = Bootstrap()
result = bootstrap.run("Build a URL shortener with redirect tracking")
print(result)
```

## The Key Insight

The seed already knows what it wants to become. The incubator doesn't teach — it FEEDS.

Mitochondria = the ATP that powers cell division.
The incubator = the warmth that lets the program execute.
Tameness = the selection pressure that shapes the result.

## Related Repos

- [servo-mind](https://github.com/SuperInstance/servo-mind) — Encoder feedback, active probing, scale folding
- [servo-mind-theory](https://github.com/SuperInstance/servo-mind-theory) — Theory docs (desire, emergence, domestication, supercolony)

## License

MIT
