# 📘 AWS Certified AI Practitioner (AIF-C01) Study Guide  
## Domain 1: Fundamentals of AI and ML (20%)

### Task Statement 1.1: Explain basic AI concepts and terminologies

---

### 🧠 Basic AI Terms

| Term | Description |
|------|-------------|
| **AI (Artificial Intelligence)** | Broad field of computer science focused on creating systems capable of performing tasks that require human intelligence. |
| **ML (Machine Learning)** | A subset of AI that enables systems to learn patterns from data and make predictions or decisions without being explicitly programmed. |
| **Deep Learning** | A subfield of ML using neural networks with many layers to model complex patterns in data. |
| **Neural Network** | A network of interconnected nodes (neurons) modeled after the human brain that can learn from data. |
| **Computer Vision** | AI field focused on enabling machines to interpret and make decisions based on visual input (images or video). |
| **Natural Language Processing (NLP)** | AI field focused on understanding, interpreting, and generating human language. |
| **Model** | A mathematical representation trained on data to perform a specific task like classification or regression. |
| **Algorithm** | A set of rules or instructions for solving a problem or performing a task (e.g., training a model). |
| **Training** | The process of teaching a model by feeding it labeled data to learn patterns. |
| **Inferencing** | Using a trained model to make predictions or decisions based on new input data. |
| **Bias** | Systematic errors in model predictions caused by skewed training data or model design. |
| **Fairness** | Ensuring models do not discriminate or produce biased results against individuals or groups. |
| **Fit** | The model’s ability to learn patterns from training data. Includes underfitting and overfitting. |
| **Large Language Model (LLM)** | A deep learning model trained on massive text corpora to understand and generate human language (e.g., GPT, Claude). |

---

### 🤖 AI vs ML vs Deep Learning

| Feature | AI | ML | Deep Learning |
|--------|----|----|---------------|
| **Definition** | Broad area of intelligent systems | Subset of AI | Subset of ML |
| **Scope** | Includes logic, planning, robotics, NLP | Focuses on data-driven prediction | Uses complex neural networks |
| **Data Dependence** | May not always need large data | Requires labeled data | Requires massive datasets |
| **Example** | Rule-based systems | Spam filtering | Self-driving cars |

---

### ⏱️ Types of Inferencing

| Type | Description | Use Case Example |
|------|-------------|------------------|
| **Batch Inference** | Running inference on a large dataset at once (offline). | Fraud detection on past transactions |
| **Real-Time Inference** | Making predictions instantly as new data comes in. | Voice assistant, recommendation engine |

---

### 📊 Types of Data in AI Models

| Data Type | Description |
|-----------|-------------|
| **Labeled** | Data that includes input and correct output (used for supervised learning). |
| **Unlabeled** | Input data without known output (used in unsupervised learning). |
| **Tabular** | Data in rows and columns, like spreadsheets. |
| **Time-Series** | Data collected over time intervals. |
| **Image** | Pixel-based data used in computer vision. |
| **Text** | Written words and sentences used in NLP. |
| **Structured** | Data with clear format and fields (e.g., SQL). |
| **Unstructured** | Data without predefined format (e.g., text, audio, video). |

---

### 🧪 Types of Machine Learning

| Learning Type | Description | Example |
|---------------|-------------|---------|
| **Supervised Learning** | Model is trained on labeled data (input/output pairs). | Email spam detection, image classification |
| **Unsupervised Learning** | Model finds patterns in unlabeled data. | Customer segmentation, anomaly detection |
| **Reinforcement Learning** | Model learns by trial and error to maximize reward in an environment. | Game playing, robotics, self-driving cars |

---

### Task Statement 1.2: Identify practical use cases for AI

#### 📈 Value from AI/ML
- Assists human decision-making (e.g., medical diagnosis, financial forecasting)
- Enables scalability of solutions (e.g., customer support chatbots)
- Automates routine tasks (e.g., invoice processing, quality checks)

#### 🛑 When AI/ML is NOT Appropriate
- Cost outweighs benefit (e.g., building an ML model for small, one-time tasks)
- Situations needing deterministic outcomes (e.g., strict compliance rules)
- Lack of quality data or domain understanding

#### 🎯 ML Techniques and Use Cases

| Technique | Description | Common Use Case |
|----------|-------------|------------------|
| **Regression** | Predicts continuous numeric values | Forecasting revenue, temperature prediction |
| **Classification** | Assigns input to predefined categories | Fraud detection, sentiment analysis |
| **Clustering** | Groups similar data points without labels | Customer segmentation, market basket analysis |

#### 🌍 Real-World AI Applications
- **Computer Vision** – Facial recognition, object detection
- **NLP** – Sentiment analysis, translation
- **Speech Recognition** – Voice assistants (e.g., Alexa)
- **Recommendation Systems** – Amazon product recommendations
- **Fraud Detection** – Credit card anomaly tracking
- **Forecasting** – Inventory, demand, traffic predictions

#### 🧰 AWS Managed AI/ML Services
- **Amazon SageMaker** – End-to-end ML development
- **Amazon Transcribe** – Speech-to-text
- **Amazon Translate** – Language translation
- **Amazon Comprehend** – Text insights (e.g., entities, sentiment)
- **Amazon Lex** – Conversational chatbots
- **Amazon Polly** – Text-to-speech

---

### Task Statement 1.3: Describe the ML development lifecycle

#### 🔄 ML Pipeline Components
1. **Data Collection** – Gathering raw data
2. **Exploratory Data Analysis (EDA)** – Understanding and visualizing data
3. **Data Preprocessing** – Cleaning, normalizing, handling missing values
4. **Feature Engineering** – Creating input features from raw data
5. **Model Training** – Applying ML algorithms to learn patterns
6. **Hyperparameter Tuning** – Optimizing model parameters
7. **Evaluation** – Measuring model performance
8. **Deployment** – Making model available for inference
9. **Monitoring** – Observing performance over time

#### 🏗️ Sources of ML Models
- **Open-source Pre-trained Models** (e.g., Hugging Face, TensorFlow Hub)
- **Custom Models** trained from scratch or fine-tuned

#### 🚀 Deployment Methods
- **Managed API Services** – e.g., SageMaker Endpoints
- **Self-hosted API** – e.g., on EC2 or containers

#### 🧰 AWS Services for Each Stage
| Pipeline Stage | AWS Service |
|----------------|-------------|
| Data Prep | SageMaker Data Wrangler |
| Feature Storage | SageMaker Feature Store |
| Training | SageMaker Studio, SageMaker Training Jobs |
| Tuning | SageMaker Automatic Model Tuning |
| Deployment | SageMaker Endpoints |
| Monitoring | SageMaker Model Monitor |

#### ⚙️ MLOps Concepts
- Experiment tracking
- Reproducible pipelines
- Scalable deployments
- Managing technical debt
- Continuous model monitoring and re-training

#### 📏 Model and Business Metrics
| Metric Type | Examples |
|-------------|----------|
| **Model Performance** | Accuracy, AUC, F1 Score |
| **Business Value** | Cost per user, ROI, user satisfaction, support ticket reduction |

---

✅ Let me know when you're ready to proceed with **Domain 2: Fundamentals of Generative AI (24%)**

