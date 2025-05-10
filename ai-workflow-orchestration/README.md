# AI Workflow Orchestration

This repository contains a framework for orchestrating AI-driven workflows across marketing, sales, and course development teams.

## Directory Structure

- `marketing/`: Marketing team workflows and content
- `sales/`: Sales team workflows and content
- `courses/`: Course development team workflows and content
- `knowledge/`: Shared knowledge base in JSON manifest format
- `.github/`: CI/CD workflows and validation scripts

## Setup

1. Clone this repository
2. Install dependencies: `pip install jsonschema pyyaml`
3. Run validation: `python .github/scripts/validate_toc.py`

## Usage

Each team has its own workflow defined in `config.yaml`. Workflows are triggered by GitHub events (labels, issues) or on a schedule.

## License

Internal use only.
