<h1 align="center">Hi, I'm Vahid 👋</h1>

<p align="center">
  <b>Senior Software Engineer @ Microsoft · SQL Server Drivers</b><br/>
  I build the plumbing between your app and SQL Server — and teach AI agents to help build it.
</p>

<p align="center">
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white"/>
  <img alt="SQL Server" src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
  <img alt="GitHub Copilot" src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white"/>
</p>

---

### 🛢️ What I work on

| Project | What I do |
|---|---|
| **Microsoft OLE DB Driver for SQL Server** | Ship the 18.x / 19.x releases: TLS 1.3, Arm64 / Arm64X builds, connection resiliency, new UI languages, and build and release modernization |
| **Microsoft ODBC Driver for SQL Server** | Connection resiliency, new connection options, localization, release pipelines |
| **[mssql-rs](https://github.com/microsoft/mssql-rs)** | The Rust TDS stack and new ODBC driver: Entra ID auth (service principal, managed identity, interactive, integrated / Kerberos), server cursors, descriptors, catalog functions, query timeouts, bulk copy |
| **Entra ID auth for the drivers** | The shared authentication library behind the Windows drivers: releases, test coverage, CI |
| **[SQL docs](https://github.com/MicrosoftDocs/sql-docs)** | Driver documentation |

### 🔬 How I work

- **Parity-driven engineering.** When I port behavior, I measure the reference driver first and cite it in the PR. If the new code differs, the difference is written down.
- **Security first.** Memory-safety hardening of TDS protocol parsing, static analysis (CodeQL, PREfast, BinSkim), and regression harnesses built on in-process mock TDS servers.
- **AI-native development.** `AGENTS.md`, Copilot instructions, and agent skills for code review, validation, and CI triage, so people and agents can ship together safely.
- **Release engineering.** Multi-stage YAML pipelines, signing, symbols, NuGet, and builds you can reproduce.

### 🚀 Recent highlights

- [Add ActiveDirectoryIntegrated authentication to mssql-odbc](https://github.com/microsoft/mssql-rs/pull/665): Windows, plus Kerberos → WS-Trust on Linux and macOS
- [Integrate descriptor records with binding and implementation metadata](https://github.com/microsoft/mssql-rs/pull/436)
- [Implement ODBC catalog functions](https://github.com/microsoft/mssql-rs/pull/325)
- [Enforce `SQL_ATTR_QUERY_TIMEOUT` so a blocked statement can't wait forever](https://github.com/microsoft/mssql-rs/pull/442)
- [Add positioned cursor operations](https://github.com/microsoft/mssql-rs/pull/67)

### 🔭 Right now

- 🦀 Bringing the Rust ODBC driver to parity with the classic C++ driver
- 🤖 Making large legacy C++ codebases ready for AI agents
- 📈 Exploring observability for database drivers
- 🤝 Open to OSS collaboration on Rust and data connectivity

<sub>⚡ Fun fact: I can read a TDS packet hex dump faster than a stack trace.</sub>
