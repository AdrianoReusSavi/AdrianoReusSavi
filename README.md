<h1 align="center">Adriano Reus Savi</h1>

<p align="center">
  <strong>Software Engineer &middot; .NET backend focus</strong>
</p>

<p align="center">
  Working with .NET since 2022. On my own projects I go deep into backend:<br>
  authentication, resilient integrations and real-time apps, always with integration tests and CI.
</p>

<p align="center">
  <a href="https://www.adrianoreussavi.com.br"><img src="https://img.shields.io/badge/Portfolio-adrianoreussavi.com.br-0A0A0A?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/adrianoreussavi"><img src="https://img.shields.io/badge/LinkedIn-adrianoreussavi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

## Tech Stack

<table>
  <tr>
    <td valign="top"><strong>Backend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white" />
      <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/.NET%20Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/EF%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Frontend</strong></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Runtime &amp; Infra</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Testing</strong></td>
    <td>
      <img src="https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white" />
      <img src="https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white" />
    </td>
  </tr>
</table>

---

## Featured Projects

Each one has a page explaining the problem, how it works and the decisions behind it.

### [dotnet-jwt-refresh](https://github.com/AdrianoReusSavi/dotnet-jwt-refresh)
JWT authentication with refresh token rotation and reuse detection: a reused token revokes the whole session family. Handles concurrent refreshes with optimistic concurrency, RFC 9457 errors and rate limiting; 233 tests, integration against a real PostgreSQL.

`.NET 10` &middot; `ASP.NET Core` &middot; `EF Core` &middot; `PostgreSQL` &middot; `Testcontainers` &middot; `GitHub Actions`

&rarr; [How it works](https://www.adrianoreussavi.com.br/projetos/jwt-refresh)

### [dotnet-ptax](https://github.com/AdrianoReusSavi/dotnet-ptax)
Exchange-rate service built on Banco Central do Brasil's PTAX rates. A background worker syncs rates idempotently and raises variation alerts; the API serves them behind a Redis cache with circuit breaker fallback. One `docker compose up`.

`.NET 10` &middot; `Worker Service` &middot; `PostgreSQL` &middot; `Redis` &middot; `Testcontainers` &middot; `Docker Compose`

&rarr; [How it works](https://www.adrianoreussavi.com.br/projetos/ptax)

### [Planning Poker](https://github.com/AdrianoReusSavi/planningpoker)
Real-time agile estimation with rooms shared by link. Room state synchronized over SignalR, reconnection with a 5-minute grace period.

`.NET 9` &middot; `SignalR` &middot; `React 19` &middot; `TypeScript` &middot; `Docker`

&rarr; [How it works](https://www.adrianoreussavi.com.br/projetos/planning-poker) &middot; [Live demo](https://planningpoker-kappa.vercel.app)

## Other Projects

- **[ArsDrop](https://github.com/AdrianoReusSavi/arsdrop)**: peer-to-peer file transfer over WebRTC, with no files stored on the server. [Live](https://www.arsdrop.com.br)
- **[Realms Map](https://github.com/AdrianoReusSavi/realms-map)**: interactive map of a Minecraft Realms world, rebuilt and published by GitHub Actions every 12 hours. [Live](https://adrianoreussavi.github.io/realms-map)
