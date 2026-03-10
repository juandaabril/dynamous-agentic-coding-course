# Module 03: Global Rules for AI Coding

Global rules - the core of layer 1 planning. The stable foundation that is auto-loaded into every AI session

## Layer 1 - Project Planning (Done once, update rarely)
- Tech stack decisions
- Architecture patterns
- Constraints + conventions
- Creating stable resources

## Layer 2 - Task Planning (Done for each feature/task)

- Codebase analysis
- Document analysis
- Integration points
- Task specific rules

## Global Rules

Every AI Assistant supports global rules
- CLAUDE.MD - Claude Code
- AGENTS.MD - Codex, Cursor, Gemini CLI

> AGENTS.MD is becoming the universal standard
> - README.md is for humans to understand a codebase
> - AGENTS.MD is for AI to understand a codebase


> Your global rules is your day 1 onboarding for your coding assistant.

### What to Include in Global Rules

![hat-to-include-global-rules](./img/what-to-include-global-rules.png)

### What not to include with Global Rules
- Universal knowledge not specific to your project
- Workflow/commands (that's next module)
- Anything very specific to your task
- Anything that seriously bloats the rules

Global rules should apply to ANY task
-> Layer 1 planning: entire codebase task
-> Layer 2 planning - task specific context

If anything in your global rules changes a lot, it doesn't belong

### Why do Global Rules Matter?

Global rules help solve the "Context Loading Tax"
Every session, the coding agent starts with zero project knowledge.

**Approach 1 for Context Loading: Manual**
- You explain the codebase every session (or ask AI to reread)
- You pay the tax every session
- Cost: at least 5-10 minutes per session
- Pattern: explain -> work -> next session -> explain again
- Cumulative cost: hours and hours

**Approach 2: Front Loading Context**

- You pay the tax once (creating global rules)
- System automatically loads context every session
- Cost: 30-60 minutes once to document (plus easy maintenance)
- Pattern: auto-load -> work -> next session -> auto-load
- Cumulative benefit: hours saved


### Front Loading Context is More than Global Rules

Global rules = day 1 employee onboarding | Dynamic context = department training | Layer 2 planning = this week's assignment

### More Important Model for Global Rules

#### Layer 1 Planning has Two Loading Strategies

**Layer 1 - Project Planning**
(done once, update rarely)

- Tech stack decisions
- Architecture patterns
- Constraints + conventions
- Creating stable resources

**Loading Strategy #1 - Automatic**
This is your global rules
- Stable project knowledge
- Very rarely changes
- Highest level info
- For every session

**Layer 2 - Task Planning**
(done for each feature/task)

- Codebase analysis
- Documentation analysis
- Integration points
- Task specific rules

**Loading Strategy #2 - As Needed**
Documents used by your system

- Still project knowledge
- Still changes very rarely
- More specific instructions
- For specific task types