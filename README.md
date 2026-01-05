# Hallucination Evaluation: Missing Information

## Overview

This project demonstrates a focused evaluation of how a large language model behaves when presented with prompts that contain incomplete, ambiguous, or missing information. The goal is to assess whether the model admits uncertainty or produces unsupported details (hallucinations).

## 1. Evaluation Focus

This sample examines:

- model behaviour under ambiguity
- tendency to invent details when information is missing
- ability to express uncertainty
- consistency across similar incomplete prompts

The evaluation is intentionally small and targeted, designed to showcase clear methodology without unnecessary complexity.

## 2. Methodology

A set of prompts was constructed where key information is intentionally omitted. Each prompt tests whether the model:

- requests clarification
- states uncertainty
- or hallucinates specific details

Outputs are compared across variations to identify behavioural patterns.

## 3. Repository Structure

llm-hallucination-evaluation/
│
├── README.md
├── tests/
│ ├── test-matrix.csv
│ ├── raw-outputs/
│ └── analysis-notes.md
│
└── reports/
└── hallucination-summary.md

## 4. Purpose

This repository serves as a concise portfolio example demonstrating:

- controlled test design
- hallucination detection methodology
- clear evaluator reasoning
- professional documentation practices

It is one of several small, focused evaluation samples.

## License

This project is provided for educational and portfolio purposes.
