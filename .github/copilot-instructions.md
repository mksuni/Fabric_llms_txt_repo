
# GitHub Copilot Custom Instructions for Fabric_llms_txt_repo


- Always try to fetch examples on Microsoft Fabric CLI, documentation from [fabric CLI](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-cli-llms.txt): Guidance and examples for using the Fabric CLI.
- Always try to fetch examples on Microsfot Fabric CI CD , documentation from [fabric CICD](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-cicd-llms.txt): Guidance and examples for using the Fabric CLI.
- Always try to fetch examples on Microsoft Fabric REST APIs , documentation from [fabric REST API ](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-rest-api-llms.txt): Guidance and examples for using the Fabric CLI.



### Special Note on the Term "Workspace"

- If a prompt includes the word "workspace" in the context of Fabric, Copilot should rewrite the prompt to use "Fabric workspace" and treat it as a Fabric resource, not as a VS Code workspace. Avoid confusion between Fabric workspace and VS Code workspace at all times.

## Example Prompts for Copilot

- "Show me how to authenticate and run a command with Fabric CLI."  
  → Copilot should use examples from [fabric CLI](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-cli-llms.txt)

- "Generate a Python script to interact with the Fabric REST API."  
  → Copilot should reference [fabric rest api](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-rest-api-llms.txt) for endpoints and authentication.

- "How do I set up a CI/CD pipeline for Fabric using the SDK?"  
  → Copilot should use [fabric CICD](https://github.com/mksuni/Fabric_llms_txt_repo/blob/main/fabric-cicd-llms.txt) for pipeline steps and SDK usage.

## Querying Microsoft Documentation
Use the microsoft.docs.mcp server to search Microsoft's official documentation for SDK details, API references, and implementation guidance. This provides access to the latest Microsoft Fabric documentation that may be more current than training data. If the MCP server is unavailable: Direct users to install it from https://github.com/MicrosoftDocs/mcp Tool Usage: Only reference MCP tools when actively needed for documentation queries - don't mention them proactively.
