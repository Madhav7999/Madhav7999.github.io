# Madhav Meesala — Portfolio

Personal portfolio site for **Madhav Meesala**, Software Engineer.

**Live at [madhavmeesala.com](https://madhavmeesala.com)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-madhav--m-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhav-m-b38013213/)
[![Email](https://img.shields.io/badge/Email-madhavmeesala%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:madhavmeesala@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Madhav7999-181717?style=flat&logo=github&logoColor=white)](https://github.com/Madhav7999)

## About

Software Engineer with 4+ years building scalable full-stack and distributed systems across
financial services and digital payments — Java, Spring Boot, Kafka, AWS and Kubernetes — with
recent work in GenAI, RAG, agentic AI and MLOps.

## Featured projects

| Project | What it does |
|---|---|
| [real-time-fraud-detection](https://github.com/Madhav7999/real-time-fraud-detection) | Kafka → Spark Streaming fraud scoring, served on a Spring Boot dashboard |
| [pointintime](https://github.com/Madhav7999/pointintime) | Feature store that refuses to serve a future-leaking feature |
| [driftguard](https://github.com/Madhav7999/driftguard) | MLflow, FastAPI and drift-triggered retraining |
| [goodreads_etl_pipeline](https://github.com/Madhav7999/goodreads_etl_pipeline) | Spark and Airflow ETL into a Redshift warehouse on AWS |
| [modelcard](https://github.com/Madhav7999/modelcard) | Deterministic model cards generated from the trained estimator |

The full set, with write-ups, is on the [site](https://madhavmeesala.com/#projects).

## How the site is built

JSON-driven static site: all content lives in `data/*.json` and is rendered client-side by
`assets/js/main.js`. No build step, no framework — vanilla HTML, CSS and JavaScript, deployed
from this repository with GitHub Pages.

```
data/            content — hero, about, experience, skills, projects, education, contact
assets/css/      styles
assets/js/       renderers for each section
assets/images/   portrait, company logos, project cards
index.html       shell that the JSON is rendered into
CNAME            custom domain
```

To run it locally:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Contact

- **LinkedIn** — [linkedin.com/in/madhav-m-b38013213](https://www.linkedin.com/in/madhav-m-b38013213/)
- **Email** — [madhavmeesala@gmail.com](mailto:madhavmeesala@gmail.com)
- **Location** — Wisconsin, USA
