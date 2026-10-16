# Awesome-API-Mocking

## Top API Mocking Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Request Matching, Stateful Simulation & Contract-First Workflows*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **API Mocking**. These tools enable developers to simulate API behavior before dependencies are ready—testing edge cases, validating contracts, and unblocking parallel work without waiting on live services.



**Examples** include WireMock, Mockoon, Beeceptor, MockServer, Postman Mock Server, Stoplight Prism, Microcks, Apidog, ReadyAPI Virtualization, and MockLab (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local-first mocking, and open simulation—ideal for developers, QA engineers, and platform teams seeking transparent, vendor-independent API mocking.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[WireMock Cloud](https://wiremock.io/)**  

  **The industry standard for scalable API simulation** with collaboration, advanced features, and AI . Features **stateful mocking, CSV or database import, contract-based validation, chaos testing, and rate limit simulations** . **Hosted/hybrid/on-prem deployment** with built-in versioning, shared API mocks, and team collaboration/ACLs . **Free tier**: 1,000 calls/month, 3 mock APIs . **Whole-API chaos injection** (random latency/errors across all traffic, no per-stub setup) is a capability **only WireMock Cloud provides** among compared tools .



- **[Beeceptor](https://beeceptor.com/)**  

  **Instant mock server with AI-powered OpenAPI mocking** . Upload an OAS file and get **realistic, contextual responses** in under a minute—product names, people names, addresses, SSNs—using AI and **300+ built-in data generators** . **Custom response overrides** let you control specific fields for predictable testing . **Forward Proxy** intercepts outbound traffic for inspection and selective mocking of third-party APIs . **Pricing**: Free (50 req/day, 3 rules), Individual **$10/month** (15,000 req/month, 50 rules), Team **$25/month** (100,000 req/month, 250 rules), Scale **$99/month** (1M+ req/month, 500 rules) .



- **[Postman Mock Server](https://www.postman.com/)**  

  **Cloud and local mock servers** from saved collection examples . **Local Mocks** (Postman Desktop) let you simulate a real API server directly from your Git-enabled local project—work against mocked responses in the same branch where you're making API changes . **Cloud Mocks** for collaboration and sharing . **Free plan**: unlimited cloud and local mock servers . **Limitation**: Only HTTP collections supported—multi-protocol collections can't be turned into a mock server .



- **[Apidog](https://apidog.com/)**  

  **All-in-one API development platform** with design, debugging, testing, mocking, and documentation. Features **OpenAPI support** and **team collaboration**.



- **[ReadyAPI Virtualization](https://smartbear.com/product/ready-api/)**  

  **Enterprise service virtualization** from SmartBear. Features **protocol support across REST, SOAP, JMS, JDBC, and more** . **The most enterprise-focused option** for complex virtualization needs.



- **[MockLab](https://www.mocklab.io/)**  

  **Hosted WireMock service**—the creator of WireMock runs it as a managed service . **The simplest path to WireMock functionality** without self-hosting.



## Open-Source GitHub Projects



- **[Mockoon](https://github.com/mockoon/mockoon)**  

  **The easiest and quickest way to run mock APIs locally** (MIT) . **7,000+ GitHub stars** . **No remote deployment, no account required, open source** . **Desktop application** for macOS, Windows, and Linux . **CLI** (`mockoon-cli`) deploys mocks anywhere—**GitHub Action available** for CI/CD integration . **Mock samples** for popular APIs . **The most accessible open-source API mocking tool**—download, start, mock . **Best for**: individual developers, local development, quick prototyping without cloud dependency .



- **[WireMock (OSS)](https://github.com/wiremock/wiremock)**  

  **The industry standard for scalable API simulation** (Apache-2.0) . **The most powerful open-source API mocking tool** for precise request matching . **Runs as standalone server, embedded library, Docker container, or Testcontainers module** . **Request matching on URL patterns, headers, query parameters, cookies, and request body content** . **Response templating with Handlebars** . **Record & Playback**—capture real service interactions and replay them . **Fault simulation**—network faults, delays, malformed responses . **Request verification**—assert your application made expected calls . **Extensible** with custom matchers, transformers, and admin API extensions . **JUnit and testing framework integrations** . **Best for**: automated test suites, JVM projects, teams needing precise request matching inside CI/CD pipelines .



- **[MockServer](https://github.com/mock-server/mockserver)**  

  **Open-source HTTP mock server with advanced request matching and proxying** (Apache-2.0) . **Supports OpenAPI request matching**—match against an operationId instead of individual fields . **Body matchers** for JSON, XML, JSON Schema, XPath, and binary . **Interactive Breakpoints**—pause live HTTP exchanges (including SSE, gRPC, WebSocket, GraphQL) mid-flight, inspect/modify them, and continue, drop, or inject . **Chaos testing**—inject errors, latency, and outages with declarative chaos profiles . **CRUD Data Store**—auto-generate a full REST CRUD API over an in-memory JSON store with a single PUT . **Record & Replay** as a proxy . **Clients for Java, JavaScript, Python, Ruby, Go, .NET, Rust, and PHP** . **Best for**: chaos engineering, multi-protocol mocking, teams needing interactive breakpoints .



- **[Stoplight Prism](https://github.com/stoplightio/prism)**  

  **Open-source HTTP mock and validation server from Stoplight** (Apache-2.0) . **Generates dynamic mock responses and validates requests against OpenAPI specifications** . **The design-first approach to mocking**—your OpenAPI spec is the source of truth, and Prism enforces it . **Best for**: teams practicing spec-first API design, validating that implementations match contracts .



- **[Microcks](https://github.com/microcks/microcks)**  

  **CNCF Sandbox project for API mocking and testing** (Apache-2.0) . **100% open source, community-driven** . **Multi-protocol support**: OpenAPI, GraphQL, gRPC, SOAP, and more . **Mock from API standards**—leverage OpenAPI specs, GraphQL schemas, and collections to get free mocks . **MCP-enabled mocks** (v1.12.0)—automatically translates API mocks into **Model Context Protocol aware endpoints** for AI agents . **Git integration** for auto-discovery of new API versions . **Testcontainers module** for integration tests . **Best for**: Kubernetes-native teams, multi-protocol mocking, AI agent integration .



- **[JSON Server](https://github.com/typicode/json-server)**  

  **The most literal answer to "mock a REST API in seconds"** (MIT) . **Write a JSON file, run one command, get full CRUD endpoints** . **Built-in filtering, sorting, and pagination** via query parameters . **Automatically saves changes back to the JSON file** on POST/PUT/PATCH/DELETE . **CORS and JSONP support** out of the box . **Zero account, dashboard, or cloud step** . **Best for**: quick prototypes, frontend development without backend, CI scripts with no external dependency .



### Additional Strong Open-Source Options



- **[Mocki](https://mocki.io/)** — Configuration-as-code mock API with YAML synced from GitHub (open-core) . **Mock definitions versioned and reviewed like application code** . No-signup editor for quick one-offs . **Best for**: teams wanting Git-native mock definitions .

- **[OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator)** — Generate API clients and server stubs from OpenAPI specs (Apache-2.0) . **The standard for SDK generation** .

- **[Swagger UI](https://github.com/swagger-api/swagger-ui)** — Visual documentation for OpenAPI specs (Apache-2.0) . **"Try it out" functionality for interactive testing** .

- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** — Open-source API request builder with mock server capabilities (MIT) .

- Community **n8n** workflows for mock API deployment and test data generation automation.



**Frameworks for building custom systems**: Combine **Mockoon** for local-first desktop mocking with **WireMock** for automated test suites, **Microcks** for multi-protocol and MCP-enabled mocks, **JSON Server** for instant REST prototypes, and **Prism** for spec-first validation—creating a fully self-hosted, enterprise-grade API mocking platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- API mocking tools handling test data and credentials must follow security best practices and avoid exposing secrets in mock configurations.

- **Open-source API mocking is mature and production-ready.** WireMock is the industry standard for precise request matching in test suites . Mockoon provides the fastest local-first experience with zero account required . Microcks brings multi-protocol mocking with MCP support for AI agents . JSON Server offers instant REST CRUD from a JSON file . **These are genuine alternatives to commercial platforms.**

- **Local vs Cloud matters for team workflow.** Postman Local Mocks simulate APIs directly from your Git-enabled project—**work against mocked responses in the same branch where you're making changes** . Cloud mocks for sharing and collaboration . **Choose based on whether you need individual iteration or team-wide accessibility.**

- **Stateful mocking is the maturity threshold.** Simple mocks return static responses. Production-grade mocks need **state that survives more than one request**—WireMock scenarios, Beeceptor multi-step behavior, Postman state sessions . **This is what separates a prototyping tool from a testing infrastructure.**

- **Chaos injection is the enterprise differentiator.** WireMock Cloud provides **whole-API chaos injection** (random latency/errors across all traffic, no per-stub setup)—a capability no other compared tool documents . MockServer supports chaos profiles with TTL auto-revert . **Testing resilience requires injecting failure, not just simulating success.**

- **MCP integration is the emerging frontier.** Microcks v1.12.0 automatically translates API mocks into **Model Context Protocol aware endpoints**—enabling AI agents to test against mocked APIs . **This is the new interface for agent-driven testing.**

- Self-hosted open-source solutions require proper security hardening, port management, and ongoing maintenance. **Mock servers exposed to the internet should be treated as public endpoints**—never include real credentials or sensitive data in mock responses.



---



**Made for developers, QA engineers, and platform teams building transparent API mocking solutions.**  

Let's make API Mocking more open, data-driven, and contract-first.
