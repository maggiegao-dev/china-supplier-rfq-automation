# China Supplier RFQ Scoring & Qualification Automation

An n8n workflow that automatically scores and qualifies suppliers based on Price, MOQ, and Lead Time.

## Business Problem

Supplier quotations are often compared manually, which is time-consuming and inconsistent.

This workflow automates the first-stage supplier screening process.

## How It Works

Supplier RFQ Form  
↓  
Calculate Supplier Score  
↓  
Supplier Qualification  
↓  
Qualified / Not Qualified  
↓  
Save Result

## Scoring Criteria

- Price: up to 40 points
- MOQ: up to 35 points
- Lead Time: up to 25 points
- Maximum Score: 100

## Qualification Rules

A supplier is qualified when:

- Price ≤ 35
- MOQ ≤ 500
- Lead Time ≤ 30 days

Otherwise, the supplier is marked as **Not Qualified**.

## Built With

- n8n
- Form Trigger
- Edit Fields
- IF Logic
- Expressions
- Data Table
- Conditional Routing

## Project Focus

China Sourcing + Supplier Qualification + Workflow Automation
