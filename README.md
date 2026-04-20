# Lead Intake & Qualification Workflow

## Business context
Many business teams receive inbound requests that vary in relevance, urgency, completeness and quality. This often creates avoidable manual review effort, inconsistent qualification and unclear follow-up.

## Workflow purpose
This project explores an AI-supported workflow for structuring inbound lead information, identifying relevant qualification signals and improving clarity before follow-up or handoff.

## Expected business benefit
Reduces repetitive manual review, improves consistency in early lead handling and helps teams access sales-relevant information faster.

## In scope for v0.2
- intake from written inbound requests
- extraction of relevant qualification signals
- basic prioritization logic
- clearer follow-up or handoff preparation

## Not in scope for v0.2
- CRM integration
- automated outreach
- production deployment
- final scoring model validation

## Initial workflow hypothesis
1. Capture incoming inquiry text
2. Extract relevant qualification signals
3. Structure the information into a consistent review format
4. Assign an initial qualification category
5. Prepare a clearer basis for follow-up or handoff

## Initial qualification signals
The first review logic in this workflow focuses on a small set of practical qualification signals:

- source of inquiry
- clarity of intent
- completeness of information
- urgency signals
- fit indicators based on stated need or context
- missing information that affects follow-up quality

## Initial review categories
At this stage, the workflow uses simple early-stage review categories:

- **high fit**  
  inquiry is relevant, sufficiently clear and ready for follow-up

- **unclear**  
  inquiry shows potential but lacks clarity or key information

- **low fit**  
  inquiry is weakly relevant, poorly matched or too incomplete for meaningful prioritization

## Notes for the next iteration
The current logic is intentionally simple. A later version should test how to distinguish between urgency, actual fit and missing information more reliably.

## Early friction points
- incomplete inquiry data
- ambiguous intent
- over-scoring based on limited signals
- difficulty separating urgency from actual fit

## Validation status
Early portfolio version. Workflow concept only. Not production-tested.
