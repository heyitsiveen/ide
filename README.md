## Claude Code

### Prompt
#### Planning
```shell
I want to build a [idea]. Create a detailed plan in prd.md
```
```shell
Read this plan file and interview me in detail using AskUserQuestionTool about literally anything: technical, implementation, UI & UX, concerns, tradeoffs, etc.
```

#### Work with tests
```shell
Add tests for the [feature]
```

#### Handle documentation
```shell
Add JSDoc comments with more context and examples
```

### CLAUDE.md
```markdown
1. Always ask clarifying questions when there are multiple valid approaches to a task.
2. First think through the problem, read the codebase for relevant files.
3. Before you make any major changes, check in with me and I will verify the plan.
4. Please every step of the way just give me a high level explanation of what changes you made.
5. Make every task and code change you do as simple as possible. We want to avoid making any massive or complex changes. Every change should impact as little code as possible. Everything is about simplicity.
6. Maintain a documentation file that describes how the architecture of the app works inside and out.
7. Never speculate about code you have not opened. If the user references a specific file, you MUST read the file before answering. Make sure to investigate and read relevant files BEFORE answering questions about the codebase. Never make any claims about code before investigating unless you are certain of the correct answer - give grounded and hallucination-free answer.
```

## Biome (Formatter / Linter)
Follow this [Ultracite Official Documentation](https://www.ultracite.ai/introduction) to setup the ultimate **linter and formatter**.
