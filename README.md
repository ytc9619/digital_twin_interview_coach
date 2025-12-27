# Digital Twin Interview Coach

This repository contains an LLM powered RAG workflow and assets for a Digital Twin based AI interview coach designed to personalize Data Analyst and Data Scientist interview preparation. The system combines persona based prompt engineering, curated YouTube and GitHub data ingestion, and retrieval augmented generation to deliver role aware and time constrained learning plans.

## Overview
Technical interviews for early career candidates are often generic and inefficient. Preparation resources rarely address individual backgrounds, skill gaps, or timelines. This project demonstrates how a Digital Twin can simulate a user's profile and produce personalized guidance that is more actionable and aligned with real interview expectations.

## What is Included
| File | Description |
|------|-------------|
| `LLM_full_pipeline.ipynb` | Full end to end code pipeline including ingestion, chunking, embedding, vector store, RAG retrieval, and persona conditioned prompt generation |
| `personalized_interview_coaching_digital_twin.pdf` | Slide deck explaining motivation, system architecture, data strategy, prompt design iterations, evaluation setup, and business implications |

## System Architecture
The system follows a modular workflow:
1. Data ingestion from YouTube and GitHub
2. Transcription and text preprocessing
3. Chunking into vector searchable segments
4. Embeddings created using text embedding models
5. RAG retrieval based on cosine similarity
6. Persona injection using structured role profiles
7. Digital Twin prompt generation and customized coaching output

## Personas and Use Case
Target users include:
- Interns and new graduates
- Early career data professionals
- Individuals preparing for analytics and ML roles with limited time

Outputs include:
- Weekly study plans
- Skill based prioritization
- Behavioral STAR coaching
- Role specific interview question prep

## Evaluation Summary
Two configurations are compared:
- Baseline: Zero shot RAG output
- Digital Twin: Persona conditioned RAG output

The Digital Twin consistently improved:
- Personalization quality
- Actionable guidance
- Clarity and coherence
- Time aware prioritization

## How to Use
1. Open the `LLM_full_pipeline.ipynb` notebook
2. Install required dependencies from the first code cell
3. Add your own persona profile or modify prompts
4. Run queries and generate personalized coaching output

## Future Improvements
- Expand retrieval dataset to more diverse interview content
- Automated rubric scoring using LLM evaluators
- Add UI for candidate onboarding and persona configuration

## Authors
Cynthia Fu  
Eric Huang  
Yurun Guo  
Yi Ting Cheng  
Chao Wang

## License
For academic and demonstration purposes only

