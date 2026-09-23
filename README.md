<div align="center">

<h1>Hi, I'm Reetu</h1>

<h3>Data Scientist · Experimentation, Causal Inference & ML</h3>

<p>6+ years turning data into pricing, supply chain, and product decisions</p>

<p>
  <strong>What should we price?</strong>
  &nbsp;&nbsp; • &nbsp;&nbsp;
  <strong>Where should inventory move?</strong>
  &nbsp;&nbsp; • &nbsp;&nbsp;
  <strong>What should we recommend?</strong>
  &nbsp;&nbsp; • &nbsp;&nbsp;
  <strong>And did it actually work?</strong>
</p>

<br>

<a href="https://datascience-portfolio-nine.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white" /></a>&nbsp;
<a href="https://linkedin.com/in/reetu-t">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;
<a href="mailto:reetu.thimmaiah@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;
<a href="https://medium.com/@reetuthimmaiah">
  <img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" /></a>
</div>

<h2>Industry Impact</h2>

<table>
<tr>

<td width="33%" align="center">
  <img src="images/Automobile.png" width="220" alt="Vehicle Pricing">
  <br><br>
  <strong>Vehicle Pricing</strong>
  <br>
  <strong>↑ ~18% profit per car</strong>
  <br>
  <strong>80% of pricing automated</strong>
  <br><br>
  Automated pricing for a German automobile client, with the profit lift measured through randomized A/B tests against manual pricing.
</td>

<td width="33%" align="center">
  <img src="images/Supplychain.png" width="220" alt="Supply Chain">
  <br><br>
  <strong>Supply Chain Optimization</strong>
  <br>
  <strong>~4.5% potential cost savings</strong>
  <br>
  <strong>10K–15K transfers/month</strong>
  <br><br>
  ML decision support for stock-transfer sourcing, saving procurement admins 1.5 hours a day.
</td>

<td width="33%" align="center">
  <img src="images/Ecommerce.png" width="220" alt="E-commerce">
  <br><br>
  <strong>E-commerce Experimentation</strong>
  <br>
  <strong>Email share of sales: 3% → 7%</strong>
  <br>
  <strong>10+ A/B tests per quarter</strong>
  <br><br>
  Designed and analyzed email experiments, and A/B-tested a cart-abandonment recommender that contributed to ~30% quarter-over-quarter growth in email-attributed sales.
</td>

</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

### 📊 Product & Decision Science

**[Churn Without a Cancel Button](https://github.com/reetu95/Customer-Retention-Segmentation-Uplift)** &nbsp; <img src="https://img.shields.io/badge/Featured-A78BFA?style=flat-square" /> <img src="https://img.shields.io/badge/Live%20app-F5A524?style=flat-square" />

`Randomized holdout → uplift models → budget-constrained targeting → Streamlit app`

Retail customers never click cancel. They just stop coming back, so churn has to be inferred rather than observed. Using a campaign's randomized control group to measure what an offer actually *caused*, the ranking flips depending on what you count. At a 5% budget, targeting by likely response returns **147** extra purchases per 1,000 customers, against **32** for targeting by churn risk. But the keenest responders spend the least, so weighting response by value gives **₽1.24M** incremental revenue against **₽0.27M** (figures in the dataset's currency, Russian rubles). Neither "who is leaving" nor "who responds" is enough on its own.

<br>

**[→ All Data Science & ML projects](https://github.com/reetu95/projects#-data-science--ml)**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

### 🤖 AI & GenAI

**[AI Powered Financial Document Analysis](https://github.com/reetu95/AI-Powered-Financial-Document-Analysis)**

`Financial PDFs → FAISS + BM25 hybrid retrieval → LangGraph agent → Llama 3.1`

An AI system that reads financial reports and answers questions about the numbers inside them, reviewing and correcting its own answers before responding. It scored **41.5% on FinanceBench**, more than double the 19% scored by GPT-4 Turbo.

I also build multi-agent workflows with CrewAI and evaluation harnesses with RAGAS.

**[→ All AI & GenAI projects](https://github.com/reetu95/projects#-ai--genai)**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

### 🔬 Research

**[ML Surrogate for Heat Sink Cooling](https://github.com/reetu95/cfd-ml-surrogate-heatsink)** &nbsp; <img src="https://img.shields.io/badge/ASME%20FEDSM%202026-2DD4BF?style=flat-square" />

`25 OpenFOAM CFD runs → 1.9M mesh samples → PyTorch surrogate → full 3D temperature field in 40 ms`

Thermal design is bottlenecked by simulation: one CFD solve of a pin-fin heat sink takes ~15 minutes, so sweeping 1,000 geometries costs ~250 CPU-hours. A feed-forward network trained on 25 simulations predicts the entire temperature field in **40 ms, a 22,500× speedup**, at **MAE 0.021 K** across 383,138 held-out points.

**Publications**

- **ASME FEDSM 2026** — Machine learning for instant prediction of spatial temperature variations in heat sinks for computer chip cooling (lead author)
- Towards utilizing machine learning and computational fluid dynamics in the classroom for high heat dissipation
- ✍️ [Blog posts on Medium](https://medium.com/@reetuthimmaiah)

**M.S. Computer Science, Rochester Institute of Technology**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

### 🛠️ Core Stack

**Experimentation & Analytics**

<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/A%2FB%20Testing-2DD4BF?style=for-the-badge" /> <img src="https://img.shields.io/badge/Causal%20Inference-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/Uplift%20Modeling-F5A524?style=for-the-badge" /> <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" /> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />

**ML & Modeling**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" /> <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black" /> <img src="https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />

**Data Platforms**

<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" /> <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" /> <img src="https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" /> <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />

**GenAI & LLMs**

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" /> <img src="https://img.shields.io/badge/GraphRAG-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/QLoRA-A78BFA?style=for-the-badge" /> <img src="https://img.shields.io/badge/Llama-0866FF?style=for-the-badge&logo=meta&logoColor=white" />

**Cloud & DevOps**

<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />

<br>

<div align="center">

📫 Open to <b>Product Data Science & Data Science roles</b> &nbsp;·&nbsp; <a href="mailto:reetu.thimmaiah@gmail.com">reetu.thimmaiah@gmail.com</a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F5A524,50:A78BFA,100:2DD4BF&height=110&section=footer" alt="" />

</div>
