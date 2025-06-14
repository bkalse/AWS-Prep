# 📘 AWS Certified AI Practitioner (AIF-C01) Study Guide  
## Domain 3: Applications of Foundation Models (20%)

---

### Task Statement 3.1: Design Considerations for Applications Using Foundation Models

#### ✅ Model Selection Criteria
| Factor | Description |
|--------|-------------|
| **Cost** | Pay-per-use or hosted model cost, training vs. inference. |
| **Modality** | Input/output types supported (e.g., text, image, audio). |
| **Latency** | Model response time – important for real-time applications. |
| **Multilingual Support** | Ability to understand and generate across languages. |
| **Model Size & Complexity** | Larger models may offer better accuracy but cost more. |
| **Customization Needs** | Support for fine-tuning, prompt tuning, RAG. |
| **Input/Output Length** | Token limits may constrain long context inputs. |

#### 🎚️ Inference Parameters
| Parameter | Purpose |
|-----------|---------|
| **Temperature** | Controls randomness in output (higher = more creative). |
| **Top-k / Top-p Sampling** | Filters token pool to control diversity. |
| **Max Token Length** | Sets output length to avoid unnecessary token use. |

#### 🔍 Retrieval-Augmented Generation (RAG)
- **Definition**: Enhances model responses by retrieving relevant documents before generation.
- **Applications**:
  - Context-rich Q&A from internal knowledge bases
  - Personalized product recommendations
  - Enterprise search experiences
- **AWS Services for RAG**:
  - **Amazon Bedrock** – Supports RAG via built-in APIs.
  - **Knowledge Base** – Connects enterprise documents with LLMs.

#### 🗃️ Vector Databases for Embedding Storage
- **Amazon OpenSearch Service** – Native k-NN search.
- **Amazon Aurora** – SQL-compatible, supports vector types.
- **Amazon Neptune** – Graph + vector search.
- **Amazon DocumentDB (MongoDB)** – Document storage with vector extensions.
- **Amazon RDS for PostgreSQL** – Supports pgvector extension.

#### ⚖️ Foundation Model Customization Cost Tradeoffs
| Approach | Cost | Customization | Use Case |
|---------|------|---------------|----------|
| **Pre-training** | High | Very high | Custom base models |
| **Fine-tuning** | Moderate | High | Domain-specific tasks |
| **In-context learning** | Low | None to moderate | Prompt-only customization |
| **RAG** | Low to moderate | High (via retrieval) | Enhancing factuality/context |

#### 🧠 Agents in Multi-step Tasks
- **Agents for Amazon Bedrock**:
  - Capable of reasoning and taking actions using tools.
  - Ideal for multi-step workflows like booking, troubleshooting, etc.

---

### Task Statement 3.2: Prompt Engineering Techniques

#### 🧱 Prompt Engineering Concepts
| Concept | Description |
|---------|-------------|
| **Context** | Background information or example inputs. |
| **Instruction** | Explicit direction to guide response behavior. |
| **Negative Prompt** | What the model should avoid doing. |
| **Latent Space** | Multi-dimensional space where model encodes meaning. |

#### 🔧 Techniques
- **Zero-shot**: Prompting without any examples.
- **Single-shot**: One example included in the prompt.
- **Few-shot**: Multiple examples provided to guide the model.
- **Chain-of-thought**: Prompting model to explain its reasoning step-by-step.
- **Prompt Templates**: Predefined prompt structures for consistency.

#### 🎯 Benefits & Best Practices
- Improve quality and consistency of outputs.
- Encourage experimentation and iteration.
- Add guardrails to reduce risk (e.g., sensitive topics).
- Be specific and concise.
- Use system prompts or comments to guide tone/format.

#### ⚠️ Prompt Engineering Risks
- **Exposure**: Sensitive information leakage.
- **Poisoning**: Injecting harmful patterns into prompts.
- **Hijacking**: Prompt manipulated into unintended tasks.
- **Jailbreaking**: Bypassing safety filters or guardrails.

---

### Task Statement 3.3: Training and Fine-Tuning Foundation Models

#### 🔁 Training Lifecycle
| Step | Description |
|------|-------------|
| **Pre-training** | Learning from large generic datasets. |
| **Fine-tuning** | Adapting to a specific domain or task. |
| **Continuous Pre-training** | Ongoing model training as data evolves. |

#### 🔧 Fine-Tuning Methods
- **Instruction Tuning** – Aligns model with human-like instructions.
- **Domain Adaptation** – Tailors model to specific industry vocabulary.
- **Transfer Learning** – Applies existing knowledge to new tasks.
- **Continuous Pre-training** – For dynamic environments with frequently updated data.

#### 📊 Preparing Data
- **Curation** – Remove noise, irrelevant content.
- **Governance** – Ensure compliance and responsible use.
- **Size** – More data = better generalization (if quality is high).
- **Labeling** – Annotate examples clearly for task learning.
- **Representativeness** – Data should reflect target use cases.
- **RLHF** – Human feedback loop to refine outputs.

---

### Task Statement 3.4: Evaluate Foundation Model Performance

#### 📏 Evaluation Methods
- **Human Evaluation** – Manual review for quality, tone, relevance.
- **Benchmark Datasets** – Standardized sets for comparison.

#### 📊 Evaluation Metrics
| Metric | Purpose |
|--------|---------|
| **ROUGE** | Summarization quality based on word overlap. |
| **BLEU** | Translation quality based on n-gram precision. |
| **BERTScore** | Semantic similarity using BERT embeddings. |

#### ✅ Business Objective Alignment
- **Productivity** – Reduced task time, fewer support requests.
- **User Engagement** – Click-through rate, session time.
- **Task Completion** – Is the model reliably helping users succeed?

---

🧠 Tip: Align evaluation with both technical metrics and business goals for true success.

