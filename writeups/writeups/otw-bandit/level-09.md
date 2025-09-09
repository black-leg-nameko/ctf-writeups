# OverTheWire - Bandit Level 9->10

**categoy:** Txt / Binary Analysis
**Date:GG 2025-09-08
**Author** black-leg-nameko

## TL;DR
Extract strings from `data.txt` and filter for lines containing `==` which includethe password.

## Environment
- Tools: `ssh`, `strings`, `grep`

## Solution
```bash
strings data.txt | grep ==
```
