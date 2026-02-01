ai_platform/
├── registry/
│   ├── model_registry.py
│   ├── model_metadata.yaml
│   └── model_selector.py
├── auth/
│   └── authapikey.py
├── agents/
│   └── sales_agent.py
└── main.py



-------------------

gpt-4.1:
  provider: openai
  reasoning: 5
  speed: 3
  cost: high
  context_window: 128000
  supports_tools: true
  supports_json: true
  best_for:
    - planning
    - reasoning
    - multi-agent

gpt-4o:
  provider: openai
  reasoning: 4
  speed: 4
  cost: medium
  context_window: 128000
  supports_tools: true
  supports_json: true
  best_for:
    - multimodal
    - chat
    - agents

gpt-4o-mini:
  provider: openai
  reasoning: 3
  speed: 5
  cost: low
  context_window: 128000
  supports_tools: true
  supports_json: true
  best_for:
    - fast-response
    - background-tasks

