<!-- Replace every <PLACEHOLDER> before publishing. Repo name must equal your GitHub username (papwrpk). -->

<h1 align="center">Worapakorn Pongudom</h1>

<p align="center">
  <b>Aspiring Data Engineer</b> · Bangkok, Thailand<br/>
  Reliable data pipelines · ETL/ELT workflows · Analytics-ready datasets
</p>

<p align="center">
  <a href="mailto:papwrpk@gmail.com"><img src="https://img.shields.io/badge/Email-papwrpk%40gmail.com-0f2027?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="<LINKEDIN_URL>"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Data%20Engineer%20roles-2c5364?style=flat-square" alt="Open to work"/>
</p>

---

## About

I build data pipelines that are reliable, tested, and easy to maintain. My background is in **Applied Statistics and Data Analysis** (B.Sc., KMITL), so I pay close attention to data quality and modeling.

---

## Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,postgres,snowflake,airflow,dbt,docker,git,github&theme=dark" alt="tech stack"/>
</p>

| Area | Tools |
|------|-------|
| Languages | Python, SQL |
| Orchestration | Apache Airflow |
| Transformation | dbt |
| Warehouse | Snowflake, `<other: PostgreSQL / BigQuery ...>` |
| Infra | Docker, Git |
| Analytics | Statistics, Data Modeling, `<BI tool>` |

---

## Featured Projects

### [Cloud-Native ELT Pipeline with dbt & Airflow](https://github.com/papwrpk/Snowflake-ELT-Pipeline-with-dbt-and-Airflow)

ELT pipeline that loads data into **Snowflake**, transforms it with **dbt**, and is orchestrated by **Airflow** running in **Docker**.

```mermaid
flowchart LR
    A[("Source<br/>&lt;data source&gt;")] --> B[("Snowflake<br/>raw")]
    B --> C["dbt<br/>staging → marts"]
    C --> D[("Snowflake<br/>analytics")]
    E{{"Airflow<br/>orchestration"}} -.-> B
    E -.-> C
```

- **Stack:** Python, Airflow, dbt, Snowflake, Docker
- **What I did:** `<e.g. customized models, added dbt tests, set up scheduling>`
- **Highlights:** `<e.g. incremental models, data quality tests, scheduled DAGs>`

### [`<Project 2>`](<REPO_URL>)

`<One or two sentences: problem, approach, outcome.>`

- **Stack:** `<tools>`

---

## Education

**B.Sc. in Applied Statistics and Data Analysis**, Faculty of Science
King Mongkut's Institute of Technology Ladkrabang (KMITL)
