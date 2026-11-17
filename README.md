# Tiny Chess 01 Entry

A deterministic, self-contained Python 3 chess engine for make.fun `tiny-chess-01`.
`main.py` contains its complete engine in a compressed payload: legal move generation,
material/positional evaluation, and fixed-depth alpha-beta search. It communicates
only with the contest environment through `MAKEFUN_ENV_URL` and uses no model calls,
files, packages, or randomness.

The committed file is intentionally packed to stay below the 4,096-byte entry limit.
