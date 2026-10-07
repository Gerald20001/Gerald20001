<div align="center">
  <a href="https://github.com/Gerald20001">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,24,30&height=220&section=header&text=IHOR%20slobodian&fontSize=42&fontAlignY=36&desc=QA%20ENGINEER%20%2F%20SDET%20%E2%80%A2%20TEST%20AUTOMATION%20SPECIALIST&descFontSize=16&descAlignY=58&fontColor=ffffff&descColor=00F7FF" width="100%" />
  </a>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/TEST_STATUS-PASSED_(100%25)-00C853?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Status Passed" />
  <img src="https://img.shields.io/badge/FLAKINESS-0.00%25-00C853?style=for-the-badge" alt="0% Flakiness" />
  <img src="https://img.shields.io/badge/FOUNDATION-EX--FULLSTACK_DEV-00B0FF?style=for-the-badge&logo=codereview&logoColor=white" alt="Dev Foundation" />
  <img src="https://img.shields.io/badge/FOCUS-AUTOMATION%20%26%20CI%2FCD-7928CA?style=for-the-badge" alt="Focus CI/CD" />
  <img src="https://img.shields.io/badge/LOCATION-UKRAINE_🇺🇦-FFD600?style=for-the-badge" alt="Location" />
</p>

```typescript
// test/suites/candidate_profile.spec.ts
import { test, expect } from '@playwright/test';

test.describe('Candidate Profile: Ihor Slobodian (Gerald20001)', () => {
  test('verifies software engineering roots & QA mindset', async ({ candidate }) => {
    expect(candidate.role).toBe('QA Engineer / SDET');
    expect(candidate.mindset).toBe('Shift-Left: Break it in development, never in production');
    expect(candidate.background).toContain(['Full-Stack Development', 'TypeScript', 'Node.js', 'Databases']);
  });

  test('executes automated quality gates', async ({ pipeline }) => {
    const report = await pipeline.runAutomationMatrix({
      suites: ['E2E Cross-Browser', 'API Contract & Schema', 'Performance & Load', 'Regression'],
      targetCoverage: 100,
    });

    expect(report.status).toBe('ALL CHECKS PASSED');
    expect(report.flakinessRate).toBe(0.0);
    expect(report.productionConfidence).toBe('MAXIMUM');
  });
});
```

---

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎯 The QA Engineering Philosophy</h3>
      <ul>
        <li><b>Developer DNA:</b> Having built full-stack applications, I never treat software as a black box. I read stack traces, inspect network requests, debug React/DOM states, and identify root causes directly in the source code.</li>
        <li><b>Shift-Left Strategy:</b> Quality begins at the architecture phase. I analyze requirements, define boundary conditions, and build automated verification into the development cycle before deployment.</li>
        <li><b>Zero-Flake E2E Philosophy:</b> Robust Page Object Models (POM), explicit state synchronizations, isolated test fixtures, and network mocking over brittle arbitrary timeouts.</li>
        <li><b>Rigorous Test Design:</b> Systematic coverage through Boundary Value Analysis (BVA), Equivalence Partitioning, State Transition testing, and deep exploratory testing.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Technical Arsenal & Tooling</h3>
      <b>🧪 Test Automation & Quality Assurance</b><br/>
      <p align="left">
        <img src="https://skillicons.dev/icons?i=postman,cypress,selenium,vitest,jest" />
      </p>
      <p align="left">
        <img src="https://img.shields.io/badge/Playwright-45BA4B?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
        <img src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" alt="k6" />
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black" alt="Swagger" />
        <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira" />
      </p>
      <b>💻 Core Languages & Scripting (Dev Superpower)</b><br/>
      <p align="left">
        <img src="https://skillicons.dev/icons?i=ts,js,py,nodejs,bash,regex" />
      </p>
      <b>🗄️ Databases & CI/CD Pipelines</b><br/>
      <p align="left">
        <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,githubactions,docker,linux" />
      </p>
    </td>
  </tr>
</table>

---

### 🔄 Quality Assurance Lifecycle

