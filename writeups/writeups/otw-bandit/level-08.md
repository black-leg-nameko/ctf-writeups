# OverTheWire - Bandit Level 8 -> 9

**Category:** Text Processing
**Date:** 2025-09-08
**Author:** black-leg-nameko

## Tl;DR
Find the only line that appears exactly once in `data.txt` by sorting first and then usign `uniq -u`.

#Environment
- Tools: `sort`, `uniq`, `wc`

#Recon
```bash
ls -lh
wc -l data.txt
sort data.txt | uniq -u
```
