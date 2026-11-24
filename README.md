# llmops-rag

Prompts and configuration for the LLMOps Bootcamp RAG application, versioned in Git.
This repository grows lab by lab into the capstone.

## Layout
- `prompts/` versioned prompt files (`<name>.v<major>.yaml`, with a `version` field)
- `config/` application configuration

## Workflow
1. Create a branch: `git switch -c feature/<change>`
2. Edit a prompt and bump its `version`
3. Open a pull request describing what changed and why
4. Review the diff, then merge to `main`
