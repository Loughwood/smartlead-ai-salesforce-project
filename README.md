# smartlead-ai-salesforce-project
AI-Powered Lead Scoring App built with Salesforce, Einstein, and Flow

# SmartLead: AI-Powered Lead Scoring in Salesforce

A lead prioritization system built using Salesforce and AI to automatically score leads based on their likelihood to convert. This project helps sales teams focus their attention on the most promising prospects using data-driven insights.

---

## Project Overview

**Problem:** Sales teams often spend too much time qualifying low-quality leads manually.  
**Solution:** Automate lead scoring using Salesforce’s Einstein Prediction Builder and Flows, assigning scores based on AI-driven predictions.

---

## Tools Used

- Salesforce Lead Object
- Custom Object: `Lead_Score__c`
- Einstein Prediction Builder
- Flow Builder (Scheduled Flow)
- Reports & Dashboards
- Apex (optional extension for future custom AI integration)
- Loom (demo recording)

---

## Screenshots

| Feature | Preview |
|--------|--------|
| Lead Object with Scoring Integration | ![Lead Object View](screenshots/lead-object-view.png) |
| Custom Object Setup | ![Lead Score Object](screenshots/lead-score-custom-object.png) |
| Flow Builder Logic | ![Flow Builder](screenshots/flow-builder-prediction-logic.png) |
| Einstein Model Setup | ![Einstein Setup](screenshots/einstein-prediction-setup.png) |
| Dashboard Example | ![Dashboard](screenshots/dashboard-example.png) |

---

## How It Works

1. **Lead Data Input** – New or updated leads enter the system.
2. **Prediction Model** – Einstein Prediction Builder assesses each lead’s likelihood to convert.
3. **Score Generation** – A Flow writes the prediction score to a custom `Lead_Score__c` object.
4. **Automation** – Optional email notifications trigger for high scores.
5. **Reporting** – Dashboards visualize score trends and lead quality insights.

---

## Impact

- Faster lead qualification
- Increased conversion focus
- Time saved for sales reps
- AI transparency and trust building

---

## Demo Video

▶️ [Watch the Demo on Loom](https://loom.com/your-demo-link-here)

---

## Folder Structure

```text
smartlead-ai-salesforce-project/
├── README.md
├── screenshots/
├── flow-diagrams/
├── documentation/


