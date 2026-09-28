# ThreatLens-SIH26106
# ThreatLens – AI-Powered Email Threat Detection & Forensic Intelligence Platform

📄 **SIH 2026 | Problem Statement SIH26106**
## SIH 2026 | Problem Statement SIH26106

ThreatLens is an AI-powered email threat detection and forensic intelligence platform designed to detect suspicious emails, analyze multiple security signals, correlate digital evidence, identify related campaigns, and generate explainable forensic insights.

### Tagline

DETECT → CORRELATE → INVESTIGATE → EXPLAIN → REPORT

---

## Problem Statement

Traditional email security systems often focus mainly on detecting whether an email is suspicious or malicious.

However, during a cyber investigation, analysts need to answer additional questions:

- Who sent the email?
- Which domain and IP infrastructure are involved?
- Are the URLs suspicious?
- Did SPF, DKIM or DMARC authentication fail?
- Are multiple suspicious emails connected?
- Is the activity part of a larger campaign?
- What evidence should be preserved for investigation?

Manual correlation of these indicators can be time-consuming and difficult.

---

## Proposed Solution

ThreatLens provides an integrated platform that combines email threat detection with forensic evidence correlation.

The platform analyzes:

- Email content
- Email headers
- SPF/DKIM/DMARC authentication
- URLs and domains
- IP information
- Header anomalies
- Suspicious patterns
- Related infrastructure

These signals are combined into an explainable risk assessment.

---

## Key Features

### 1. Email Threat Detection
Analyze suspicious emails and identify potential phishing, spoofing and other email-based threats.

### 2. Multi-Signal Risk Analysis
Combines multiple security indicators to calculate a unified risk score.

### 3. Explainable Risk Decision
Shows the major factors contributing to a risk verdict instead of providing only a final score.

### 4. Threat Evidence Graph
Connects related evidence:

Email → Sender → Domain → IP → Mail Server → URL → Infrastructure → Related Incidents

### 5. Campaign Detection
Groups potentially related suspicious emails using common domains, URLs, IPs and infrastructure.

### 6. Attack Timeline
Provides a structured investigation flow:

Email Received → Header Analysis → Domain/IP Discovery → URL Analysis → Threat Correlation → Risk Decision

### 7. Evidence & Audit Metadata
Maintains evidence IDs, timestamps and analysis history to support forensic investigation.

### 8. Forensic Report
Generates a structured investigation report containing analyzed indicators and evidence.

---

## Main USP

### Threat Evidence Graph

Instead of treating every suspicious email as an isolated alert, ThreatLens connects the email with its related digital infrastructure and incidents.

This helps investigators move from:

**Single Email Detection**

to

**Connected Campaign-Level Forensic Intelligence**

---

## System Workflow

```text
Email Input
     ↓
Email & Header Parsing
     ↓
Indicator Extraction
     ↓
Multi-Signal Security Analysis
     ↓
Unified Risk Assessment
     ↓
Threat Evidence Correlation
     ↓
Campaign Detection
     ↓
Explainable Investigation
     ↓
Forensic Report
