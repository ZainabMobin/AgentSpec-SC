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

Number | Rubric | Owner(s) | Status | Is it implemented  | Will we Implement it
-|-|-|-|-|-
1 | [Software Principles and UML](./docs/1_softPrinciplesUML.md) | - | -  | - | -
2 | [Static Checking](./docs/2_staticChecking.md) | - | - | - | -
3 | [Testing & Partitions](./docs/3_testing.md) | - | - | - | -
4 | [Code Review and Version Control](./docs/4_codeReview.md) | - | - | - | -
5 | [Specifications](./docs/5_specifications.md) | - | - | - | -
6 | [Debugging](./docs/6_debugging.md) | - | - | - | -
7 | [Immutability and Mutability](./docs/7_immutability.md) | - | - | - | -
8 | [Recursion](./docs/8_recursion.md) | - | - | - | -
9 | [Recursive Data Types, Regex and grammar](./docs/9_recursiveDataTypeRegexGrammar.md) | -  | - | -| -
10 | [ADTs and Invariants](./docs/10_ADTsInvriants.md) | - | - | - | -
11 | [Parser generator and ANTLR grammar](./docs/11_parserANTLR.md) | - | - | - | -
12 | [Traversing Parse Tree and AST](./docs/12_ASTtraversal.md) | - | - | - | -
13 | [Concurrency](./docs/13_concurrency.md) | - | - | - | -
14 | [Little Languages](./docs/14_littleLanguages.md) | - | - | - | -