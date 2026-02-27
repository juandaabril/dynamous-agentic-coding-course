# Module 01

> Capabilities, not tools. Learning the basics of AI coding tools is great, and we will cover that. But the real value is learning how to create your own systematic approach to using an AI coding assistant that is reliable and repeatable.

## How to develop your own AI coding workflows

### Primary mental model for AI coding

1. Planning
2. Implementation
3. Validation
4. Iteration

### Step 1: Planning

Start with a "vibe plan":
- Explore ideas, architecture, concepts, and tech stack choices with the AI coding assistant.
- Keep this phase exploratory before enforcing strict structure.

For new projects:
- Research online resources.
- Review previous projects and patterns you can reuse.

For existing projects:
- Analyze the current codebase and documentation first.

#### Layer 1: Foundation planning

Done once and updated rarely:
- Tech stack decisions
- Architecture patterns
- Constraints and conventions
- Stable reference resources

#### Layer 2: Task planning

Done for each feature or task:
- Codebase analysis
- Documentation analysis
- Integration points
- Task-specific rules

### Step 2: Create a structured plan with the "componenets of context engineering"
![components-context-engineering](img/components-context-engineering.png)

The goal is to produce a detailed plan of attack for the AI coding assistant based on your conversation and planning work.

Your plan can include:

- Goals
- Success criteria
- Documentation references
- Task list
- Validation strategies
- Desired codebase structure


### Step 3: Implement and validate

Execute the implementation plan task by task. Most structure should already be set up during planning, so this phase focuses on execution quality.

Trust, but verify.

1. You can allow the AI coding assistant to move quickly, but monitor it to ensure it:
    - Uses tools correctly
    - Reads and edits the right files
    - Manages tasks in the correct order
    - Produces reasoning that matches the planned approach

2. Validate the produced code continuously:
    - Run tests and checks after each meaningful change
    - Compare outcomes against your success criteria
    - Confirm integrations behave as expected

![validate-the-produced-code](img/validate-the-produced-code.png)

### Step 4: Iterate

Use validation results to refine the plan and repeat the cycle:
1. Update context and constraints
2. Adjust the task plan
3. Re-implement where needed
4. Re-validate until the feature is complete