```
┌──────────────────┐     ┌──────────────────┐     ┌──────────────────┐     ┌──────────────────┐
│ 01. PLAN & SPEC  │ ──> │ 02. TEST DESIGN  │ ──> │ 03. AUTOMATION   │ ──> │ 04. CI/CD GATES  │
├──────────────────┤     ├──────────────────┤     ├──────────────────┤     ├──────────────────┤
│ Requirements     │     │ BVA / Partitions │     │ Playwright (E2E) │     │ GitHub Actions   │
│ Edge Cases       │     │ Test Matrices    │     │ Postman (API)    │     │ Parallel Runs    │
│ Acceptance Rules │     │ Risk Priority    │     │ k6 (Performance) │     │ Zero Flake Deploy│
└──────────────────┘     └──────────────────┘     └──────────────────┘     └──────────────────┘
```

---

### 🔬 Featured Projects & Engineering Highlights

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🎭 Playwright E2E Automation Framework</h4>
      <p>Modular end-to-end test framework built in <b>TypeScript</b> following Page Object Model (POM) best practices.</p>
      <p>
        <code>TypeScript</code> • <code>Playwright</code> • <code>GitHub Actions</code><br/>
        ✔ Multi-browser parallel execution across Chromium, Firefox, WebKit<br/>
        ✔ Auto-wait mechanics, network route mocking, and trace recordings<br/>
        ✔ Automated test reporting integrated directly into pull request checks
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📡 Automated API Regression & Contract Suite</h4>
      <p>Data-driven RESTful API validation suite testing authentication contracts, payload mutations, and edge cases.</p>
      <p>
        <code>Postman</code> • <code>Newman</code> • <code>JSON Schema</code><br/>
        ✔ Dynamic token extraction & environment variable session chaining<br/>
        ✔ Strict JSON schema assertions on every endpoint<br/>
        ✔ Automated CI execution via Newman CLI with comprehensive HTML reports
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🛡️ Resilient Network Scraper & Sentinel</h4>
      <p>Autonomous monitoring service engineered with Puppeteer Stealth to monitor dynamic marketplaces with high fault tolerance.</p>
      <p>
        <code>Node.js</code> • <code>Puppeteer Stealth</code> • <code>Telegram Bot API</code><br/>
        ✔ Cloudflare anti-bot handling with automated session persistence<br/>
        ✔ Exponential backoff, jitter algorithms, and memory-safe caching<br/>
        ✔ Real-time status alerts and background execution monitoring
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🧪 Full-Stack Testbed Applications</h4>
      <p>Realistic full-stack applications built to reproduce concurrency collisions, edge cases, and state bugs.</p>
      <p>
        <code>React</code> • <code>Express</code> • <code>MongoDB</code> • <code>PostgreSQL</code><br/>
        ✔ Architected to stress-test UI race conditions and async states<br/>
        ✔ Implements JWT authorization, RBAC, and real-time events<br/>
        ✔ Serves as a playground for continuous testing experimentation
      </p>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Telemetry

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gerald20001&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Gerald20001&theme=tokyonight&hide_border=true" height="155" alt="GitHub Streak" />
</div>
<br/>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Gerald20001&theme=tokyo-night&area=true&hide_border=true" width="94%" alt="Activity Graph" />
</div>

---

<div align="center">

### 🤝 Connect & Collaborate

```bash
$ curl -X POST https://api.slobodian.io/v1/collaborate \
  -H "Content-Type: application/json" \
  -d '{"status": "Ready for high-impact QA / SDET challenges"}'
```

<p align="center">
  <a href="mailto:igorslobodan05@gmail.com"><img src="https://img.shields.io/badge/Gmail-igorslobodan05%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://t.me/crytracer"><img src="https://img.shields.io/badge/Telegram-@crytracer-229ED9?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <img src="https://img.shields.io/badge/Discord-Griffith__2001-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  <a href="https://github.com/Gerald20001"><img src="https://img.shields.io/badge/GitHub-Gerald20001-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,24,30&height=120&section=footer" width="100%" />

</div>
