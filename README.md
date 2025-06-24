# Assignment-2-e-gmat
# e-GMAT Sales Call Analysis – AI Application Engineer Assignment

## Overview

This project is a complete AI-powered analytical system designed to evaluate and optimize sales call performance using real transcript data from e-GMAT. The objective is to analyze conversation quality, identify key conversion factors, and recommend an AI-powered follow-up strategy to improve conversion rates.

The assignment was completed as part of the AI Application Engineer internship selection process.

---

## 🧠 Problem Statement

- Analyze two sets of sales call transcripts (Set A and Set B).
- Identify top and least converting calls.
- Determine drivers of performance — customer factors, sales rep behavior, or both.
- Justify findings using statistical and anecdotal evidence.
- Design an AI-powered post-call follow-up strategy to increase conversions.

---

## 🛠️ Tech Stack

| Tool / Platform    | Purpose                                        |
|--------------------|------------------------------------------------|
| **Google Drive**   | Input: Load raw transcript documents           |
| **n8n**            | Orchestration: Modular workflow automation     |
| **Airtable**       | Output: Structured data storage and retrieval  |
| **OpenRouter API** | Language model integration                     |
| **JavaScript**     | Used in Function nodes for data transformation |
| **LLMs Used**      | GPT-4o, GPT-4o Mini, Claude 3.5 Sonnet         |

---

## 🔧 Workflows Implemented

1. **Main Workflow**
   - Converts raw transcripts to structured JSON.
   - Extracts: conversion score, reasons, strengths, weaknesses, deep insights.

2. **Top/Least Call Identification**
   - Selects top 5 and least 5 calls from each set.
   - Extracts improvement suggestions and patterns.

3. **Individual Inference Generator**
   - For each call:
     - Infers conversion driver (customer / sales rep / both)
     - Extracts statistical + anecdotal evidence.

4. **Combined Inference Part 1 & 2**
   - Compares Set A and B:
     - Performance differences
     - Demographic/reasoning insights
     - 3 improvement areas for best and least converting calls



## 📊 Key Findings

- **Set B converted better** (Avg Score: 8.06) than Set A (Avg Score: 7.90).
- Strong sales rep performance (rapport, urgency, objection handling) drove Set B’s success.
- Insights supported by both qualitative anecdotes and measurable behavioral patterns.
- Follow-up gaps, missed pricing discussions, and lack of family involvement were recurring issues in both sets.

---



## ✅ Deliverables

- Structured Airtable database with insights from 140+ transcripts
- Fully-automated, low-cost, LLM-powered data pipeline
- PDF report with performance analysis, visualizations, and AI strategy
- End-to-end reproducible AI system built using real-world workflow tools

---

## 🤝 Acknowledgements

- Models: OpenAI GPT-4o, GPT-4o Mini, Anthropic Claude 3.5 Sonnet via OpenRouter
- Orchestration: n8n
- Data Storage: Airtable



---

> 🚀 _"Built with cost-efficiency, clarity, and performance in mind — powered by real reasoning, not just automation."_
