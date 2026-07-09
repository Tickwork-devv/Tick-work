# Security

tickwork is an **educational reference implementation**, not production software.

- The engine uses floating point, is unaudited, and models a subset of real CLMM
  behavior. **Do not use it to custody or trade real funds.**
- The site runs entirely client-side. It has no backend, requests no wallet
  connection, and collects no data.

If you find a correctness bug in the math (a case where the engine disagrees with
the real CLMM invariants), please open an issue with a minimal reproduction — a
failing test is the ideal format. Math bugs are the only "vulnerabilities" this
project can meaningfully have, and finding them makes the reference better.
