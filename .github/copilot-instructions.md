# GitHub Copilot Custom Instructions for Fabric_llms_txt_repo

This repository contains the following context files:
- `fabric-cli-llms.txt`: Guidance and examples for using the Fabric CLI.
- `fabric-rest-api-llms.txt`: Information and usage patterns for the Fabric REST API and SDKs.
- `fabric-cicd-llms.txt`: Instructions and best practices for Fabric CI/CD and related SDKs.

## How to Use Copilot Effectively in This Repo

When working in this repository, GitHub Copilot should:
- Reference the relevant `.txt` file for context-specific suggestions.
- Use examples and command patterns from `fabric-cli-llms.txt` when generating CLI usage or automation scripts.
- For REST API or SDK-related code, consult `fabric-rest-api-llms.txt` for endpoints, authentication, and integration patterns.
- For CI/CD pipeline automation, deployment, or SDK integration, use the guidance in `fabric-cicd-llms.txt`.

### Special Note on the Term "Workspace"

- If a prompt includes the word "workspace" in the context of Fabric, Copilot should rewrite the prompt to use "Fabric workspace" and treat it as a Fabric resource, not as a VS Code workspace. Avoid confusion between Fabric workspace and VS Code workspace at all times.

## Example Prompts for Copilot

- "Show me how to authenticate and run a command with Fabric CLI."  
  → Copilot should use examples from `fabric-cli-llms.txt`.

- "Generate a Python script to interact with the Fabric REST API."  
  → Copilot should reference `fabric-rest-api-llms.txt` for endpoints and authentication.

- "How do I set up a CI/CD pipeline for Fabric using the SDK?"  
  → Copilot should use `fabric-cicd-llms.txt` for pipeline steps and SDK usage.

## Best Practices

- Always check the corresponding `.txt` file for the most up-to-date usage patterns.
- When in doubt, Copilot should suggest looking at the relevant `.txt` file for detailed instructions.

---

> For maintainers: Update the `.txt` files as Fabric tools and APIs evolve to keep Copilot suggestions accurate and helpful.