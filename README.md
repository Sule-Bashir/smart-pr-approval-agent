# smart-pr-approval-agent
Smart PR Approval Agent - UiPath AgentHack 2026 Track 2
## UiPath AgentHack 2026 | Track: Maestro BPMN
### Problem
Finance teams waste 3-5 days processing manual purchase approvals with no audit trail.
### Solution
AI agent that automatically approves low-value requests and escalates high-value requests to managers/finance.
### How It Works
1. User submits purchase request (request_id, amount, requester_name)
2. Agent evaluates amount against business rules
3. Decision: Auto-approve (<$1000), Manager ($1000-5000), Finance (>$5000)
### UiPath Components Used
- Agent Builder (Autopilot)
- Orchestrator
- Action Center
- Maestro BPMN

### Setup Instructions
1. Import agent package to UiPath Orchestrator
2. Configure input arguments: request_id (String), amount (Number), requester_name (String)
3. Start job with JSON input

### Demo Video
https://youtu.be/mAkarrzvpl0?si=pHypqSiVjIUol49g
### Author
Sule Bashir
### License
MIT
