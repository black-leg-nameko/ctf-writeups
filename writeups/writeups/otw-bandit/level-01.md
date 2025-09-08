# OverTheWire — Bandit Leel 1 → 2

**Category:** Linux Basics  
**Date:** 2025-09-08  
**Author:** your-handle

## TL;DR
The password is stored in a file literally named `-`. Use a path or `--` to treat it as a filename, not stdin.

## Environment
- Attacker: Kali 2024.x
- Tools: `ssh`, `cat`, `ls`

## Recon
```bash
ssh -p 2220 bandit1@bandit.labs.overthewire.org
ls -la
```
## Commands
cat ./-
