# Dependencies and Quick Run

Need to have Ollama installed for current local execution

### Python venv
```bash
# create python virtual env
python3 -m venv venv
source venv/bin/activate
pip install -r requirement.txt
ollama pull qwen3.5-coder:4b # local model
python3 agentSpec/src/code_agent.py # run the code-agent
```

# Project Directory

- `docs/` folder documents work done on each ruric in markdown files
- `agentSpec/` is the original fork with necessary changes for running


```
.
├── agentSpec
├── docs
│   └── rubric1.md
└── README.md
```

# Rubric checklist Overview

Will be populated as rubrics are covered

Number | Rubric | Is it implemented  | Will we Implement it
-|-|-|-
