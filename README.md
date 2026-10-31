# THEIA — Indoor Navigation Assistance for Visually Impaired Users

**Washington State University | CPT_S 484: Software Requirements | Fall 2024**

## Project Overview

THEIA is a proposed smartphone application designed to help blind and visually impaired individuals navigate unfamiliar indoor environments more safely and independently. The concept focuses on multi-story buildings, including schools and offices, where finding rooms, navigating hallways, and avoiding obstacles can be challenging.

This repository documents a **team software requirements engineering project** completed for CPT_S 484. Our assignment was to analyze the problem, identify stakeholders, evaluate and refine requirements, and produce a structured specification for a proposed solution. **THEIA was a requirements and interface-design concept, not a completed or deployed navigation application.**

## Project Goals

- Support safe, reliable indoor navigation using spoken directions.
- Identify obstacles and provide timely warnings.
- Assist users during emergencies, including potential falls.
- Recommend routes based on user preferences and routines.
- Make navigation controls accessible and customizable.
- Define a flexible design that could accommodate additional sensors and features.

## Proposed Functional Requirements

| ID | Requirement |
| --- | --- |
| FR1 | Deliver real-time indoor navigation instructions. |
| FR2 | Detect obstacles and provide audio guidance to avoid collisions. |
| FR3 | Recognize emergencies, such as falls, and initiate an alert with location information. |
| FR4 | Learn from user routines to suggest destinations or activities. |
| FR5 | Support multiple destinations within one navigation session. |
| FR6 | Allow customization of voice volume, instruction frequency, and route preferences. |

## Non-Functional Requirements

The specification also addresses seven quality objectives: **safety, route efficiency and comfort, personalized navigation, accessibility, reliability across indoor environments, customization, and extensibility**. Proposed approaches include a simplified voice-driven interface, smartphone motion sensors, adaptive use of available positioning technologies, and a modular architecture.

## Requirements Engineering Process

The project follows a **World–Requirements–Specifications (WRS)** approach:

1. **Define the problem and domain:** Describe the navigation challenges, intended indoor environments, and affected stakeholders.
2. **Elicit preliminary requirements:** Identify initial functional and non-functional expectations.
3. **Analyze ambiguities and trade-offs:** Examine issues such as indoor positioning accuracy, obstacle classification, false emergency alerts, user privacy, and the balance between route speed and safety.
4. **Refine objectives and requirements:** Evaluate possible solutions, document decisions and rationales, and improve requirement statements.
5. **Establish traceability:** Connect identified problems to goals, objectives, requirements, and specifications using identifiers.
6. **Explore the interface:** Describe and mock up screens for destination entry, route planning, navigation, obstacle alerts, emergency assistance, and settings.

## Stakeholders

The analysis considers visually impaired users as primary stakeholders, alongside caregivers and family members, facility staff, building managers, and emergency responders.

## Proposed User Experience

A user would enter or speak a destination, choose an available route, and receive step-by-step audio guidance. The proposed app would warn of obstacles, announce turns and arrival, and provide emergency assistance options. Settings would allow users to tailor the navigation experience to their needs.

The specification includes preliminary mobile interface mockups illustrating these interactions.

## Repository Document

- [`WRS_Project_Specifications.docx`](WRS_Project_Specifications.docx) — Team requirements elicitation report, WRS analysis, functional and non-functional requirements, specifications, and interface mockups.

## Academic Context

**Course:** CPT_S 484 — Software Requirements  
**Institution:** Washington State University  
**Project type:** Team requirements analysis and specification  
**Document date:** October 13, 2024

This repository demonstrates experience with requirements elicitation, stakeholder analysis, ambiguity resolution, trade-off evaluation, requirements traceability, and early interface design. It is shared as an academic project artifact, not as evidence of an implemented, tested, or safety-certified assistive navigation product.
