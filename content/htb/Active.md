---
title: "HTB — Active (Linux)"
Difficulty: "Easy"
date: 2025-07-25
tags: ["htb", "ctf", "writeup", "Active"]
---

## 🧠 Overview

Active is a basic Active Directory box involving manipulating shares. Kerberoasting and using Impacket

---

## 🔎 Recon

```bash
nmap -sV -sC -oA nmap/lame 10.10.10.3
