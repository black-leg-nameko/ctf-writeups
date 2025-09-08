# OverTheWire — Bandit Level 5 → 6

**Category:** Linux Basics  
**Date:** 2025-09-08  
**Author:** your-handle

## TL;DR
Use `find` to locate a regular file under `inhere/` that is **1033 bytes**, **non-executable**, and verify it's human-readable. Print it.

## Environment
- Attacker: Kali 2024.x
- Tools: `find`, `file`, `cat`

## Recon
```bash
cd inhere

