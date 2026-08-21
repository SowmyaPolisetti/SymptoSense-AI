# SymptoSense AI: A Multi-Agent Health Symptom Analytics, Risk Prediction, and Care Routing Ecosystem

## Project Title

**SymptoSense AI: A Multi-Agent Health Symptom Analytics, Risk Prediction, and Care Routing Ecosystem**

## Team Members

| S. No. | Name            | Roll Number |
| ------ | --------------- | ----------- |
| 1      | B.Vignesh Reddy | 2420030285  |
| 2      | P. Karthik      | 2420030404  |
| 3      | P.Sowmya        | 2420030457  |

## Supervisor

**Supervisor Name:** Dr. Srikanth Cherukuvada

## Abstract

Emergency rooms around the world are overcrowded, and many patients who visit them do not actually need emergency-level care. They could have been checked earlier, given appropriate advice, or directed to a more suitable form of care. Existing symptom-checker applications are often basic, relying on fixed yes/no question trees. They may struggle to handle multiple confusing symptoms described in natural language and often fail to explain why a particular suggestion was provided. This reduces trust among both patients and doctors.

SymptoSense AI addresses this need by providing an intelligent system that can understand symptoms described in plain language, assess the potential seriousness of a situation, and guide users toward the appropriate level of care.

Instead of relying on a single program, SymptoSense AI uses three smaller AI agents that work together.

The **Symptom Analytics Agent** performs symptom analysis on text input from the patient. It uses GPT-4o/Gemini to extract important medical details and convert them into structured data for further processing.

The **Risk Prediction Agent** uses the extracted information to predict how risky or serious the situation may be. Importantly, it also explains its reasoning rather than providing only an unexplained risk score.

The **Care Routing Agent** determines the appropriate next step based on the predicted risk. Urgent cases can be directed toward the emergency room, moderate cases toward a video doctor consultation, and minor cases toward safe self-care advice.

Collectively, these three agents form an autonomous, explainable, and safety-conscious triage ecosystem. By combining symptom analytics, predictive risk scoring, and intelligent care routing within a service-oriented architecture, SymptoSense AI aims to reduce preventable delays in care-seeking, reduce unnecessary burden on emergency systems, and improve early access to appropriate care.

SymptoSense AI is **not intended to replace doctors or provide a definitive diagnosis**. It is designed as an intelligent first-level triage assistant that helps users understand the urgency of their symptoms and identify an appropriate next step in care. The project directly supports **SDG 3: Good Health and Well-Being**.

## Objectives

* Analyze symptoms provided by users in natural language.
* Extract important medical information from patient symptom descriptions.
* Convert extracted symptom information into structured data.
* Predict the potential risk or seriousness of a patient's condition.
* Provide explanations for the predicted risk.
* Route users toward an appropriate level of care.
* Direct urgent cases toward emergency care.
* Guide moderate cases toward video doctor consultations.
* Provide safe self-care advice for minor issues.
* Provide an autonomous, explainable, and safety-conscious first-level triage system.
* Reduce unnecessary burden on emergency systems.
* Improve early access to appropriate care.

## Technologies Used

### AI and Language Models

* GPT-4o
* Google Gemini

### Multi-Agent Components

* Symptom Analytics Agent
* Risk Prediction Agent
* Care Routing Agent

### Architecture

* Service-Oriented Architecture
* Multi-Agent AI Architecture

## Project Architecture

```text
                         SymptoSense AI
                              │
                              ▼
                  ┌───────────────────────┐
                  │   Patient Symptoms    │
                  │     Natural Language  │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │ Symptom Analytics     │
                  │       Agent           │
                  │                       │
                  │ GPT-4o / Gemini       │
                  │ Symptom Extraction    │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │   Risk Prediction     │
                  │       Agent           │
                  │                       │
                  │ Risk Assessment       │
                  │ Explainable Reasoning │
                  └───────────┬───────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │     Care Routing      │
                  │        Agent          │
                  │                       │
                  │ ER / Video Doctor /   │
                  │ Safe Self-Care        │
                  └───────────────────────┘
```

## System Workflow

1. **Symptom Input:** The patient provides symptoms in natural language.
2. **Symptom Analytics:** The Symptom Analytics Agent analyzes the input and extracts important medical details.
3. **Structured Information:** The extracted information is converted into structured data.
4. **Risk Prediction:** The Risk Prediction Agent evaluates the potential seriousness of the situation.
5. **Explainable Assessment:** The system provides reasoning for the predicted risk rather than only displaying a risk score.
6. **Care Routing:** The Care Routing Agent determines the appropriate next step.
7. **Care Recommendation:** The system may direct the patient to emergency care, a video doctor consultation, or safe self-care advice depending on the situation.

## Current Phase Status

**Current Phase:** Project Abstract / Initial Project Development

**Status:** Project title, problem definition, multi-agent concept, system workflow, and service-oriented project overview defined.

## Project Overview

SymptoSense AI combines three specialized AI agents:

### 1. Symptom Analytics Agent

Analyzes patient symptom descriptions in text form and uses GPT-4o/Gemini to extract key medical details and convert them into structured information.

### 2. Risk Prediction Agent

Uses the extracted information to assess the potential risk or seriousness of the patient's situation and provides an explanation for its assessment.

### 3. Care Routing Agent

Determines the appropriate next step based on the risk level, including:

* Emergency Room for urgent cases
* Video doctor consultation for moderate cases
* Safe self-care advice for minor issues

## Key Features

* Natural-language symptom understanding
* Multi-agent processing
* Symptom analytics
* Risk prediction
* Explainable risk assessment
* Intelligent care routing
* Autonomous first-level triage
* Safety-conscious recommendations
* Service-oriented architecture

## Expected Outcome

SymptoSense AI aims to shift symptom checking from static lookup systems toward genuine multi-agent reasoning. The system is intended to reduce preventable delays in care-seeking, ease unnecessary burden on emergency systems, and improve early access to appropriate care.

## Safety and Scope

SymptoSense AI is **not intended to replace doctors or provide a definitive diagnosis**.

The system is intended to function as an **intelligent first-level triage assistant**, helping users understand the urgency of their symptoms and identify an appropriate next step in care.

## SDG Alignment

**SDG 3: Good Health and Well-Being**

The project supports SDG 3 by aiming to improve early access to appropriate care and reduce unnecessary burden on emergency healthcare systems.

## Academic Information

**Course:** SOA Programming and Microservices (24SDCS03)

**Academic Year:** 2026–2027

**Guide:** Dr. Srikanth Cherukuvada
