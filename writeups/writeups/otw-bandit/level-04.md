# OverTheWire — Bandit Level 4 → 5

**Category:** Linux Basics  
**Date:** 2025-09-08  
**Author:** your-handle

## TL;DR
Search inside `inhere` for the only human-readable file, identified via `file`, and read it.

## Environment
- Attacker: Kali 2024.x
- Tools: `ssh`, `ls`, `file`, `cat`

## Recon
```bash
ssh -p 2220 bandit4@bandit.labs.overthewire.org
cd inhere
ls -la
file ./*
```

## Tips
You can use wild card(*) in order to process data in batches
