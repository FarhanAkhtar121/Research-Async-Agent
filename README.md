# Research Async Agent

A system for conducting parallel asynchronous research tasks using AI agents to efficiently gather and synthesize information.

## Features

- Asynchronous search operations for efficient data retrieval
- Parallel execution of multiple research tasks
- AI-driven synthesis and summarization of research findings
- Structured output in JSON and Markdown formats

## Requirements

- Python 3.8+
- praisonaiagents
- duckduckgo_search
- pydantic

## Usage

```python
# Run the main application
python app.py
```

## How It Works

This system uses two specialized AI agents:

1. **AsyncSearchAgent**: Performs parallel searches and returns structured results
2. **SummaryAgent**: Synthesizes information from multiple search results into a cohesive research document

The system allows for efficient parallel execution of research tasks and produces well-structured research documents.

## Output

Results are saved to `/tmp/research.md` in JSON format.