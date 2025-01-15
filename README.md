# Hello, I'm Ayush Singh
**Data Science & Finance Student @USYD**  

I am currently pursuing a Data Science and Finance degree at the University of Sydney, where my primary intellectual curiosities revolve around advanced machine learning paradigms, high-dimensional data orchestration, and the synergy between quantitative finance models and cutting-edge AI. My research interests include developing scalable multi-model architectures, optimizing hyperparameters for XGBoost regressors with Bayesian techniques, and leveraging HPC concurrency for ephemeral AI pipelines.

---

## Technical Focus

- **Multi-Model Orchestration**: I employ ephemeral concurrency patterns (e.g., HPC cluster scaling, containerized workloads) to dynamically instantiate and manage multiple LLMs tailored for diverse problem domains.
- **High-Dimensional Data Processing**: Expertise in Dask-based distributed data manipulation, iterative imputation methods, and sophisticated feature engineering for real-time market forecasting.
- **Spatial and Geospatial Analytics**: Advanced knowledge of PostGIS for geospatial indexing and queries, harnessed to develop robust "bustling score" metrics and urban analytics pipelines.
- **Explainable AI**: Proficient in generating SHAP values for local and global interpretability, especially in domains requiring transparency and interpretability of complex models.
- **Quantitative Finance**: Strong background in statistical modeling, particularly time-series analysis and predictive modeling for market data. Emphasis on advanced regularization techniques and Bayesian optimization.

---

## Pinned Projects

### 1. Multi Model AI Agent
**Repository**: [Multi Model AI Agent (link)](https://github.com/Ayush-Singh-31/Ai-Agent)  
A robust orchestration script for managing multiple domain-specific Large Language Models (LLMs) using [Ollama](https://ollama.ai/). Key functionalities include:

- **Dynamic Model Lifecycle**: Automatic creation and teardown of specialized LLMs via `ollama create` and `ollama rm`.
- **Task Classification & Decomposition**: Breaks down user inputs into domain-specific tasks (e.g., Decider, Language, Task-Breaker) using hierarchical prompt engineering strategies.
- **Contextual Session Management**: Maintains ephemeral states to facilitate concurrent usage of multiple LLM instances, enabling minimal overhead in HPC or containerized environments.
- **Custom Parameterization**: Extendable logic to incorporate specialized hyperparameters, context windows, or advanced concurrency patterns for large-scale deployments.

### 2. Real-Time Market Forecasting Model
**Repository**: [Real-Time Market Forecasting (link)](https://github.com/Ayush-Singh-31/Market-Data-Forecasting)  
An intricate pipeline for:

- **High-Dimensionality**: Reading and aggregating large Parquet files with Dask while tracking and imputing missing data to maintain data consistency.
- **Feature Engineering**: Automated transformations, scaling, and feature selection for downstream regression tasks.
- **Modeling & Interpretability**: Employing an XGBoost regressor with R² ~ 0.99 and complementing it with SHAP-based explanations to illuminate model decisions.
- **Next Steps**: Iterative improvement through Bayesian hyperparameter tuning, distributed training approaches, and domain-specific feature expansions.

### 3. Greater Sydney Area Data Analysis Project
**Repository**: [Sydney Bustling Score (link)](https://github.com/Ayush-Singh-31/Sydney-Postgres-Analysis)  
A geospatial analytics initiative using PostgreSQL + PostGIS and Python to calculate a "bustling score" for distinct regions across Sydney:

- **Database Architecture**: Advanced indexing for high-efficiency spatial queries; integrated with large-scale open datasets (e.g., public transport, green spaces, parking).
- **Data Pipeline**: SQL scripts for schema creation and data cleaning, Python routines for data ingestion, spatial transformations, and generating visualizations.
- **Analytics & Reporting**: Combines multiple city metrics—transport density, public amenities, population distribution—to build a comprehensive indicator of urban vibrancy.

---

## Skill Set

- **Languages**: Python (NumPy, Pandas, Dask), SQL (PostgreSQL, PostGIS), R (basic modeling)
- **ML/AI Frameworks**: TensorFlow, PyTorch, XGBoost, scikit-learn
- **Data Infrastructure**: Docker, HPC cluster orchestration, containerized ephemeral concurrency
- **DevOps & Automation**: GitHub Actions, container-based workflows, CI/CD
- **Analytical Techniques**: Statistical modeling, hierarchical decomposition, advanced time-series forecasting, and model interpretability

---

## Future Trajectory

I aim to synthesize my proficiency in quantitative finance with sophisticated AI toolchains to innovate in algorithmic trading, risk analysis, and large-scale data intelligence. My aspiration is to architect high-performance, multifaceted data systems that seamlessly integrate domain-specific knowledge with next-generation AI solutions.

Feel free to connect or explore my repositories for a deeper dive into my work. I’m always enthusiastic about discussing concurrency optimizations, HPC strategies, and groundbreaking AI research!
