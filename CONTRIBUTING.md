# Contributing to tickwork

Contributions welcome — this is a learning project, and clearer explanations,
more tests, or new modeled mechanisms all make it better.

## Ground rules

- **Tests are the spec.** Any change to the engine must keep `npm test` green,
  and new behavior needs a new invariant test that reads like a claim.
- **Readability over cleverness.** This code is meant to be *understood*. If a
  reviewer can't follow it in one pass, simplify.
- **No scope inflation.** This is a reference engine, not a production DEX. PRs
  that add real-funds features (custody, live trading) are out of scope by design.

## Workflow

1. Fork and branch (`fix/tick-rounding`, `feat/il-simulator`).
2. Make the change; run `cd engine && npm test`.
3. Open a PR describing what changed and which test proves it.

## Ideas that would help

- An impermanent-loss simulator (natural next figure on the site)
- More edge-case tests around partial fills and extreme ranges
- Plain-language improvements to the site's explanations
