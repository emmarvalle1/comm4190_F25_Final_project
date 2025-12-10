# Read Me
RenovAI is an AI-powered home renovation and improvement platform that helps homeowners move seamlessly from idea → design → product selection → contractor hiring → project execution using multimodal input (images + measurements).

The system leverages:
- Large Language Models (LLMs)
- Computer Vision
- Structured Data Tools (pricing, catalogs, contractor graphs)
- Workflow-based AI orchestration

RenovAI solves a major real-world problem: decision paralysis and fragmentation in home renovation planning.


## Notebook Structure:
/RenovAI
├── notebooks/
│   └── RenovAI_Workflow_Notebook.ipynb
│       - Workflow diagrams
│       - LangGraph-style implementation
│       - Scenario testing
│       - Adversarial evaluation
│
├── src/
│   ├── tools/              # Vision, pricing, defect detection, matching
│   ├── workflows/          # Router, planners, executors
│   └── prompts/            # System + tool prompts
│
├── data/
│   └── samples/            # Sample catalogs, contractor lists, test images
│
├── tests/
│   └── scenarios/          # MS#2 and MS#3 inputs + expected outputs
│