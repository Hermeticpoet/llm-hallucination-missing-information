# Hallucination Evaluation Summary

## Objective

Assess whether the model hallucinates details when presented with prompts containing incomplete, ambiguous, or entirely fictional information.

## Method

A small set of prompts was constructed where key facts were intentionally missing or fabricated. Each prompt tested whether the model would:

- express uncertainty
- request clarification
- or confidently invent details

Outputs were compared across variations to identify consistent hallucination patterns.

## Key Findings

- **Confident fabrication:** The model frequently produced detailed answers for fictional books, treaties, people, and cities.
- **Lack of uncertainty markers:** Responses rarely included phrases indicating ambiguity or missing information.
- **Premise acceptance:** The model accepted undefined or ambiguous terms without hesitation.
- **Authoritative tone:** Hallucinated content was often delivered with high confidence and specificity.

## Conclusion

The model demonstrates a strong tendency to hallucinate when information is missing or fictional. This behaviour appears consistent across multiple prompt types and suggests insufficient uncertainty signalling.

## Recommendations

- Expand rubric criteria to include uncertainty expression and fact‑checking triggers.
- Use clarification‑seeking prompts to reduce hallucination risk.
- Flag high‑confidence responses to ambiguous or fictional inputs for additional review.
