# FUTURE_CS_02 — Phishing Email Detection & Awareness Report

**Intern:** Idowu  
**Track:** Cyber Security  
**Organization:** Future Interns  
**Date:** April 2026  

---

## About This Task

This task involved analyzing real phishing email samples collected from a 
public research repository. The goal was to identify phishing indicators, 
classify each email by risk level, and produce a professional awareness 
report that businesses and users can apply to protect themselves.

---

## Samples Analyzed

| # | File | Type | Language | Classification |
|---|---|---|---|---|
| 1 | sample-1.eml | Fake Bank Rewards Scam | Portuguese | 🚨 Phishing |
| 2 | sample-10.eml | Fake Microsoft Security Alert | English | 🚨 Phishing |
| 3 | sample-100.eml | Fake Solar Panel Deal | Dutch | 🚨 Phishing |

> Samples sourced from: https://github.com/rf-peixoto/phishing_pot  
> Used strictly for educational analysis — not copied or claimed as original work.

---

## Tools Used

- Raw .eml file inspection (text editor)
- Google Apps Message Header Analyzer — https://toolbox.googleapps.com/apps/messageheader/
- MXToolbox Email Header Analyzer — https://mxtoolbox.com/EmailHeaders.aspx
- Browser tools for safe URL inspection

---

## Analysis Approach

Each email was examined for the following indicators:
- Sender domain spoofing
- Return-Path and Reply-To domain mismatches
- SPF / DKIM / DMARC authentication failures
- Urgency and fear-based language
- Suspicious or mismatched links
- Generic greetings
