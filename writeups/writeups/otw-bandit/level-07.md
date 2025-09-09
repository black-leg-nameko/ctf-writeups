# OverTheWire — Bandit Level 7 → 8

**Catgory:** Linux Basics  
**Date:** 2025-09-08  
**Author:** your-handle

## TL;DR
The password for the next level is stored in the file data.txt next to the word millionth

## Environment
- Tools: `find`, `cat`, `grep`

## Solution
```bash
ls -la
cat data.txt | grep millionth
```
