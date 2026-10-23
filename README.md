# Hi there, I'm Victor Vakareev 👋

### Senior Test Automation Engineer | AI Quality & Agent Testing | C#, Playwright & Python

I make large, unpredictable software testable. For 5+ years I've worked on enterprise test automation in C#/.NET, on a suite of **19,000 tests that runs every night**. Since 2026 I've been retraining in AI engineering, applying the same discipline to **LLM agents**, whose output is non-deterministic by design. Before software I ran construction and print production operations, which is where my production-first mindset comes from.

### 🛠️ What I do at work
- **Enterprise test automation at scale:** extending and maintaining a C# framework on **Bellatrix**, **Selenium**, **Playwright** and **NUnit**: 16,000+ system tests and 3,000 UI component tests, run nightly.
- **Speed:** cut regression run time by about **40%** by running the suite in parallel across Jenkins pipelines.
- **Safety net for big changes:** the suite carried the application through upgrades to **.NET 6** and **.NET 10** and a SQL database upgrade. Since all test data is created through the API, it also caught API contract changes early.
- **Multi-tenant testing:** one suite running against many customer tenants, each with its own data and configuration, including linked tenants that trade with each other.
- **Reliability:** turning flaky UI tests into stable ones: Locator APIs over raw selectors, auto-waiting instead of `Thread.Sleep`, small reusable components over monolithic page objects.
- **CI/CD and security:** **Azure DevOps**, **Jenkins** and **GitHub Actions** pipelines, secrets in Azure Key Vault and HashiCorp Vault, dependencies through JFrog Artifactory.
- **AI-assisted work:** **GitHub Copilot Business** every day for test code, refactoring and pipelines, under enterprise data controls with mocked test data only.

### 🧪 AI engineering & testing (learning projects, 2026)
These are learning projects, not production systems. Each one is tested properly.
- **[docchat-multi-agent-rag](https://github.com/ViktorVakareev/docchat-multi-agent-rag):** multi-agent RAG in **LangGraph**, with a verifier agent that checks every citation and number in code against what was retrieved, plus a fixed task eval and separate retrieval metrics (hit rate, nDCG).
- **LangGraph agents:** ReAct and Reflexion agents with human-in-the-loop, checkpoints and evals against the course baselines.
- **[pydantic-structured-tool-calls](https://github.com/ViktorVakareev/pydantic-structured-tool-calls):** a validate-and-repair loop for LLM tool arguments, with an eval harness that scores valid vs exact output.
- **[llm-safety-mutation-testing](https://github.com/ViktorVakareev/llm-safety-mutation-testing):** safety policies as automated tests, hardened with **mutation testing** (`mutmut`), raising the mutation score from 50% to 100%.
- **Azure agents:** Azure AI Foundry, Azure OpenAI, Semantic Kernel (plugins, memory), Bot Framework and Microsoft Graph connectors, each with a real **pytest** suite.

### 🧭 Test automation showcases
- **[saucedemo-qa-assignment](https://github.com/ViktorVakareev/saucedemo-qa-assignment):** C# Playwright + NUnit: manual test cases in Gherkin, a bug report with evidence, and a CI gate that separates known defects.
- **[playwright-ts-multilayer-tests](https://github.com/ViktorVakareev/playwright-ts-multilayer-tests):** TypeScript Playwright across UI and API layers.

### 📈 Currently learning
- 🐳 **Docker and Kubernetes** (IBM): containers, orchestration, OpenShift.
- 📊 Next: running the docchat evals against a live model and adding an evaluation and observability tool (Promptfoo, LangSmith or Langfuse).

### 🎓 Certifications
- ISTQB® Certified Tester: *Foundation Level (CTFL)* and *AI Testing (CT-AI)*
- Microsoft: *AI Agent Fundamentals with Azure AI Foundry*
- Microsoft: *Code and Framework-Based Agent Development*
- Coursera: *Test and Secure Your AI Code*
- Coursera: *Safeguard LLM Outputs: Test and Evaluate*
- IBM: *Fundamentals of Building AI Agents*
- IBM: *Agentic AI with LangChain and LangGraph*

### 🧰 Tech stack
**Test automation:** `C#` `.NET` `Playwright` `Selenium` `NUnit` `Bellatrix` `REST API` `SQL` `Allure` `qTest`
**CI/CD & DevOps:** `Azure DevOps` `Jenkins` `GitHub Actions` `Key Vault` `HashiCorp Vault` `Artifactory` `Docker` `Kubernetes (learning)`
**AI (learning projects):** `Python` `pytest` `mutmut` `LangChain` `LangGraph` `RAG` `Pydantic` `Azure AI Foundry` `Azure OpenAI` `Semantic Kernel` `Bot Framework` `Microsoft Graph` `Ollama`

### ⚡ Beyond the Terminal
- ⛰️ Pushing limits through mountain ultra-marathons and CrossFit.
- 🎸 Coding to a solid metal soundtrack (From Ashes to New, Amaranthe, Beyond the Black, Evanescence).
- 📚 Recharging with sci-fi, horror/adventure movies, and the dark fantasy worlds of Vasil Popov.

### 📫 Let's Connect
- **Email:** [v.vakareev@gmail.com](mailto:v.vakareev@gmail.com)
- **LinkedIn:** [victor-vakareev-a5619b97](https://www.linkedin.com/in/victor-vakareev-a5619b97/)
- **Collaboration:** Always open to discussing AI quality and LLM evaluation, scalable Playwright architectures, or the best trail running gear!

<!---
ViktorVakareev/ViktorVakareev is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
