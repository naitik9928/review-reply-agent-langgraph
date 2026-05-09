# Sentiment Analysis & Reply Automation

A LangGraph-based system that automatically analyzes customer reviews and generates appropriate replies based on sentiment (positive/negative).

## Features

- ✅ Sentiment classification (positive/negative)
- ✅ Automatic reply generation for positive reviews
- ✅ Issue diagnosis for negative reviews (issue type, tone, urgency)
- ✅ Conditional workflow routing
- ✅ Structured output with Pydantic

## Tech Stack

- LangGraph / LangChain
- Groq LLM (llama-3.3-70b-versatile)
- Pydantic
- Python 3.13

## Workflow
START → Sentiment Analysis → Conditional Check
↓
Positive → Reply → END
Negative → Diagnose → Reply → END

Built independently without following a tutorial — workflow architecture designed from scratch after understanding LangGraph conditional edges.
