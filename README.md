### 👋 Hi, I’m Alex — a .NET backend engineer who turns complex workflows into maintainable software.

I build APIs, integrations, and self-hosted applications with C# and .NET. I enjoy the parts where software meets reality: legacy systems, authentication, unreliable connections, background jobs, and data that needs to stay correct.

My recent personal work focuses on **passwordless identity, multi-tenant applications, and reusable infrastructure**.

### 🚀 What I’m Building 

#### 🔐 [D3AuthServer](https://github.com/d3sync/D3AuthServer)
A standalone passwordless identity platform for connecting my applications through a shared sign-in system.

- OpenID Connect with OpenIddict, Authorization Code flow, and PKCE.
- Passkeys, magic links, and trusted-device approvals with number matching.
- Per-service access grants, session management, audit trails, and a reusable .NET client library.

#### 🏠 [Family Organizer](https://github.com/d3sync/HouseHoldWebApp)
A household management application connecting shared finances, shopping, receipts, inventory, schedules, and meal planning.

- A multi-tenant modular monolith with explicit module boundaries.
- Household isolation enforced on database reads and writes.
- Background processing through a transactional outbox, with integration tests against PostgreSQL.

#### 🏢 [BuildingManagementApp](https://github.com/d3sync/BuildingManagementApp)
A condominium management application built around how Greek apartment buildings actually operate.

- Monthly expense workflows connecting building managers, accounting offices, and residents.
- Reconciliation, versioned statements, payments, maintenance, and assembly voting.
- .NET 10, Angular, and EF Core with SQLite and PostgreSQL support.

#### 🤖 [AIAgentApp](https://github.com/d3sync/AIAgentApp)
A modular .NET library for embedding AI agents into applications.

- Pluggable skills, MCP tools, memory, and scheduled tasks.
- Email workflows and structured extraction from receipts and documents.
- Application-specific policies and approval controls, with agent runtime data separated from host application data.

#### 🖥️ [DotNetDesk-Server](https://github.com/d3sync/DotNetDesk-Server)
A self-hosted server implementation in C#/.NET targeting compatibility with unmodified RustDesk clients.

- Rendezvous and relay services, plus a web administration console.
- Device management, shared address books, access policies, and audit logs.
- Ongoing work on protocol compatibility, deployment, and end-to-end validation.

### 🏥 Integration Background

My MedTech work includes **ORMService**, a configurable HL7-to-database mapper built over raw TCP sockets, using reflection and JSON mapping definitions.

I’ve also built Windows services and APIs for:

- Uploading laboratory results to national platforms through REST and SOAP.
- Turning complex ERP data into medical referral payloads.
- Ingesting HL7 messages and mapping them into EF Core models.
- Queuing email and SMS notifications with `System.Threading.Channels` and Polly.

### ⚓ At Marpoint

I work on **company-owned maritime connectivity and management systems**, contributing to backend APIs, shared data-access components, authentication, and integrations.

This includes extending existing services, investigating issues across repositories, and maintaining compatibility with legacy components. These are team projects at my current employer.

### 🛠️ Tech Stack

- **Core:** C#, .NET / ASP.NET Core, SQL, Entity Framework Core
- **Web & desktop:** TypeScript, Angular, Blazor, MudBlazor, Avalonia, .NET MAUI
- **Identity:** OpenID Connect, OAuth 2.0, OpenIddict, WebAuthn / passkeys
- **Data:** PostgreSQL, SQL Server, SQLite, MariaDB, LiteDB
- **Integrations:** TCP/IP, HL7, REST, SOAP, MQTT, SignalR, MCP
- **Operations:** Linux, Docker, Nginx, systemd, Azure DevOps, WireGuard
- **Testing:** xUnit, integration tests, Playwright

### 🧠 How I Build

I care about explicit boundaries, useful logs, recoverable failures, and tests that exercise real behavior.

> Build it like someone’s going to depend on it.  
> Secure it like someone’s going to attack it.  
> Simplify it like you’ll be maintaining it at 3 AM.

📫 Want to collaborate? Reach out here on GitHub. Let’s build something useful.
