# OverTheWire — Bandit Level 0

**Category:** Linux Basics  
**Date:** 2025-09-08  
**Author:** <your-handle>

## TL;DR
SSH to the game server on a non-default port, read the welcome, and prepare for credential handoff in Level 0→1.

## Environment
- OS: Kali 2024.x
- Tools: `ssh` 9.x

## Recon
```bash
ssh -p 2220 bandit0@bandit.labs.overthewire.org

