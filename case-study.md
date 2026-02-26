# UniSwap — Case Study

Prototype (Figma high fidelity interactive prototype): https://www.figma.com/proto/qWJnSJfVpX0d3ArfxpyH1h/CSCC10-Prototype-for-Phase-3?node-id=94-531&starting-point-node-id=94%3A531

## Why this project matters
UniSwap is a secure, university based exchange platform for students and staff to swap reusable items using a point system. The goal is to reduce friction and risk in second hand exchanges by combining university credential verification, structured search, in app messaging, and reviews. The project was explicitly designed around trust, safety, accessibility, and sustainability needs in university communities.

This case study is written to match UX UI Designer expectations: Figma first workflow, user flows and journeys, high fidelity mockups, research and feedback loops, and usability driven iteration.

## My role
Product Lead and UX Researcher in a six person team (TheSix). I led the research planning and execution across phases, turned findings into user flows and a high fidelity prototype in Figma, and drove usability evaluation and prioritized iterations.

## Problem
University students often do not have a secure and user friendly platform to exchange items within their community. Existing channels create inefficiency and safety concerns, especially when identity is uncertain and coordination is inconsistent. This project framed the problem as a need for a secure, convenient, and inclusive exchange workflow within the university community.

## Target users
We explicitly targeted multiple student groups to reflect diverse needs:
- Students on a budget and those facing financial pressure
- International students who frequently relocate and need short term items
- Students with mobility challenges who benefit from proximity and reduced travel
- Eco conscious students motivated by reuse and waste reduction
These user groups and motivations are documented in the proposal and user requirements work.

## Research questions
What features and workflows are essential for a user centered platform that supports safe, convenient, and accessible item exchanges on campus, and how should the design communicate trust and clarity at each step.

## Research and ideation methods
We used mixed methods to cover breadth and depth:
- Questionnaire and interviews to gather user requirements and motivations, and to validate priority themes such as security and convenience
- Personas, scenarios, and hierarchical task analysis to define critical journeys and scope the design
- Low fidelity prototypes to test early hypotheses before building the high fidelity prototype
This method mix is consistent with early stage product discovery and iterative prototyping.

## Artifacts and deliverables
### Personas, scenarios, and HTA
We created personas and scenario narratives for representative users, then produced an HTA that decomposed core tasks such as sign up and verification, browse and search, post an item, initiate an exchange, and rate and review. This created a clear structure for both design and evaluation.

### High fidelity user flows and prototype in Figma
The high fidelity prototype focuses on three primary workflows, written as task flows with step by step instructions:
1) Sign up and verification
   - University account authentication and two factor verification
   - Profile setup with inclusive options and structured fields
   - Confirmation feedback and entry into the home experience

2) Complete a transaction
   - Explore and search with filters by category, location, and points
   - Item detail view with seller info
   - In app messaging to coordinate pickup details
   - Checkout and transaction confirmation
   - Transaction history and post transaction rating and review

3) Post an item for exchange
   - Title, description, photos, usage condition with quantitative options
   - Availability selection via calendar
   - Point value input and submission confirmation feedback

These flows were chosen because they represent the core end to end experience and the highest risk points for confusion, trust breakdown, and abandonment.

## Usability evaluation
### Method
We ran a usability study using semi structured interviews with six university students. Participants completed the three primary tasks and then provided quantitative ratings and qualitative feedback. Sessions lasted about 30 minutes and were conducted in informal campus settings to encourage natural interaction.

### Metrics captured
- Task completion and failure points per task
- Satisfaction score out of 10 per task group
- Common issues and their frequency across participants
- Qualitative explanation of confusion and suggestions for improvements

### Results summary
Overall results by task:
- Sign up and verification: 6 of 6 completion, average score 7.7
- Completing a transaction: 5 of 6 completion, average score 7.8
- Posting an item: 5 of 6 completion, average score 7.7

Top issues by frequency:
- Confusion with pickup checkboxes in chat: 4 of 6 participants, 67 percent
- Ambiguity in input requirements for location and item description: 4 of 6, 67 percent
- Dense and unorganized design in posting interface: 3 of 6, 50 percent
- Missing transaction status and visible review entry point: 3 of 6, 50 percent
- Difficulty selecting a date range for availability: 3 of 6, 50 percent
- Missing category input field during item posting: 2 of 6, 33 percent
- Navigation inconsistency and redundant fields: 2 of 6, 33 percent
- Lack of point system guidelines: 2 of 6, 33 percent

## What I changed and why
All changes below are directly tied to observed usability breakdowns and participant suggestions.

### Clarify the transaction workflow and reduce confusion
- Remove confusing pickup checkboxes in chat that did not provide useful functionality
- Add clearer transaction status in transaction history and make review entry points visible for completed transactions
- Add a transaction completion confirmation view to prompt review and reduce uncertainty

### Reduce cognitive load in item posting
- Reorganize the posting interface by grouping fields under clear headers such as Item Details, Condition, and Availability
- Add spacing and alignment improvements to reduce the dense layout perception
- Add a preview step so users can verify their listing before submission

### Increase form clarity and error prevention
- Mark required fields with asterisks and use stronger placeholder guidance
- Add an icon and popup with examples for item description so users know what detail is expected
- Provide clearer guidance for the location field to reduce ambiguity

### Improve availability selection
- Replace single day selection with a range selector so users can choose start and end dates in one action, addressing repeated feedback about tedious day by day selection

### Make the point system understandable
- Add a point system overview in the transaction interface and include point explanation during onboarding, addressing confusion about how points are earned and used

## Communication and collaboration
This project produced reusable research artifacts such as consent forms, interview scripts, and evaluation structure. Findings were summarized into a ranked issue list and translated into concrete UI iterations and future work.

## Alignment to UX UI Designer job requirements
This project demonstrates:
- Figma as the primary design tool and delivery of a high fidelity interactive prototype
- Detailed user flows and journeys grounded in personas, scenarios, and HTA
- User research and usability testing, with both quantitative metrics and qualitative synthesis
- Iteration based on feedback to improve usability and satisfaction
- Clear communication of findings and prioritized design decisions

## Next steps
Future work includes expanding participant diversity, especially accessibility focused testing, standardizing the interview protocol for consistency, and adding objective interaction analytics such as click path and error logging to validate improvements over multiple iterations.
