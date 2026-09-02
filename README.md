# Hi there, I'm Matteo Pagani! 👋

**Cloud Solution Architect · ABS Tech Success @ Microsoft** · Como, Italy · [developerscantina.com](https://www.developerscantina.com)

## About Me

I'm a Cloud Solution Architect in the ABS Tech Success team at Microsoft, where I envision, drive and scale innovative projects across the AI agent and Microsoft 365 ecosystems. Most of my work these days sits at the intersection of **AI agents, agent governance and the Model Context Protocol** — building agents with .NET, Python and TypeScript, then making them observable, secure and accountable inside an organization.

I have a strong passion for knowledge sharing, which leads me to support the developer community by writing articles, blog posts and books, and by speaking at conferences around the world. Before joining Microsoft, I was a Microsoft MVP in the Windows Development category and a Nokia Developer Champion for almost 5 years.

📝 I write about all of this on my blog, [**The Developer's Cantina**](https://www.developerscantina.com), where you'll also find write-ups behind many of the repos below.

## 🛠️ Technologies & Tools

- **AI & Agents**: Microsoft Agent 365, Microsoft Agent Framework, Semantic Kernel, LangChain, Microsoft 365 Agents SDK, Copilot Studio, Azure AI Foundry, Azure OpenAI
- **Protocols & Integration**: Model Context Protocol (MCP), Microsoft Graph, Copilot connectors, declarative agents
- **Cloud & Platform**: Azure, Power Platform, Microsoft Entra ID, Azure Functions, .NET Aspire
- **Languages**: C# / .NET, TypeScript, Python, JavaScript
- **Web & Apps**: ASP.NET Core, Blazor, React
- **DevOps & CI/CD**: GitHub Actions, Azure DevOps

## 🚀 What I'm working on

### Agent 365 — bringing your own agents under enterprise governance

| Repository | What it is |
| --- | --- |
| [**agent365-labs**](https://github.com/qmatteoq/agent365-labs) | Hands-on labs that take an agent with zero Agent 365 code and onboard it end to end: Entra identity, Defender / Purview reporting, user attribution, and Microsoft 365 data via Work IQ MCP servers. [Read the labs →](https://qmatteoq.github.io/agent365-labs) |
| [**agent365-runbook**](https://github.com/qmatteoq/agent365-runbook) | Step-by-step runbooks for onboarding your own agent into Microsoft Agent 365, driven in natural language through the Agent 365 Skills for your AI coding assistant. |
| [**agent365-demos**](https://github.com/qmatteoq/agent365-demos) | Demo agents for Agent 365 onboarding — Microsoft Learn MCP research assistants built with different stacks. |
| [**langchain-agent365**](https://github.com/qmatteoq/langchain-agent365) | A LangChain agent in Python wired up with the Microsoft Agent 365 SDK: observability, notifications, MCP tools and hosting patterns. |
| [**BeConnected2026-Agent365**](https://github.com/qmatteoq/BeConnected2026-Agent365) | The same conversational agent implemented on two different stacks, to show what Agent 365 onboarding looks like regardless of your technology. |

### Model Context Protocol

| Repository | What it is |
| --- | --- |
| [**MCP-Client-Server-for-agents**](https://github.com/qmatteoq/MCP-Client-Server-for-agents) ⭐ | A full MCP client/server implementation in .NET over both HTTP Streaming/SSE (with .NET Aspire, ASP.NET Core and a Blazor + Semantic Kernel client) and stdio. Documented in a blog series. |
| [**MCP-FederatedConnector**](https://github.com/qmatteoq/MCP-FederatedConnector) | A .NET 10 MCP server secured with Microsoft Entra ID and registered as a federated Copilot connector for Microsoft 365 Copilot. |
| [**expense-mcp-app**](https://github.com/qmatteoq/expense-mcp-app) | An MCP server with an interactive expense-submission widget (MCP app / SEP-1865), packaged both as a declarative agent action and a Copilot Cowork plugin. |
| [**Flights-MCP-Server**](https://github.com/qmatteoq/Flights-MCP-Server) | An ASP.NET Core flight search API exposed to AI agents through MCP, with OpenAPI docs. |

### Copilot Studio & Microsoft 365 Copilot

| Repository | What it is |
| --- | --- |
| [**copilotstudio-feedback**](https://github.com/qmatteoq/copilotstudio-feedback) | A web app to browse and search the feedback users leave on your Copilot Studio agents, reading the `ConversationTranscript` table straight from Dataverse. |
| [**copilotstudio-webchat-react**](https://github.com/qmatteoq/copilotstudio-webchat-react) | Connecting a Copilot Studio agent to a custom React WebChat client via the Power Platform API and Entra ID. |
| [**CustomAgentInDA**](https://github.com/qmatteoq/CustomAgentInDA) | How to wrap an agent built with any technology into a declarative agent for Microsoft 365 Copilot. |
| [**GraphConnectorAspire**](https://github.com/qmatteoq/GraphConnectorAspire) | A custom Graph connector built with .NET Aspire and a microservices approach, ingesting RSS content into a Microsoft 365 tenant with a Blazor UI. |
| [**outlook-businessmails-openai**](https://github.com/qmatteoq/outlook-businessmails-openai) ⭐ | An Outlook add-in that turns a plain sentence into a full business email using OpenAI. |

### AI orchestration

| Repository | What it is |
| --- | --- |
| [**SemanticKernel-Demos**](https://github.com/qmatteoq/SemanticKernel-Demos) ⭐ | My most popular repo: a growing series of samples for Semantic Kernel, Microsoft's library to orchestrate AI workflows and build agents. |
| [**github-maf-agent**](https://github.com/qmatteoq/github-maf-agent) | Two .NET 10 chat apps on Microsoft Agent Framework — one authenticating directly against the GitHub MCP endpoint, one backed by Azure AI Foundry Agent Service. |
| [**TicketApi**](https://github.com/qmatteoq/TicketApi) | A simple ticketing API (Azure Functions, .NET 8) handy as a backend when you need something realistic for agents and plugins to call. |

### 🗂️ Conference demos

[**NetConf2025**](https://github.com/qmatteoq/NetConf2025) · [**WPC2025-MultiAgent**](https://github.com/qmatteoq/WPC2025-MultiAgent) · [**WPC2025-CopilotAgent**](https://github.com/qmatteoq/WPC2025-CopilotAgent) · [**Codemotion2025**](https://github.com/qmatteoq/Codemotion2025) · [**CopilotPartnerShow**](https://github.com/qmatteoq/CopilotPartnerShow)

### 📚 From the Windows & Xamarin days

Still around and still useful if that's your world: [**DesktopBridge**](https://github.com/qmatteoq/DesktopBridge) ⭐ (MSIX packaging samples) · [**DesktopBridgeHelpers**](https://github.com/qmatteoq/DesktopBridgeHelpers) ⭐ (detect if an app runs packaged as MSIX) · [**UWP-MVVMSamples**](https://github.com/qmatteoq/UWP-MVVMSamples) ⭐ · [**XamarinForms-Prism**](https://github.com/qmatteoq/XamarinForms-Prism) ⭐ · [**Prism-UniversalSample**](https://github.com/qmatteoq/Prism-UniversalSample)

## 📈 GitHub Stats

![Matteo's GitHub stats](https://github-readme-stats.vercel.app/api?username=qmatteoq&show_icons=true&theme=radical)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=qmatteoq&layout=compact&theme=radical&langs_count=8)

## 📫 Get in Touch

- 🌐 Blog: [The Developer's Cantina](https://www.developerscantina.com)
- 💼 LinkedIn: [@matteopagani](https://linkedin.com/in/matteopagani)
- 🐦 X: [@qmatteoq](https://twitter.com/qmatteoq)
- 🧵 Threads: [@qmatteoq](https://threads.net/@qmatteoq/)
