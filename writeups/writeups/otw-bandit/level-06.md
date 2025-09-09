# OverTheWire — Bandit Level 6 → 7

**Catgory:** Linux Basics  
**Date:** 2025-09-08  
**Author:** your-handle

## TL;DR
Search the whole filesystem for a file owned by `bandit7`, group `bandit6`, with an exact size of 33 bytes. Read it.

## Environment
- Tools: `find`, `cat`

## Solution
```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password   # example path
