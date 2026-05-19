# Week 1 Plan

## Objective

Build a usable shared language for AI x Web3 with a hackathon bias:

- Know what an LLM can and cannot be trusted to do.
- Understand how context and agent workflow affect execution safety.
- Build a beginner-level Web3 mental model around network, wallet, signature, and contract.
- End the week with one small AI x Web3 project direction.

## Week 1 Reading Map

- Handbook home:
  - https://aiweb3.school/zh/handbook/
- AI basics:
  - LLM: https://aiweb3.school/zh/handbook/ai/llm/
  - Prompt: https://aiweb3.school/zh/handbook/ai/prompt/
  - Context: https://aiweb3.school/zh/handbook/ai/context/
  - Agent: https://aiweb3.school/zh/handbook/ai/agent/
- Web3 basics:
  - Network: https://aiweb3.school/zh/handbook/web3/network/
  - Wallet: use Handbook sidebar entry if direct link is unavailable in the browser cache
  - Cryptography: use Handbook sidebar entry
  - Smart Contract: use Handbook sidebar entry
- Bridge:
  - Agent Workflow: use Handbook sidebar entry

## Daily Time Budget

- 70 min reading
- 60 min note-making
- 60 min small exercise or diagram
- 20 min daily check-in draft

## Day 1

### Focus

- Handbook overview
- LLM

### Why Today

- You already have AI basics, so the goal is not theory depth. The goal is to set a reliability boundary: model output is a candidate, not a fact.

### Tasks

1. Read the Handbook homepage and write down the four-layer map:
   - AI basics
   - Web3 basics
   - AI x Web3 Bridge
   - frontier tracks
2. Read `LLM`.
3. Write one bilingual note:
   - What an LLM is good at
   - What an LLM must not do alone in a high-stakes workflow
4. Add one glossary file in `tasks/` for:
   - token
   - hallucination
   - structured output

### Output

- `daily/YYYY-MM-DD.md`
- one glossary note or short markdown note

## Day 2

### Focus

- Prompt
- Context

### Why Today

- Your hackathon edge will come from building workflows, not just calling a model API. Prompt and context are the minimum control plane.

### Tasks

1. Read `Prompt`.
2. Read `Context`.
3. Write a short note answering:
   - Which information belongs to instruction layer
   - Which information belongs to task layer
   - Which information belongs to fact layer
4. Complete one exercise:
   - design a context spec for a "wallet approval check agent"

### Output

- one context-spec note in `tasks/`
- daily note update

## Day 3

### Focus

- Agent
- Agent Workflow

### Why Today

- This is the bridge between "AI can answer" and "AI can act". For hackathon work, this is where product shape starts to appear.

### Tasks

1. Read `Agent`.
2. Read `Agent Workflow`.
3. Write a one-page flow:
   - user intent
   - model planning
   - tool call
   - validation
   - human confirmation
   - execution
   - audit log
4. Mark which steps can be automated and which steps must stay human-in-the-loop.

### Output

- one workflow note in `tasks/`
- one diagram or bullet flow in `experiments/` or `tasks/`

## Day 4

### Focus

- Network
- Wallet

### Why Today

- As a Web3 beginner, this is the minimum layer you need before discussing any onchain product seriously.

### Tasks

1. Read `Network`.
2. Read `Wallet`.
3. Write down answers to:
   - What is chain id and why does it matter
   - Why the same address can behave differently across networks
   - Why a wallet is not just a login button
4. Make a simple comparison table:
   - mainnet vs testnet
   - EOA intuition vs smart account intuition

### Output

- one comparison note in `tasks/`
- glossary additions: chain id, RPC, wallet, signature

## Day 5

### Focus

- Cryptography
- Smart Contract

### Why Today

- You do not need to become a cryptographer. You need enough intuition to understand signatures, trust boundaries, and contract execution.

### Tasks

1. Read `Cryptography`.
2. Read `Smart Contract`.
3. Write a note explaining in plain language:
   - hash
   - private key vs public key
   - signature
   - contract call
4. Add one risk list:
   - what users think they are signing
   - what the signed message may actually authorize

### Output

- one beginner-friendly explainer note
- one risk checklist draft

## Day 6

### Focus

- Synthesis day

### Tasks

1. Review your notes from Day 1 to Day 5.
2. Draft a mini concept map linking:
   - LLM
   - Context
   - Agent
   - Network
   - Wallet
   - Smart Contract
3. Write one bilingual summary:
   - "What changes when an LLM can trigger Web3 actions?"
4. Create your first hackathon direction note in `hackathon/` using the template.

### Output

- one synthesis note
- one first project brief draft

## Day 7

### Focus

- Reflection and public proof-of-work

### Tasks

1. Review the full week.
2. Pick your strongest project direction.
3. Update `learning-plan.md` if the project focus becomes narrower.
4. Write a week recap in Chinese and English:
   - what you learned
   - what still feels weak
   - what you will build next week
5. Add at least one `handbook-feedback/` record if any concept or structure was unclear.

### Output

- weekly recap note
- one handbook feedback record if applicable

## Minimum Deliverables By End Of Week

- 5 daily notes
- 3 to 5 glossary or concept notes
- 1 context spec
- 1 agent workflow note
- 1 week recap
- 1 first hackathon project brief

## Stretch Deliverables

- One toy demo:
  - input: a user asks whether a wallet action is safe
  - output: a structured checklist with chain, contract, spender, risk, and confirm step
- One visual flow diagram for an AI x Web3 agent

## Check-in Angle

Use this framing in daily check-ins:

- what I read
- what concept boundary became clearer
- what I turned into a note or artifact
- what confused me enough to become Handbook feedback

## End Of Week Self-Test

If you can answer these without hand-waving, Week 1 is successful:

1. Why is LLM output not enough for a system that can trigger transactions?
2. What is the difference between context, memory, and knowledge base?
3. Why does network choice affect UX, risk, and debugging?
4. Why is a wallet closer to identity plus signature than to a login button?
5. Which parts of an AI x Web3 workflow must usually stay human-in-the-loop?
