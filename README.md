<br>

  Data Scientist and ML Engineer with **7 years of experience** taking models from notebook to production, and the data engineering background to build the pipelines underneath them. I work across the full path:
  **Spark, Kafka, Databricks and Delta Lake** for the data layer, **XGBoost, LightGBM and PyTorch** for the models, and **LangGraph, fine-tuning and RAG evaluation** for the agentic AI layer. Seven years across
  supply chain, retail pricing and e-commerce, plus graduate research in clinical AI. M.S. in Computer Science, Rochester Institute of Technology (May 2026).

  <br>

  | Area | What I build | Proof point |
  |---|---|---|
  | **Data Science** | Forecasting, pricing, experimentation | Demand forecasting across 6,500+ SKUs, 8% MAE reduction |
  | **ML Engineering** | Training to serving to automated retraining | LightGBM pricing API on AWS ECS, 30 min to 5 s turnaround |
  | **Applied AI** | Agentic RAG, fine-tuning, LLM evaluation | 41.5% on FinanceBench vs 19% for GPT-4 Turbo |
  | **Data Engineering** | Batch and streaming pipelines, lakehouse, dbt | Kafka to Spark to Delta Lake with exactly-once processing |

  <br>

  <a id="data-science"></a>

  ### 📊 Data Science & ML

  **[Vehicle Price Prediction with AWS CI/CD](https://github.com/reetu95/AWS-CI-CD-Proejct)** · *featured*

  `Used car data → CatBoost / XGBoost model bake-off → Flask app → Docker → Amazon ECR`

  A web app that predicts the fair price of a used car from details like brand, year, mileage and accident history. Several models are trained and compared to pick the best performer, and every code push
  automatically builds a Docker image and deploys the app to AWS through **GitHub Actions**.

  **[CFD-ML Surrogate for Heat Sink Thermal Prediction](https://github.com/reetu95/cfd-ml-surrogate-heatsink)**

  `25 CFD simulations → PyTorch neural network surrogate → full 3D temperature field in 40 ms`

  A neural network that replaces hours of physics simulation with a 40 ms prediction, a **22,000x speedup** over OpenFOAM at 0.034 K mean absolute error. Basis for the ASME FEDSM 2026 publication.

  **[→ All Data Science & ML projects](https://github.com/reetu95/projects#-data-science--ml)**

  <br>

  <a id="genai"></a>

  ### 🤖 AI & GenAI

  **[AI Powered Financial Document Analysis](https://github.com/reetu95/AI-Powered-Financial-Document-Analysis)** · *featured*

  `Financial PDFs → FAISS + BM25 hybrid retrieval → LangGraph agent → Llama 3.1`

  An AI system that reads financial reports and answers questions about the numbers inside them, reviewing and correcting its own answers before responding. It scored **41.5% on FinanceBench**, more than double
  the 19% scored by GPT-4 Turbo.
  
  **Clinical GraphRAG for Echocardiogram Reports** · *research, RIT*
  
  `MedGemma + QLoRA → GraphRAG over clinical entities → severity classification`
  
  Fine-tuned a medical LLM and built a graph-based retrieval pipeline that links clinical entities across echocardiogram reports, improving contextual retrieval for rare cardiac conditions. Reached **82.5% F1 and 
  90% recall on the highest risk class**.
  
  **[Enterprise RAG Service](https://github.com/reetu95/enterprise-rag-service)**
  
  `FastAPI → async ingestion with OCR fallback → ChromaDB → metadata-filtered top-K retrieval`
  
  A production-oriented RAG backend that ingests documents asynchronously, falls back to OCR for scanned PDFs, and serves metadata-filtered semantic retrieval over the results.
  
  **[→ All AI & GenAI projects](https://github.com/reetu95/projects#-ai--genai)**

  <br>

  <a id="data-engineering"></a>

  ### ⚙️  Data Engineering

  **[Real Time Inventory Lakehouse](https://github.com/reetu95/realtime-inventory-lakehouse)** · *featured* 
  
  `Kafka → Spark Structured Streaming → Delta Lake (Bronze / Silver / Gold) on Databricks`
  
  A streaming pipeline that processes inventory events the moment they happen, counting every event exactly once even through failure and recovery. A built-in quality check quarantines bad records automatically
  and caught a hidden bug that was silently dropping **20% of events**. Infrastructure provisioned with Terraform, dbt tests running in CI.
  
  **[dbt + Snowflake Analytics Engineering](https://github.com/reetu95/DBT-Snowflake-project)**
  
  `Raw source tables → dbt models → Snowflake → tested, lineage-tracked marts`
  
  Transforms raw source data into clean, analytics-ready models with automated data quality tests and full lineage tracking, so every number on a dashboard can be traced back to where it came from.

  **[→ All Data Engineering projects](https://github.com/reetu95/projects#-data-engineering)**

  <br>
  
  <a id="stack"></a>

  ### 🛠️  Core Stack

  **ML & Modeling**

  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" alt="XGBoost" />
  <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black" alt="CatBoost" />
  <img src="https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge" alt="LightGBM" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow" />

  **Data & Analytics**

  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />

  **GenAI & LLMs**

  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS" />
  <img src="https://img.shields.io/badge/GraphRAG-7C3AED?style=for-the-badge" alt="GraphRAG" />
  <img src="https://img.shields.io/badge/QLoRA-A78BFA?style=for-the-badge" alt="QLoRA" />
  <img src="https://img.shields.io/badge/Llama-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Llama" />

  **Data Platforms & Cloud**

  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logo=delta&logoColor=white" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />

  <br>

  <a id="research"></a>

  ### 📄 Research, Writing & Credentials

  - **ASME FEDSM 2026:** Machine Learning Applied for Instant Predictions of Spatial Temperature Variations in Heat Sinks for Computer Chip Cooling
  - **ASME FEDSM 2026:** Towards Utilizing Machine Learning and Computational Fluid Dynamics in the Classroom to Generate Methods for High Heat Dissipation
  - **Accepted abstract:** AI Medical Report Analysis, an agentic GraphRAG system for heart scan severity classification
  - **Certified:** Microsoft Certified: Azure Data Fundamentals · Databricks Lakehouse Fundamentals
  - ✍️  [Blog posts on Medium](https://medium.com/@reetuthimmaiah)

  <br>

  <div align="center">

  📫 Open to **Data Science, Machine Learning, Applied AI and Data Engineering** roles: <a href="mailto:reetu.thimmaiah@gmail.com">reetu.thimmaiah@gmail.com</a>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F5A524,50:A78BFA,100:2DD4BF&height=110&section=footer" alt="footer" />

  </div>
