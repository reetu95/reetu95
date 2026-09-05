<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:F5A524,50:A78BFA,100:2DD4BF&height=190&section=header&text=Reetu%20Thimmaiah&fontSize=58&fontColor=FFFFFF&fontAlignY=32&desc=Data%20Scientist%20%C2%B7%20Applied%20AI&descSize=17&descAlignY=52)

<a href="[https://linkedin.com/in/reetu-t](https://datascience-portfolio-nine.vercel.app/)"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=Portfolio&logoColor=white" /></a>&nbsp;
<a href="https://linkedin.com/in/reetu-t"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;
<a href="mailto:reetu.thimmaiah@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;
<a href="https://medium.com/@reetuthimmaiah"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" /></a>&nbsp;
<img src="https://komarev.com/ghpvc/?username=reetu95&color=A78BFA&style=for-the-badge&label=PROFILE+VIEWS" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=850&lines=Data+Science+%E2%86%92+ML+%E2%86%92+AI;Streaming+Pipelines%2C+Lakehouse+%26+MLOps;Agentic+RAG%2C+LLM+Fine-Tuning+%26+Evaluation;7+years+turning+data+into+decisions" alt="typing" />

</div>

<br>

Hi, I'm Reetu

I’m a Data Scientist with over six years of experience delivering measurable business impact through machine learning.

1) I developed an automated vehicle pricing system that
<strong>increased profit per car by approximately 18%</strong> and
<strong>automated 80% of eligible pricing decisions</strong>.

2) Built a supply chain decision support solution that identified
<strong>around 7% in potential cost savings</strong> across
<strong>10,000–15,000 monthly stock transfers</strong>.

3) In e-commerce, developed a recommendation system that
<strong>increased email-attributed sales by approximately 30%</strong>
in a randomized A/B test.

Lately I've been working with LLMs: agentic RAG with LangGraph and Llama 3.1,
multi-agent workflows with CrewAI, and evaluation harnesses using RAGAS.

<strong>Toolkit:</strong> Python, SQL, PyTorch, Spark, Kafka, Databricks,
Snowflake, dbt, MLflow, AWS, Azure

<strong>M.S. Computer Science, RIT.</strong>
Research on ML surrogates for thermal prediction published at
<strong>ASME FEDSM 2026</strong>.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

  ### 📊 Data Science & ML

  **[ML Surrogate for Heat Sink Cooling](https://github.com/reetu95/cfd-ml-surrogate-heatsink)** &nbsp; <img src="https://img.shields.io/badge/Featured-A78BFA?style=flat-square" /> <img 
  src="https://img.shields.io/badge/ASME%20FEDSM%202026-2DD4BF?style=flat-square" />

  `25 OpenFOAM CFD runs → 1.9M mesh samples → PyTorch surrogate → full 3D temperature field in 40 ms`

  Thermal design is bottlenecked by simulation: one CFD solve of a pin-fin heat sink takes ~15 minutes, so sweeping 1,000 geometries costs ~250 CPU-hours. A feed-forward network trained on 25 simulations predicts
  the entire temperature field in **40 ms — a 22,500× speedup** — at **MAE 0.021 K** and **R² 0.999997** across 383,138 held-out points. Accepted to ASME FEDSM 2026.

  <br>

  **[Churn Without a Cancel Button](https://github.com/reetu95/Customer-Retention-Segmentation-Uplift)** &nbsp; <img src="https://img.shields.io/badge/Live%20app-F5A524?style=flat-square" />

  `Randomised holdout → uplift models → budget-constrained targeting → Streamlit app`

  Retail customers never click cancel, they just stop coming back, so churn has to be inferred rather than observed. Using a campaign's randomised control group to measure what an offer actually *caused*, the
  finding is that the ranking flips depending on what you count: at a 5% budget, targeting by likely response returns **147** extra purchases per 1,000 customers against **32** for targeting by churn risk, but the
  keenest responders spend the least, so weighting response by value gives **₽1.24M** incremental revenue against **₽0.27M**. Neither "who is leaving" nor "who responds" is enough alone.

  <br>

  **[PriceWise — C2B Vehicle Pricing](https://github.com/reetu95/AutopricingNew)**

  `Used car data → CatBoost on log price → pricing rules → FastAPI → React ops console`

  Not a notebook but a pricing product: a user enters vehicle details and the system predicts market value, recommends an acquisition offer, estimates margin after reconditioning, flags quotes needing approval,
  and logs whether each recommendation was accepted, rejected, or **overridden** — closing the loop between the model and the people using it.

  **[→ All Data Science & ML projects](https://github.com/reetu95/projects#-data-science--ml)**

  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />

  
  ### 🤖 AI & GenAI

  **[AI Powered Financial Document Analysis](https://github.com/reetu95/AI-Powered-Financial-Document-Analysis)** &nbsp; <img src="https://img.shields.io/badge/Featured-A78BFA?style=flat-square" />

  `Financial PDFs → FAISS + BM25 hybrid retrieval → LangGraph agent → Llama 3.1`

  An AI system that reads financial reports and answers questions about the numbers inside them, reviewing and correcting its own answers before responding. It scored **41.5% on FinanceBench** — more than double
  the 19% scored by GPT 4 Turbo.

  **[→ All AI & GenAI projects](https://github.com/reetu95/projects#-ai--genai)**
  
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />



  ### 🛠️  Core Stack

  **ML & Modeling**
  
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img 
  src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge" /> <img 
  src="https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge&logoColor=black" /> <img src="https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge" /> <img 
  src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
  
  **GenAI & LLMs**
  
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> <img 
  src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white"
  /> <img src="https://img.shields.io/badge/GraphRAG-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/QLoRA-A78BFA?style=for-the-badge" /> <img 
  src="https://img.shields.io/badge/Llama-0866FF?style=for-the-badge&logo=meta&logoColor=white" />
  
  **Cloud & DevOps**
  
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" /> <img 
  src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" />
  
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:F5A524,50:A78BFA,100:2DD4BF&height=2" />
  
  ### 📄 Research & Writing
  
  - **ASME FEDSM 2026** — Machine learning for instant prediction of spatial temperature variations in heat sinks for computer chip cooling
  - ✍️  [Blog posts on Medium](https://medium.com/@reetuthimmaiah)
  
  <br>
  
  <div align="center">
  
  📫 Open to <b>Data Science roles</b> roles &nbsp;·&nbsp; <a href="mailto:reetu.thimmaiah@gmail.com">reetu.thimmaiah@gmail.com</a>
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F5A524,50:A78BFA,100:2DD4BF&height=110&section=footer" alt="" />
  
  </div>

