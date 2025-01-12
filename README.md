# Data Scientist | Software Developer
#### 👷🏼 [https://www.linkedin.com/in/supreet-sharma-082bb4100/](https://www.linkedin.com/in/supreet-sharma-082bb4100/)
#### 📜 [Resume](https://github.com/supreetshm947/portfolio/blob/main/Supreet_Sharma_Resume.pdf)
#### Technical Skills: Python, Pytorch, MLOps, Generative AI, DevOps, AWS, DATALAKE, Java, SQL

## Education				       		
- M.S., Data Science	      | RWTH Aachen University, Aachen, Germany (_November 2024_)	 			        		
- B.Tech., Computer Science | SRM University, Chennai, India (_June 2016_)

## Work Experience
- **Generative AI Developer (Student Assistant) @ E.ON Energy Research Center (_December 2023 – July 2024_)**

- **Data Engineer @ Munich RE (_April 2023 – October 2023_)**

- **Research and Development Engineer @ Dassault Systèmes (_February 2018 – March 2020_)**

- **Assistant System Engineer @ Tata Consultancy Services (_May 2016 - February 2018_)**

## Projects
### Learning Heuristics for Counting Problems with Graph Neural Networks - Masters Thesis, 2024
[GitLab](https://git.rwth-aachen.de/supreetshm947/anycsp_enum/)

<p align="center">
  <img src="anycsp_grid.gif" alt="grid"><br>
  <em>ANYCSP enumerating 2-coloring solution for an 11 x 11 Grid graph.</em>
</p>

**TechStack:** Python, Pytorch, Numpy, NetworkX, Pandas, Matplotlib, Tensorboard, Deep Learning, Convolution Neural Networks, Graph Neural Networks, Recurrent Neural Networks, Reinforcement Learning

Built on the foundation of [ANYCSP](https://arxiv.org/abs/2208.10227), which addresses Constraint Satisfaction Problems (CSPs) as a decision problem, this work extends its application to counting problems in Graph Coloring and Boolean Satisfiability.

The model introduces a novel Graph Representation called the Constraint Value Graph, which represents input CSP problems and processes them through a Recurrent Graph Neural Network sampling a list of solutions. It is trained through Reinforcement learning on a configurable training distribution that generates random instances.

### Document Chat Agent with n8n
[Github](https://github.com/supreetshm947/document_conv_agent)

<p align="center">
  <img src="workflow_n8n.png" alt="grid"><br>
</p>

**TechStack:** Docker, N8N, RAG, Vector Database, Vector Embeddings, Webhooks, Cohere, Gemini, Google AI Studio, GenAI, Large Language Models

An AI Agent designed for seamless interaction with documents, built using n8n (workflow automation platform), Gemini, and Supabase. This system automates document ingestion from Google Drive, transforms them into embeddings with Cohere, and stores them in a vector database to enable fast and accurate semantic search.

### End-to-end Model Deployment Pipeline
[Github](https://github.com/supreetshm947/VirtualMindsTask_Airflow)

<p align="center">
  <img src="mlops_workflow.png" alt="grid"><br>
</p>

A Machine Learning pipeline orchestrated using Apache Airflow that automates model training, experiment tracking using MLflow, model artifact storage in MinIO, and deployment of the trained model as a FastAPI service. Additionally, it provides CI/CD automation for deploying Docker images to Kubernetes, and monitoring with Prometheus, InfluxDB, and Grafana, sending Alerts on Slack.

### GenAIStackOverflow
[Github](https://github.com/supreetshm947/GenAIStackOverflow)

<p align="center">
  <img src="genai_workflow.png" alt="genai_workflow"><br>
</p>

Developed a GenAI project which involves fetching relevant, answered StackOverflow posts using the API, generating vector embeddings with Cohere, and storing them in Qdrant for similarity matching. The post data is stored in PostgreSQL, while the RAG system retrieves relevant posts and combines them with user queries for LLM-driven responses. The frontend is built with Streamlit, and Docker with GitLab CI/CD ensures streamlined deployment and scalability.

### CryptoDataPipeline
[Github](https://github.com/supreetshm947/CryptoDataPipeline)

<p align="center">
  <img src="crypto_app_flow.png" alt="crypto_app"><br>
</p>

Developed a comprehensive data pipeline for acquiring both real-time and historical cryptocurrency pricing data, as well as related Reddit submissions. Orchestrated data collection with Apache Airflow and used PySpark to load data into a Datalake via a Minio Docker Container. Implemented real-time trend analysis by collecting Reddit submissions through Airflow DAGs, storing them in Elasticsearch, and later in Datalake parquet format for sentiment analysis. This ongoing personal project focuses on integrating sentiment analysis with pricing data and plans to incorporate LLMs using Retrieval-Augmented Generation (RAG).

### Machine Learning (MLOps) Workflow and Deployment using ZENML for an Image Classification Model

[Github](https://github.com/supreetshm947/MLOps_ImageClassification)

<p align="center">
  <img src="mlflow_classifier.png" alt="mlflow_classifier"><br>
</p>

I implemented a holistic machine learning workflow, including deployment, for an image classification model built with PyTorch and trained on the CIFAR-100 dataset. The MLOps pipeline was developed using ZenML for orchestration, covering all stages from data ingestion and processing to model training, evaluation, and deployment. I created a Streamlit application as the web user interface, allowing end users to upload and classify images. Additionally, I set up a FastAPI server for backend services to facilitate communication between the Streamlit app and the deployed model on the MLOps server for inference. The goal was to showcase the integration of machine learning pipelines with MLOps tools and demonstrate how to serve a deep learning model using a modern full-stack setup.

### Semantic Analyser

[Github](https://github.com/supreetshm947/SemanticAnalyzer)

In this project, I implemented SemanticAnalyzer, a sentiment analysis tool that classifies text reviews as either positive or negative. Using the PyTorch framework, which includes a Deep Learning Network, to capture the nuances of language and context. The model is trained and evaluated on the IMDB movie review [Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).


### Graph Learning, 2021

[Github](https://github.com/supreetshm947/Graph_ML)

<p align="center">
  <img src="node_embedding.webp" alt="node_embedding"><br>
  <em><a href="https://medium.com/the-modern-scientist/graph-neural-networks-series-part-3-node-embedding-36613cc967d5">SOURCE</a></em>
</p>

I took a Graph Learning Laboratory course in the Summer of 2021 during my Master's, where I was introduced to and implemented various Graph Learning algorithms, evaluating them on multiple datasets. Throughout the lab, I implemented the Graphlet Kernel and Closed Walk Kernel to obtain vector embeddings and worked on the Weisfeiler-Leman Kernel, computing vector embeddings based on the coloring scheme produced by the algorithm. Additionally, I built a simple Graph Convolution Network (GCN) using a Normalized Adjacency Matrix and Node Attributes for Node Classification. I also implemented a model to compute node2vec embeddings for graphs, training it for Node Classification tasks on the Citeseer and Cora datasets, and Link Prediction tasks on Facebook and PPI datasets. Furthermore, I developed a Message Passing Graph Neural Network and performed a regression task on the ZINC dataset.

### AI Snake Game , 2022
[Github](https://github.com/supreetshm947/AISnake)

<p align="center">
  <img src="snake_demo.gif" alt="snake_demo"><br>
</p>

Developed a self-playing Snake game using Reinforcement Learning, leveraging the Bellman Equation to update model parameters. The game’s user interface was created with PyGame, while the model itself was built using PyTorch.

### Covid Tableau Dashboard, 2022

[Tableau](https://public.tableau.com/app/profile/supreet.sharma/viz/Covid_data_demo)

<p align="center">
  <img src="covid_dashboard.jpg" alt="covid_dashboard"><br>
</p>

Performed data exploration on Covid data using SQL, and then imported the analyzed data into Tableau to develop a dashboard that visualized Covid infection rates around the world.

