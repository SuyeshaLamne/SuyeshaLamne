<!--
  Website-style README for Suyesha Lamne
  Note: The hover effects below work in Markdown renderers that allow custom CSS.
  GitHub README pages may strip custom <style> blocks, so the layout will still render,
  but advanced hover animations may not appear on GitHub.
-->

<style>
  :root {
    --bg-dark: #0f172a;
    --card-dark: #111827;
    --card-light: #ffffff;
    --text-main: #e5e7eb;
    --text-muted: #94a3b8;
    --accent: #7c3aed;
    --accent-2: #06b6d4;
    --border: rgba(148, 163, 184, 0.25);
  }

  .portfolio-wrapper {
    font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    max-width: 1100px;
    margin: auto;
    color: var(--text-main);
  }

  .hero {
    padding: 42px 28px;
    border-radius: 28px;
    background:
      radial-gradient(circle at top left, rgba(124, 58, 237, 0.35), transparent 35%),
      radial-gradient(circle at bottom right, rgba(6, 182, 212, 0.25), transparent 35%),
      linear-gradient(135deg, #020617 0%, #111827 55%, #0f172a 100%);
    border: 1px solid var(--border);
    text-align: center;
    box-shadow: 0 18px 45px rgba(15, 23, 42, 0.35);
  }

  .hero h1 {
    font-size: 44px;
    line-height: 1.1;
    margin: 0;
  }

  .hero h2 {
    font-size: 18px;
    font-weight: 500;
    color: #cbd5e1;
    margin-top: 10px;
  }

  .hero p {
    max-width: 760px;
    margin: 18px auto 0;
    color: #dbeafe;
    font-size: 16px;
  }

  .nav-pills {
    margin-top: 26px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
  }

  .nav-pills a,
  .btn-link {
    display: inline-block;
    padding: 10px 16px;
    border-radius: 999px;
    background: rgba(255, 255, 255, 0.08);
    color: #ffffff;
    text-decoration: none;
    border: 1px solid rgba(255, 255, 255, 0.12);
    transition: all 0.25s ease;
  }

  .nav-pills a:hover,
  .btn-link:hover {
    background: linear-gradient(135deg, var(--accent), var(--accent-2));
    transform: translateY(-3px);
    box-shadow: 0 12px 28px rgba(6, 182, 212, 0.28);
  }

  .section-title {
    margin-top: 44px;
    margin-bottom: 16px;
    font-size: 28px;
    color: #111827;
  }

  .section-subtitle {
    color: #64748b;
    margin-top: -8px;
    margin-bottom: 18px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 18px;
  }

  .grid-3 {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 16px;
  }

  .card {
    background: #ffffff;
    color: #0f172a;
    border: 1px solid #e5e7eb;
    border-radius: 22px;
    padding: 22px;
    box-shadow: 0 8px 24px rgba(15, 23, 42, 0.08);
    transition: all 0.25s ease;
  }

  .card:hover {
    transform: translateY(-6px);
    border-color: var(--accent);
    box-shadow: 0 18px 40px rgba(124, 58, 237, 0.18);
    background: linear-gradient(180deg, #ffffff 0%, #f8f7ff 100%);
  }

  .card h3 {
    margin-top: 0;
    margin-bottom: 10px;
    font-size: 20px;
  }

  .card p {
    color: #475569;
  }

  .tag-row {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 14px 0;
  }

  .tag {
    display: inline-block;
    padding: 6px 10px;
    border-radius: 999px;
    background: #eef2ff;
    color: #3730a3;
    font-size: 13px;
    font-weight: 600;
    transition: all 0.2s ease;
  }

  .tag:hover {
    background: #7c3aed;
    color: #ffffff;
    transform: scale(1.05);
  }

  .metric-card {
    text-align: center;
    background: #ffffff;
    color: #0f172a;
    border-radius: 20px;
    border: 1px solid #e5e7eb;
    padding: 18px;
    transition: all 0.25s ease;
  }

  .metric-card:hover {
    background: #ecfeff;
    border-color: #06b6d4;
    transform: translateY(-5px);
  }

  .metric-card strong {
    display: block;
    font-size: 24px;
    color: #7c3aed;
  }

  details {
    background: #ffffff;
    color: #0f172a;
    border: 1px solid #e5e7eb;
    border-radius: 18px;
    padding: 16px 18px;
    margin-bottom: 14px;
    transition: all 0.25s ease;
  }

  details:hover {
    border-color: #06b6d4;
    box-shadow: 0 14px 30px rgba(6, 182, 212, 0.14);
  }

  summary {
    cursor: pointer;
    font-size: 18px;
  }

  .footer-card {
    margin-top: 42px;
    padding: 28px;
    border-radius: 24px;
    text-align: center;
    background: linear-gradient(135deg, #111827, #312e81);
    color: #ffffff;
  }

  .footer-card a {
    color: #a5f3fc;
    font-weight: 700;
  }

  @media (max-width: 760px) {
    .grid,
    .grid-3 {
      grid-template-columns: 1fr;
    }

    .hero h1 {
      font-size: 34px;
    }
  }
</style>

<div class="portfolio-wrapper">

<section class="hero">

# 👩‍💻 Suyesha Lamne

## AI Engineer • BI Engineer • Data Engineer • Data Analyst

Building AI agents, analytics automation, BI dashboards, and scalable data solutions that turn business problems into reliable, data-driven products.

<div class="nav-pills">
  <a href="https://www.linkedin.com/in/suyesha-lamne/">LinkedIn</a>
  <a href="mailto:suyeshalamne@gmail.com">Email</a>
  <a href="#featured-projects">Projects</a>
  <a href="#dashboard-projects">Dashboards</a>
  <a href="#technical-skills">Skills</a>
  <a href="#education">Education</a>
</div>

</section>

<h2 class="section-title">🚀 Portfolio Snapshot</h2>

<div class="grid-3">
  <div class="metric-card">
    <strong>3+ yrs</strong>
    Data & AI Experience
  </div>
  <div class="metric-card">
    <strong>AI + BI</strong>
    Automation Focus
  </div>
  <div class="metric-card">
    <strong>Cloud Data</strong>
    Pipelines & Dashboards
  </div>
</div>

<div class="card" style="margin-top: 18px;">
  <h3>About Me</h3>
  <p>
    I’m a data and AI professional with experience building <b>AI-powered workflows, business intelligence dashboards, data pipelines, and automation solutions</b>.
    Currently, I work at <b>Crayola as an AI Engineer</b>, where I develop AI agents, automate analytics workflows, and support Power BI reporting initiatives that improve productivity and decision-making.
  </p>
</div>

<a id="featured-projects"></a>

<h2 class="section-title">🔥 Featured AI & Data Projects</h2>
<p class="section-subtitle">Hover over each card to highlight the project.</p>

<div class="grid">

  <div class="card">
    <h3>🤖 AI Agents & BI Automation at Crayola</h3>
    <p>Developed AI-powered tools and agent workflows to automate business tasks, improve reporting efficiency, and support BI operations.</p>
    <div class="tag-row">
      <span class="tag">Python</span>
      <span class="tag">Power BI</span>
      <span class="tag">SQL</span>
      <span class="tag">OpenAI API</span>
      <span class="tag">Azure Foundry</span>
      <span class="tag">Prompt Engineering</span>
    </div>
    <ul>
      <li>Built AI agents for internal workflow automation</li>
      <li>Created prompt-based AI solutions for business use cases</li>
      <li>Supported Power BI dashboards and KPI reporting</li>
      <li>Automated manual reporting steps using Python</li>
    </ul>
    <p><b>Status:</b> Professional project — details available upon request</p>
  </div>

  <div class="card">
    <h3>🧠 AI-Powered Resume Screener</h3>
    <p>Designed a semantic search application that matches resumes with job descriptions using embeddings and vector search.</p>
    <div class="tag-row">
      <span class="tag">OpenAI API</span>
      <span class="tag">Pinecone</span>
      <span class="tag">Streamlit</span>
      <span class="tag">Embeddings</span>
    </div>
    <ul>
      <li>Used OpenAI embeddings for resume-job matching</li>
      <li>Stored vector data in Pinecone</li>
      <li>Built an interactive Streamlit demo</li>
      <li>Improved matching using semantic similarity</li>
    </ul>
    <a class="btn-link" href="https://youtu.be/dMODRvqjwKE?si=Duv1dWvc19TFifhj">🎥 Watch Demo</a>
  </div>

  <div class="card">
    <h3>⚙️ Transaction Pulse: Real-Time ELT Pipeline</h3>
    <p>Built a real-time ELT pipeline for financial transaction processing, automated scheduling, and analytics-ready reporting.</p>
    <div class="tag-row">
      <span class="tag">Apache Airflow</span>
      <span class="tag">PySpark</span>
      <span class="tag">DBT</span>
      <span class="tag">Snowflake</span>
      <span class="tag">Looker</span>
    </div>
    <ul>
      <li>Orchestrated workflows using Airflow</li>
      <li>Processed high-volume data with PySpark</li>
      <li>Modeled warehouse data using DBT</li>
      <li>Created Looker dashboards for monitoring</li>
    </ul>
    <p><b>Status:</b> Private repo — link available upon request</p>
  </div>

  <div class="card">
    <h3>📈 Stock Optimate</h3>
    <p>Created an interactive financial analytics web app for exploring stock metrics, financial KPIs, trends, and forecasts.</p>
    <div class="tag-row">
      <span class="tag">SQL Server</span>
      <span class="tag">React</span>
      <span class="tag">Power BI</span>
      <span class="tag">Forecasting</span>
    </div>
    <ul>
      <li>Designed SQL Server data structure</li>
      <li>Built React-based user interface</li>
      <li>Created Power BI financial dashboards</li>
      <li>Enabled metric and forecast exploration</li>
    </ul>
    <p><b>Status:</b> Link available upon request or in GitHub repo</p>
  </div>

</div>

<a id="dashboard-projects"></a>

<h2 class="section-title">📊 Dashboard Projects</h2>

<details open>
<summary><b>💸 Bank Loan Performance Analytics</b></summary>

<br>

**Tools:** SQL, Tableau

Built an interactive dashboard to analyze borrower risk, credit grades, payment behavior, and delinquency trends.

**Highlights**
- Analyzed loan performance across customer segments
- Tracked borrower risk and repayment patterns
- Visualized funded amount, interest rate, DTI, and loan status
- Identified patterns across good loans and risky loans

<a class="btn-link" href="https://public.tableau.com/views/BankLoanReport_17431111023620/Summary?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">🔗 View Dashboard</a>

</details>

<details>
<summary><b>👥 HR Analytics Dashboard</b></summary>

<br>

**Tools:** Tableau, Alteryx

Developed an HR dashboard to visualize employee turnover, hiring trends, workforce demographics, and planning insights.

**Highlights**
- Visualized employee attrition and workforce trends
- Prepared and transformed data using Alteryx
- Built Tableau dashboard for HR decision-making
- Supported workforce planning through KPI tracking

<a class="btn-link" href="https://public.tableau.com/views/HRAnalyticsDashboard_17330798584100/HRAnalyticsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">🔗 View Dashboard</a>

</details>

<a id="experience"></a>

<h2 class="section-title">💼 Current Experience</h2>

<div class="card">
  <h3>🖍️ Crayola — AI Engineer</h3>
  <p><b>Dec 2025 – Present | Remote</b></p>
  <p>
    Working on <b>AI agents, BI automation, Power BI reporting, and analytics workflows</b> to reduce manual effort and improve business decision-making.
  </p>
  <div class="tag-row">
    <span class="tag">AI Agents</span>
    <span class="tag">Power BI</span>
    <span class="tag">Python Automation</span>
    <span class="tag">SQL</span>
    <span class="tag">Prompt Engineering</span>
    <span class="tag">BI Reporting</span>
    <span class="tag">Workflow Automation</span>
    <span class="tag">Azure Foundry</span>
  </div>
</div>

<a id="technical-skills"></a>

<h2 class="section-title">🧰 Technical Skills</h2>
<p class="section-subtitle">Each skill badge highlights on hover.</p>

<div class="grid">

  <div class="card">
    <h3>🤖 AI & Automation</h3>
    <div class="tag-row">
      <span class="tag">AI Agents</span>
      <span class="tag">OpenAI API</span>
      <span class="tag">Prompt Engineering</span>
      <span class="tag">LLMs</span>
      <span class="tag">Semantic Search</span>
      <span class="tag">Workflow Automation</span>
      <span class="tag">Azure Foundry</span>
    </div>
  </div>

  <div class="card">
    <h3>📊 Business Intelligence</h3>
    <div class="tag-row">
      <span class="tag">Power BI</span>
      <span class="tag">Tableau</span>
      <span class="tag">Looker</span>
      <span class="tag">Excel</span>
      <span class="tag">DAX</span>
      <span class="tag">KPI Reporting</span>
    </div>
  </div>

  <div class="card">
    <h3>⚙️ Data Engineering</h3>
    <div class="tag-row">
      <span class="tag">Python</span>
      <span class="tag">SQL</span>
      <span class="tag">PySpark</span>
      <span class="tag">Airflow</span>
      <span class="tag">DBT</span>
      <span class="tag">SSIS</span>
      <span class="tag">Alteryx</span>
    </div>
  </div>

  <div class="card">
    <h3>🗄️ Databases & Warehousing</h3>
    <div class="tag-row">
      <span class="tag">Snowflake</span>
      <span class="tag">BigQuery</span>
      <span class="tag">SQL Server</span>
      <span class="tag">Oracle</span>
    </div>
  </div>

  <div class="card">
    <h3>☁️ Cloud & Tools</h3>
    <div class="tag-row">
      <span class="tag">AWS S3</span>
      <span class="tag">Redshift</span>
      <span class="tag">AWS Lambda</span>
      <span class="tag">Azure Synapse</span>
      <span class="tag">GCP</span>
      <span class="tag">Git</span>
      <span class="tag">JIRA</span>
      <span class="tag">Streamlit</span>
    </div>
  </div>

  <div class="card">
    <h3>🧩 Portfolio Strengths</h3>
    <div class="tag-row">
      <span class="tag">Analytics Automation</span>
      <span class="tag">Dashboard Design</span>
      <span class="tag">Data Pipelines</span>
      <span class="tag">Stakeholder Collaboration</span>
      <span class="tag">AI Prototyping</span>
    </div>
  </div>

</div>

<a id="education"></a>

<h2 class="section-title">🎓 Academic Background</h2>

<div class="card">
  <h3>Master of Science in Information Systems</h3>
  <p><b>Northeastern University</b></p>
  <div class="tag-row">
    <span class="tag">2023–2025</span>
    <span class="tag">Boston, MA</span>
    <span class="tag">Completed</span>
  </div>
  <p>
    Completed a graduate program focused on information systems, analytics, data management, and technology-driven business solutions.
  </p>
</div>

<h2 class="section-title">🧭 Portfolio Map</h2>

```mermaid
graph TD
    A[Data & AI Portfolio] --> B[AI Agents]
    A --> C[BI Dashboards]
    A --> D[Data Engineering]
    A --> E[Automation]
    A --> F[Analytics Applications]

    B --> B1[OpenAI API]
    B --> B2[Prompt Engineering]
    B --> B3[Azure Foundry]

    C --> C1[Power BI]
    C --> C2[Tableau]
    C --> C3[KPI Reporting]

    D --> D1[Airflow]
    D --> D2[DBT]
    D --> D3[Snowflake]

    E --> E1[Python Automation]
    E --> E2[Workflow Optimization]

    F --> F1[Streamlit]
    F --> F2[React]
```

<div class="footer-card">
  <h2>Let’s Build Data Products That Make Work Smarter</h2>
  <p>Open to AI, BI, analytics engineering, data engineering, and automation-focused opportunities.</p>
  <p>
    <a href="mailto:suyeshalamne@gmail.com">Contact Me</a> ·
    <a href="https://www.linkedin.com/in/suyesha-lamne/">LinkedIn</a>
  </p>
</div>

</div>
