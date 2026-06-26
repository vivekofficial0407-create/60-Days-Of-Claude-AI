# Day 26 - Build an Interactive Prior Authorization Workflow Simulator

## Project Overview

For Day 26 of the 60 Days of Claude AI Challenge, I built an interactive healthcare workflow simulator using Claude AI.

The goal of this project was to transform the complex US healthcare Prior Authorization (PA) process into a visual and educational drag-and-drop experience.


---

# Objective

The application simulates how a Prior Authorization request moves through different healthcare stakeholders:

- Patient
- Healthcare Provider
- Insurance Payer


The simulator helps users understand:

- Request initiation
- Medical necessity evaluation
- Document collection
- Insurance review
- Approval / denial workflow


---

# Technology Used

- HTML
- CSS
- Vanilla JavaScript
- Claude AI


No frameworks or backend were used.


---

# Main Features Implemented

## 1. Interactive Patient Scenarios

The simulator supports different healthcare cases:

- MRI Scan
- Elective Surgery
- Specialty Medication
- Inpatient Admission


Example scenario tested:

MRI Brain Scan


---

# 2. Three Workflow Lanes


## Patient Lane

Represents:

- Patient request initiation
- Medical information sharing
- Starting the authorization process


## Provider Lane

Represents:

- Healthcare provider involvement
- Medical necessity documentation
- Required document submission


## Payer Lane

Represents:

- Insurance company review
- Approval decisions
- Authorization outcome


---

# 3. Drag & Drop Workflow

Users can move the authorization case through workflow stages:

Patient → Provider → Payer


This represents the real-world movement of a Prior Authorization request.


---

# 4. Document Checklist

The simulator includes required documentation tracking:

Examples:

- Referral Letter
- Clinical Notes
- Previous Imaging Reports
- Specialist Consultation
- Insurance Card Copy


The system tracks document completion before submission.


---

# 5. Workflow Tracking Dashboard

The dashboard displays:

## Days Elapsed

Tracks the time taken in the authorization process.


## Efficiency Score

Measures workflow performance.


## Status

Shows current workflow progress.


---

# 6. Decision Outcomes

The simulator supports:

✅ Approval

⏳ Pending Review

❌ Denial

🔄 Appeal

👥 Peer-to-Peer Review


---

# UI & Design

The application uses:

- Healthcare dashboard style
- Blue themed interface
- Responsive layout
- Interactive cards
- Workflow visualization


---

# Key Learnings

Through this project I learned:

1. AI can help build domain-specific applications quickly.

2. Complex real-world processes can be converted into interactive simulations.

3. Good product design is not only about UI but also about representing real user workflows.

4. AI-assisted development helps accelerate prototyping.


---

# Testing

Completed testing:

✅ Started new patient scenario

✅ Generated workflow

✅ Collected documents

✅ Tracked progress

✅ Reviewed workflow dashboard


---

# Future Improvements

Possible improvements:

- Add AI-generated explanations
- Add realistic payer decision logic
- Add analytics dashboard
- Add database support
- Add multiple user roles


---

