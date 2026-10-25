# 🦉 OTaker

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OTaker** — Authorized visual reconnaissance: subdomain screenshots, ASN, Wayback, HTML reports

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OTaker is a subdomain asset visualizer that turns a list of hosts into a visual intelligence report with screenshots, HTML output, ASN data, Wayback history and CVE hints. It drives a headless Chromium to capture full-page screenshots and enriches each asset with network and historical context. It runs with a bounded worker pool for authorized reconnaissance.

---

## ✨ Features


- Headless-Chromium full-page screenshots of discovered subdomains/assets
- Consolidated HTML report with visual asset cards
- ASN lookup and network context enrichment per host
- Wayback Machine history and CVE hinting
- Bounded worker pool (default 4, hard cap 16) with HTTP and page-load timeouts
- CSV/JSON output and an offline --self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OTaker
./OTaker --self-test
./OTaker --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
