# UniSwap Portfolio

UniSwap is a user centered exchange platform for university communities. This portfolio highlights my end to end UX UI process using Figma as the primary design tool, and demonstrates user flows, high fidelity prototype work, user research, and usability driven iteration.

This page is structured to match common UX UI Designer expectations: user flows and journeys, high fidelity mockups, research and feedback loops, and clear deliverables.

## Quick links
- Figma high fidelity interactive prototype: https://www.figma.com/proto/qWJnSJfVpX0d3ArfxpyH1h/CSCC10-Prototype-for-Phase-3?node-id=94-531&starting-point-node-id=94%3A531
- Case study: ./case-study.md
- Reports
  - Phase 1 Project Proposal: ./Phase1_ProjectProposal.pdf
  - Phase 2 User Requirements: ./UniSwap_Phase2_UserRequirements.pdf
  - Phase 3 Interactive Prototype: ./Phase3_InteractivePrototype.pdf
  - Phase 4 Final Report and Usability Study: ./Phase4_FinalReport_UsabilityStudy.pdf

## My role
Product Lead and UX Researcher in a six person team. I led multi phase research, translated insights into user flows and a high fidelity Figma prototype, and ran usability evaluation to prioritize iterations and future work.

## Problem and users
### Problem
University students often lack a secure and user friendly way to exchange items within their community. Existing methods create inefficiency and safety concerns, especially when users cannot rely on verification, consistent coordination, or clear transaction status.

### Target users
We designed for four primary user groups:
- Students on a budget
- International students
- Students with disabilities and mobility constraints
- Eco conscious students
These groups were used to define personas, scenarios, and critical journeys.

## Research and ideation
### Methods used
- Questionnaire and interviews to gather user requirements, validate priorities such as trust and convenience, and identify feature expectations
- Personas, scenarios, and hierarchical task analysis to define user journeys and scope design questions
- Low fidelity prototypes to test early assumptions and refine workflows before building the high fidelity prototype

### What we learned from requirements research
Key themes that repeatedly surfaced:
- Trust and safety: strong preference for university credential verification, plus the need for safer exchange coordination
- Convenience and accessibility: demand for location based filtering and simple coordination, especially for mobility constrained users
- Clear interaction design: strong need for advanced filters, messaging, and reviews to reduce uncertainty in second hand exchanges
- Transparency of points: concerns about understanding and fairness of the point system, and the need for clearer guidance

## Design deliverables in Figma
### High fidelity user flows and journeys
The Figma prototype is organized around three end to end flows, each written as step by step task instructions:
1) Sign up and verification
2) Complete a transaction including search filters, messaging, checkout, transaction confirmation, and post transaction review
3) Post an item for exchange including usage condition selection, availability calendar, and submission confirmation

### Interaction design decisions
Across the prototype, the design emphasizes clarity and feedback:
- Navigation consistency via a bottom navigation bar
- Clear prompts and confirmation feedback after key actions
- Filters for category, location, and points to reduce search effort
- In app messaging to coordinate exchange details without sharing personal contact information
- Ratings and reviews to support trust in a closed community environment

## Usability evaluation and iteration
### Study setup
We ran a usability study with six university students using semi structured interviews in informal campus settings. Participants completed the three core tasks and then provided quantitative ratings and qualitative feedback.

### Summary metrics
- Sign up and verification: 6 of 6 completion, average score 7.7 out of 10
- Completing a transaction: 5 of 6 completion, average score 7.8 out of 10
- Posting an item: 5 of 6 completion, average score 7.7 out of 10

### Top usability issues found
The most frequent breakdowns included:
- Confusion with pickup checkboxes in chat
- Ambiguity in required inputs for location and item description
- Dense and unorganized layout in posting
- Missing transaction status and visible review entry points
- Difficulty selecting a date range for availability

### Iteration plan driven by findings
We proposed concrete improvements tied to the issues above:
- Remove confusing pickup checkboxes and streamline the transaction workflow
- Add transaction status indicators and visible review entry points
- Reorganize the posting interface with field grouping, spacing, and a preview step
- Add clearer input guidance via placeholders, required field marking, and description examples
- Replace single day selection with a range selector for availability
- Add point system overview and onboarding explanation for clarity

## Bonus: web based implementation
UniSwap also included a web based UI build using React, and I iterated the front end based on research findings and usability feedback.

## What to review first
If you only have two minutes:
1) Open the Figma prototype and click through the three flows
2) Read the usability metrics and top issues section above
3) Skim the case study for how issues mapped to concrete design changes
