<div align="center">

  <!-- Animated Typing Banner -->
  <a href="https://github.com/yogeshrajput7906">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Hi%2C%20I%27m%20Yogesh%20Rajput;Data%20Engineer%20%26%20ML%20Engineer;Building%20Scalable%20Lakehouses%20%26%20Robust%20ML%20Pipelines;Designing%20Systems%20That%20Hold%20Up%20in%20Production" alt="Typing SVG Banner" />
  </a>

  <p align="center">
    <strong>Data Engineering &bull; Machine Learning &bull; Software Engineering</strong>
  </p>

  <!-- Social & Profile Badges -->
  <p align="center">
    <a href="https://www.linkedin.com/in/yogesh-rajput" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/yogeshrajput7906" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="mailto:yogeshrajput7080@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/Focus-Data%20%2B%20ML%20%2B%20Software-8B5CF6?style=flat-square" alt="Focus" />
    <img src="https://img.shields.io/badge/Stack-Databricks%20%C2%B7%20PySpark%20%C2%B7%20Python%20%C2%B7%20TensorFlow-0284C7?style=flat-square" alt="Stack" />
    <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-22C55E?style=flat-square" alt="Status" />
  </p>

</div>

---

### Executive Summary & Engineering Focus

> *Data & ML Engineer focused on building robust, idempotent data pipelines and leak-free machine learning systems — designing the architecture first, verifying with automated tests, and ensuring reliability in production.*

I work at the intersection of **Software Engineering**, **Data Engineering**, and **Machine Learning**. I believe that successful AI and analytics systems depend on solid software fundamentals: typed boundaries, automated test coverage, reproducible environments, and disciplined data modeling.

I focus on the engineering practices that matter beyond isolated notebooks: **idempotent pipelines, medallion lakehouse architecture, zero-leakage time-series preprocessing, honest baseline benchmarking, and automated CI/CD quality gates**.

<p align="center">
  <img src="https://img.shields.io/badge/DATA%20ENGINEERING-8B5CF6?style=for-the-badge" alt="Data Engineering" />
  <img src="https://img.shields.io/badge/MACHINE%20LEARNING-F59E0B?style=for-the-badge" alt="Machine Learning" />
  <img src="https://img.shields.io/badge/SOFTWARE%20ENGINEERING-0EA5E9?style=for-the-badge" alt="Software Engineering" />
</p>

- **Data Engineering & Lakehouse:** Medallion lakehouse design (Bronze → Silver → Gold), Delta Lake, PySpark ETL/ELT pipelines, Databricks Asset Bundles (DABs), dimensional star schema modeling, SCD Type 2 tracking, and partitioned incremental ingestion.
- **Machine Learning & Time Series:** Recurrent neural networks (LSTM), sequence preparation, zero-leakage chronological preprocessing, feature engineering (technical momentum indicators, moving averages, RSI), and transparent persistence baseline benchmarking.
- **Software Engineering & Quality:** Python (3.10+), modular architecture, type annotations, pytest suites, strict Ruff linting, Git workflow, and GitHub Actions CI pipelines.
- **Reliability & Experimentation:** Reproducible random seeding, EarlyStopping regularization, evaluation metrics (MAE, RMSE, MAPE, Directional Accuracy), headless figure generation, and clean separation between training and inference.

---

### Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">Stock Price Trend Prediction with LSTM</h3>
      <p><strong>Leak-Free Time-Series Forecasting Pipeline &amp; Baseline Benchmark</strong></p>
      <p>Modular ML engineering pipeline forecasting Apple Inc. (<code>AAPL</code>) price trends using stacked LSTMs. Engineered 20-day/50-day moving averages and 14-day RSI. Enforces <strong>strict zero-leakage chronological splitting</strong>, fitting scalers strictly on training data. Honestly benchmarks against a naive persistence baseline (&hat;y<sub>t</sub> = y<sub>t-1</sub>) and delivers 52.75% directional accuracy. Backed by <strong>19 automated unit tests and GitHub Actions CI</strong>.</p>
      <p>
        <a href="https://github.com/yogeshrajput7906/Stock-Price-Trend-Prediction-with-LSTM" target="_blank"><img src="https://img.shields.io/badge/Repository-Stock--Price--LSTM-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/19%20tests%20%C2%B7%20Ruff%20Clean-22C55E?style=flat-square" alt="Tests" />
        <img src="https://img.shields.io/badge/CI-Passing-brightgreen?style=flat-square" alt="CI" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
        <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" />
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
        <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
        <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">Food Delivery AI Data Platform</h3>
      <p><strong>Medallion Lakehouse Architecture &amp; Analytics Layer</strong></p>
      <p>End-to-end batch lakehouse platform: raw data ingestion into a cloud lakehouse following the <strong>Medallion pattern (Bronze &rarr; Silver &rarr; Gold)</strong>. Scalable data transformations with PySpark and dbt, analytical star schemas, role-based access control, and automated data quality checks.</p>
      <p>
        <a href="https://github.com/yogeshrajput7906/food-delivery-ai-data-platform" target="_blank"><img src="https://img.shields.io/badge/Repository-food--delivery--platform-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/Medallion%20Lakehouse-Bronze%2FSilver%2FGold-8B5CF6?style=flat-square" alt="Lakehouse" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark" />
        <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
        <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Airflow" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">Movie Recommendation System</h3>
      <p><strong>Content-Based &amp; Collaborative Filtering Engine</strong></p>
      <p>Personalized movie recommendation application utilizing NLP feature extraction and vector space similarity. Computes high-dimensional cosine similarity across metadata (genres, cast, crew, overview tags), serving low-latency real-time recommendations with an intuitive interactive front end.</p>
      <p>
        <a href="https://github.com/yogeshrajput7906/Movie-Recommendation-System" target="_blank"><img src="https://img.shields.io/badge/Repository-Movie--Recommendation-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/Cosine%20Similarity-NLP-38BDF8?style=flat-square" alt="Similarity" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
        <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">Wanderbricks Databricks Lakehouse</h3>
      <p><strong>Production Lakehouse Platform, Delta Lake &amp; PySpark Pipelines</strong></p>
      <p>Production data lakehouse built with <strong>Databricks Asset Bundles (DABs)</strong> and <strong>Delta Lake</strong>. Implements ACID transactions, schema enforcement, time travel, dimensional modeling, automated orchestrations, and data monitoring.</p>
      <p>
        <a href="https://github.com/yogeshrajput7906" target="_blank"><img src="https://img.shields.io/badge/Repository-databricks--wanderbricks-181717?style=flat-square&logo=github" alt="Repo" /></a>
        <img src="https://img.shields.io/badge/Delta%20Lake-PySpark-00ADD4?style=flat-square" alt="Delta" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
        <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark" />
        <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square" alt="Delta Lake" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      </p>
    </td>
  </tr>
</table>

---

### Technical Competencies

<div align="center">

| Domain | Core Technologies &amp; Tooling |
| :--- | :--- |
| **Data Engineering &amp; Lakehouse** | ![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat-square) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Machine Learning &amp; AI** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Software Engineering &amp; DevOps** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Ruff](https://img.shields.io/badge/Ruff-261230?style=flat-square&logo=ruff&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Visualization &amp; MLOps** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |

</div>

<details>
  <summary><strong>Deep-Dive: Comprehensive Technical Stack &amp; Tooling</strong></summary>
  <br />

  - **Languages:** Python (3.10+), SQL (advanced — window functions, MERGE, recursive CTEs, query optimization), Bash.
  - **Data Engineering:** Medallion (Bronze/Silver/Gold) lakehouse design, star schemas, SCD Type 2 history, partitioned incremental loads, idempotent ETL/ELT pipelines, schema enforcement and evolution.
  - **Lakehouse &amp; Cloud:** Databricks (Workflows, Notebooks, Asset Bundles / DABs), Delta Lake, Apache Spark / PySpark, PostgreSQL, cloud data integration.
  - **Machine Learning &amp; Time Series:** Long Short-Term Memory (LSTM), neural network regression, sliding-window sequence engineering, technical indicators (SMA, EMA, RSI), feature normalization, leak-free preprocessing, persistence baselines.
  - **Software Engineering &amp; Testing:** Modular package design, type hinting, unit testing with pytest (fixtures, edge cases, schema tests), Ruff linting & formatting, Git branch workflows, GitHub Actions CI.
  - **Serving &amp; UI:** Streamlit dashboards, REST API endpoints, headless Matplotlib figure generation.
</details>

---

### Core Engineering Tenets

> *"A pipeline you can't re-run isn't a pipeline. A model without a baseline isn't a benchmark. Good engineering is what makes both reliable."*

- **Leak-Free by Design:** In time-series and ML pipelines, strict chronological boundaries and out-of-sample scaling prevent data leakage before it happens.
- **Measure Against Baselines:** Every neural network belongs next to a transparent baseline. Reporting real numbers honestly is the foundation of engineering maturity.
- **Idempotent by Default:** Pipelines should be safely re-runnable without duplicate records or side effects.
- **Automated Quality Gates:** Linting, tests, and CI workflows verify correctness on every commit, keeping the main branch production-ready.

---

<div align="center">
  <p>
    <strong>Open to Data Engineering, Machine Learning, and Software Engineering roles, and open to collaborating on high-impact projects.</strong>
  </p>
  <a href="mailto:yogeshrajput7080@gmail.com">
    <img src="https://img.shields.io/badge/Initiate%20Contact-Get%20in%20Touch-38BDF8?style=for-the-badge&logo=mailgun&logoColor=white" alt="Get in Touch" />
  </a>
  <a href="https://www.linkedin.com/in/yogesh-rajput">
    <img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>

  <br/><br/>

  <a href="https://github.com/yogeshrajput7906">
    <img src="https://komarev.com/ghpvc/?username=yogeshrajput7906&label=PROFILE%20VIEWS&color=0284c7&style=flat-square" alt="Profile Views" />
  </a>
</div>
