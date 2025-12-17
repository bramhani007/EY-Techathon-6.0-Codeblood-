# EY-Techathon-6.0-Codeblood-

# 🧬 End-to-End Drug Repurposing Multi-Agent Workflow

## 📌 Overview

This project demonstrates an **AI-driven, multi-agent workflow** for drug repurposing research using **CrewAI**.
The system automates the collection, analysis, and synthesis of clinical and scientific data to identify potential repurposing opportunities for a given molecule and generates a **structured Word (DOCX) research report**.

## 🎯 Problem Statement

Drug repurposing research is often slow and fragmented due to manual analysis across disconnected data sources such as clinical trials, scientific literature, and regulatory information. This leads to increased effort, longer research cycles, and missed opportunities.

## 💡 Solution Summary

This solution uses **multiple specialized AI agents** working in parallel to:

* Collect real-time research data
* Analyze clinical and scientific evidence
* Synthesize insights into a single, decision-ready report

The entire process is automated and orchestrated through a visual workflow in CrewAI.

## 🧠 Workflow Architecture

### 🔹 User Flow

1. User submits a molecule name or research query
2. Specialized agents process the query in parallel
3. Outputs are consolidated into a final Word document
4. User downloads the structured research report

## 🤖 Agents Used

* **Research Coordinator Agent**
  Provides initial background and overview of the molecule

* **Clinical Trials Research Agent**
  Identifies and analyzes relevant clinical trials

* **Knowledge Extraction Agent**
  Extracts mechanism of action, targets, pathways, and indications

* **Report Aggregator / Document Processor Agent**
  Combines all insights and generates the final Word (DOCX) report

## 📊 Key Tasks

* Quick Research Overview
* Clinical Trials Analysis
* Scientific Knowledge Extraction
* Comprehensive Report Generation

## 📄 Output

* **Web-based execution**
* **Automatically generated Word (DOCX) report**
* Includes:

  * Repurposing opportunities
  * Scientific rationale
  * Clinical trial insights
  * Risks and recommendations

## 📈 Value Proposition

* Automates drug-repurposing research
* Reduces manual analysis effort
* Speeds up research cycles
* Improves accuracy and consistency
* Converts fragmented data into actionable insights

## 🛠️ Tools & Platform

* CrewAI (Visual Workflow Editor)
* GPT-based agents
* Online research tools (search & data retrieval)
* Microsoft Word document generation

## 🚀 How to Use

1. Open the workflow in **CrewAI Studio**
2. Enter a molecule name (e.g., *Metformin*)
3. Run the workflow
4. Download the generated Word (DOCX) report


## 🔮 Future Enhancements

* Add more domain-specific agents
* Extend report sections
* Integrate additional data sources
* Support multiple output formats

## 📌 Project Status

✅ Workflow implemented
✅ Agents connected
✅ Automated Word report generation
