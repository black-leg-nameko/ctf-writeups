# OverTheWire — Bandit Level 2

**Category:** Linux Basics  
**Date:** 2025-09-08  
**Author:** <black-leg-nameko>

## TL;DR
ssh to get into the game.

## Environment
- OS: Kali 2024.x
- Tools: `ssh` 9.x

## Recon
```bash
ssh -p 2220 bandit2@bandit.labs.overthewire.org

ls -la

cat ./--spaces\ in\ this\ filename
```

## Tips
You can use quotation marks or \ if the filename includes spaces.
If the filename starts with -- (-), you can use ./-- (./-)
