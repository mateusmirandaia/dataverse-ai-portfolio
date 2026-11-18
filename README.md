# Dynamics 365 / Dataverse + AI Portfolio

I'm Mateus Miranda, a senior Dynamics 365 CE / Dataverse engineer with more than 10 years working exclusively with Dynamics. This repository is the index of projects that show how I bring AI into business applications — not as a bolt-on demo, but integrated with the platform's security model, extensibility points and ALM.

## Projects

| Project | What it shows | Stack | Link |
| --- | --- | --- | --- |
| dataverse-ai-plugin | A server-side plugin that enriches Dynamics 365 cases with Azure OpenAI: classification, sentiment and summary written back to the record. | C#, .NET, Dataverse SDK, Azure OpenAI | [repo](https://github.com/mateusmirandaia/dataverse-ai-plugin) |
| pcf-ai-assistant | A PCF control that suggests AI-generated replies inside model-driven forms, calling Azure OpenAI through an Azure Function proxy so no keys reach the browser. | TypeScript, React, PCF, Azure Functions | [repo](https://github.com/mateusmirandaia/pcf-ai-assistant) |
| dataverse-mcp-server | An MCP server that lets AI agents query and update Dataverse safely — read-only by default, writes only when explicitly enabled. | Python, MCP, Dataverse Web API | [repo](https://github.com/mateusmirandaia/dataverse-mcp-server) |
| crm-rag-agent | A RAG agent that answers questions over CRM data with cited sources, plus an offline mode and an evaluation harness. | Python, FastAPI, Azure OpenAI | [repo](https://github.com/mateusmirandaia/crm-rag-agent) |
| power-platform-alm | Power Platform ALM with GitHub Actions and the pac CLI: export and unpack, build, solution checker, and gated deploys to TEST and PROD. | GitHub Actions, pac CLI, Power Platform | [repo](https://github.com/mateusmirandaia/power-platform-alm) |

All projects are under active development.

## Coming next

Planned and not yet published:

- **Copilot Studio extensions** — agents and actions that build on Dataverse data and the projects above.
- **Custom connectors** — exposing the AI services as Power Platform connectors for makers.

## How I build

- **Tested** — unit tests for plugin and service logic, with Dataverse dependencies mocked.
- **CI/CD** — every repo builds and tests in GitHub Actions; solutions move through gated environments.
- **Secure** — no secrets in code; credentials live in environment variables or pipeline secrets, and integrations use least-privilege access.
- **Platform-aware** — respects Dataverse security roles, execution limits and supported extensibility patterns.
- **Documented** — every repo explains the problem, the architecture and how to deploy it.

## More

- Profile: [github.com/mateusmirandaia](https://github.com/mateusmirandaia)
- Python + AI projects: [python-ai-portfolio](https://github.com/mateusmirandaia/python-ai-portfolio)
