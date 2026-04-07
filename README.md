# MSK Monitoring & Return-to-Play Decision System (Azure AI Prototype)

AI-assisted workflow for tracking musculoskeletal (MSK) injuries and supporting return-to-play decisions using structured performance and recovery data.

## Overview
This system captures daily athlete inputs (pain, training load, energy, readiness) and translates them into consistent monitoring, trend analysis, and decision-support outputs.

The goal is to reduce subjective decision-making and provide a more structured, data-informed approach to rehabilitation and performance progression.

## 🔁 System Flow

Injury Status  
→ Daily Monitoring (pain, load, energy, readiness)  
→ Trend Analysis  
→ AI-assisted Decision Support  
→ Return-to-Play Progression  

## 📊 Example

- Input data → /data/sample-inputs.csv  
- Decision output → /outputs/sample-decisions.md  

## Decision Logic (Simplified)

- Pain decreasing + energy stable → **Progress**
- Pain increasing + energy low → **Modify**
- Load increasing + energy dropping → **Hold**

---

## Decision Output

- **Progress** → Increase load or complexity  
- **Hold** → Maintain current level  
- **Modify** → Reduce load or adjust exercise  
## 🚀 Next Steps

- Integrating Azure OpenAI for automated insights and summaries  
- Expanding into injury risk prediction models  
- Building a dashboard for real-time monitoring  
