# Module 02

## How to Develop Your Own AI Coding Workflows

### Primary Mental Model for AI Coding

```mermaid
flowchart LR
    A[1. Planning] --> B[2. Implementation] --> C[3. Validation] --> D[4. Iteration]
```

### Step 1: Planning

Start with a "vibe plan":
- Explore ideas, architecture, concepts, and tech stack options with the AI coding assistant.
- Keep this phase exploratory instead of overly structured.

For new projects:
- Research online resources.
- Review previous projects and reusable patterns.

For existing projects:
- Analyze the current codebase and documentation first.

#### Layer 1: Foundation Planning

Done once and updated rarely:
- Tech stack decisions
- Architecture patterns
- Constraints and conventions
- Stable reference resources

#### Layer 2: Task Planning

Done for each feature or task:
- Codebase analysis
- Documentation analysis
- Integration points
- Task-specific rules

### Step 2: Create a structured plan with the components of context engineering

![Components of context engineering](./img/components-context-engineering.png)

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

![Validate the produced code](./img/validate-the-produced-code.png)

#### AI Coding Assistant Validations
See the [Validation Suite](./module02-validation.md)
- Unit testing
- Linting
- Integration testing
- End-to-end testing

#### Human Validation
- Review critical files for correctness and maintainability
- Verify feature behavior against acceptance criteria
- Check UX and edge cases manually
- Confirm documentation updates where needed

### Step 4: Iterate

Use validation results to refine the plan and repeat the cycle:
1. Update context and constraints
2. Adjust the task plan
3. Re-implement where needed
4. Re-validate until the feature is complete

