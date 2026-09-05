# SupplyChainTiQ – AI Disruption Impact Analyzer

## 🚀 Overview

**SupplyChainTiQ** is a GenAI-powered Supply Chain Disruption Impact Analyzer designed to help supply-chain teams quickly understand disruption events and take proactive action.

The system analyzes disruption notices, identifies affected suppliers, shipments, and customer orders, evaluates operational impact, and provides AI-generated mitigation recommendations.

## 🎯 Problem

Supply-chain disruptions such as electrical grid instability, severe weather, transportation delays, and supplier issues can affect shipments and customer orders.

Manually analyzing these disruptions takes time and can delay decision-making.

## 💡 Solution

SupplyChainTiQ uses **Generative AI + Python** to automatically:

* Extract disruption information from notices
* Identify the affected supplier
* Detect disruption type
* Estimate delay duration and impact window
* Match disruptions with shipments and customer orders
* Analyze operational impact
* Generate recommended mitigation actions
* Provide an executive-level impact summary

## ✨ Key Features

### 1. Disruption Analysis

Extracts important information from disruption notices using AI.

### 2. Supplier Identification

Identifies the supplier and relevant supplier information.

### 3. Impact Detection

Matches disruption information with supply-chain data to identify affected shipments and customer orders.

### 4. Risk & Delay Analysis

Calculates expected delays and the disruption impact window.

### 5. AI Recommendations

Generates actionable mitigation recommendations for supply-chain teams.

### 6. Executive Report

Provides a concise summary of the disruption and its business impact.

## 🏗️ Project Structure

```text
SupplyChainTiQ/
│
├── data/
│   ├── orders.json
│   ├── sample_notices.txt
│   ├── shipments.json
│   ├── stock.json
│   └── suppliers.json
│
├── frontend/
│   └── dist/
│       ├── app.js
│       ├── index.html
│       └── styles.css
│
├── src/
│   ├── __init__.py
│   ├── app.py
│   ├── impact.py
│   ├── llm.py
│   └── matching.py
│
├── requirements.txt
└── README.md
```

## 🛠️ Technology Stack

* **Python**
* **Generative AI / LLM**
* **Flask / Python Backend**
* **HTML**
* **CSS**
* **JavaScript**
* **JSON**
* **Supply Chain Analytics**

## 🔄 Workflow

```text
Disruption Notice
       ↓
AI Disruption Extraction
       ↓
Supplier Identification
       ↓
Shipment & Order Matching
       ↓
Impact Analysis
       ↓
Risk / Delay Assessment
       ↓
AI Mitigation Recommendations
       ↓
Executive Report
```

## 📊 Sample Output

The system can identify:

* Disruption type
* Supplier
* Supplier location
* Confidence score
* Affected shipment
* Affected customer order
* Expected delay
* Impact window
* Recommended mitigation actions

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd SupplyChainTiQ
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python src/app.py
```

Then open the local URL displayed by the application in your browser.

## 🏆 Hackathon

Built for **NexusTiQ 24 – CareerTiQ** under the **Supply Chain** track.

The project demonstrates how Generative AI can support faster disruption detection, impact assessment, and proactive supply-chain decision-making.

## 👩‍💻 Developer

**Priyadharshini Balasubramani**

BE Computer Science and Engineering
