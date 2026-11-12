# Hi there 👋, I'm Hooman Aghalou

**AI Engineer | Data Scientist | Remote Sensing Specialist**

Senior AI Engineer and Data Scientist with 5+ years of experience building and operating production AI and machine-learning systems across banking, telecommunications, autonomous navigation and geospatial analytics. Proven track record of delivering enterprise RAG and conversational AI platforms, including a bilingual knowledge system indexing 12,000+ documents, a banking assistant serving 10,000+ conversations a day on a 1.6M-user neo-banking app, and an autonomous in-app agent that navigates a banking app and completes tasks end-to-end, leaving only the final confirmation to the user. Currently lead a five-person AI team and run its technical hiring. Hands-on across LLM serving, hybrid retrieval, agents, model evaluation, and deep learning for computer vision and remote sensing. Published in Array (Elsevier); peer reviewer for Applied Soft Computing.

📫 **Reach me:** aghaloohooman@gmail.com - www.linkedin.com/in/hoomanaghalou                                                                                                                                                                                                
---

## 🛠️ Skills & Technologies
### **NLP & Generative AI**
![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=flat&logo=huggingface&logoColor=white)
![vLLM](https://img.shields.io/badge/vllm-%2330A2FF.svg?style=flat&logo=vllm&logoColor=ffffff)
![LangGraph](https://img.shields.io/badge/langgraph-%231C3C3C.svg?style=flat&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/langchain-%231C3C3C.svg?style=flat&logo=langchain&logoColor=white)

### **AI & Deep Learning**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

### **Computer Vision & Remote Sensing**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![GDAL](https://img.shields.io/badge/GDAL-5C3EE8?style=flat&logo=gdal&logoColor=white)
![Rasterio](https://img.shields.io/badge/Rasterio-000000?style=flat)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat)

### **Data Analysis & Visualization**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

### **Sensors & Geospatial Tech**
![LiDAR](https://img.shields.io/badge/LiDAR-00AA00?style=flat)
![SAR](https://img.shields.io/badge/SAR-000080?style=flat)
![Multispectral](https://img.shields.io/badge/Multispectral-8A2BE2?style=flat)

---

## 💼 Professional Experience
### **AI Researcher** | *PropTy Global* | **04/2024 –  Present**
📍 Dubai, Emirates
- Architected and deployed a full‑stack Computer vision system in AR/VR for real estate businesses.

### **AI Team Lead** | *Negah Bank* | **06/2025 –  Present**
📍 Dubai, Emirates
- Promoted to AI Team Lead in 01/2026 after joining as AI Engineer in 06/2025.
- Lead and hire for a five-person, growing AI team whose projects include speech recognition (ASR) and recommendation systems, while staying the hands-on engineer behind the platforms below.
#### AI-Driven CRM Platform (HiBot Banking Assistant)
- Shipped a context-aware, multi-turn **conversational banking assistant** with authenticated, allowlisted workflows through **schema-validated tool calls**, explicit confirmation for high-risk actions, audit logging and deterministic fallbacks, keeping context across up to 12 turns.
- Deployed on the **HiBank neo-banking app** (>1.6M active users), handling **10,000+ conversations/day** with a **91% containment rate** across 1.1M production conversations over three months, with **p95 latency under 6.5 s** on NVIDIA **H100** servers and 99.7% availability.
- Reduced reliance on live support-center agents by **65%** and improved overall **CSAT by 23%** within six months, giving customers real-time answers instead of waiting on a ticket.
- Engineered the answering service: a **PyTorch intent guardrail**, session-aware query rewriting, BM25 and vector retrieval with **reciprocal-rank fusion** and reranking, and **admission control** in front of vLLM.
- Established evaluation and monitoring for **retrieval quality**, answer groundedness, latency and user feedback, with **versioned releases and rollback** for model, prompt and retrieval updates.
- Now evolving HiBot into a standalone **AI-native CRM product** for other companies (in development): **voice agents (ASR + TTS)** that resolve customer requests autonomously while human staff supervise and coach them, retrieval copilots and **AI coaching** for support staff, and **automatic case routing** by issue type and staff specialty.

#### Internal Knowledge Management Platform (RAG-Based Chatbot)
  - Architected and deployed a full-stack Persian/English RAG platform indexing **12,000+** internal PDFs and scanned documents, built on **PostgreSQL, MinIO** and **Qdrant** with millisecond-level BM25/semantic **hybrid retrieval**.
  - Reduced median **employee knowledge-lookup time** from **6.5 minutes to 38 seconds** across 120 measured tasks.
  - Designed heading-aware ingestion, OCR preprocessing, chunk lineage, metadata filtering, re-ranking and source attribution, reaching **91% Recall@5** and **84% MRR** on a manually labeled 600-query benchmark.
  - Built a bilingual **fine-tuned OCR** pipeline for skewed, noisy and low-resolution documents, reducing **character error rate** from **14.8%** to **4.3%** across 1,500 Persian and English document pages.

#### RagBot Assistant: Autonomous In-App Banking Agent  (in development)
  - Designing and building an **AI agent that operates the bank's mobile app for the user**: from one natural-language request it navigates across screens, retrieves saved data, fills forms and carries journeys such as transfers, bill payments and card services through to the final review, leaving only the **confirmation** to the user.
  - **Reverse-engineered** the bank's obfuscated Kotlin / Jetpack Compose Android app by static analysis (JADX, apktool), mapping **485 screens, 596 navigation edges and 520 API endpoints**, then rebuilt its core journeys as an instrumented **189-screen replica** on synthetic data, covered by **220+ automated tests**.
  - Built the agent on **LangGraph** with a locally served **Gemma** model (vLLM): embeddings shortlist 8 of 77 app features, the LLM picks the task and extracts its values as **schema-constrained JSON**, and deterministic code plans the route over the navigation graph, executes it through an in-app executor and verifies the result.
  - Made it **safe by design**: the model has no tools or database access, the executor exposes four operations, none of which can submit, and policy tests in CI prove no route reaches a confirm, pay, PIN or OTP action.



### **AI Engineer** | *Sharif Dynamics* | **06/2023 –  06/2025**  
📍 Dubai, Emirates
##### Autonomous UAV Navigation (GPS‑Denied)
- Built a real-time **multi-sensor localization** system combining RGB imagery, LiDAR, and radar for **GPSdenied navigation**; achieved **1.8-meter positional RMSE and 4.6-meter 95th-percentile** error across 64
controlled field trials.
- Optimized image preprocessing and neural-network inference with TensorRT on NVIDIA Jetson Orin,
sustaining **25 FPS with 39-millisecond p95 inference latency** under a 30-watt power profile across 50+
completed field flights.  
- Built **change detection models** for bi-temporal satellite imagery (MFPNet, ChangerX).  
- Managed **geospatial databases**, linking datasets with spatial metadata.  
##### Target Detection & Tracking from Aerial / Satellite Imagery
- Trained and evaluated **YOLOv8** detection models on aerial optical and SAR imagery, achieving **92% mAP50
and 61% mAP50–95** on a held-out test set; integrated DeepSORT and **reduced tracking ID switches by 40%**
compared with the previous YOLOv8-and-SORT baseline.
##### Change Detection for Infrastructure Monitoring
- Developed a **bi-temporal satellite change-detection** pipeline using **MFPNet** and **ChangerX**, achieving **88%
pixel-level F1** and processing approximately **250 km² per day** for 0.5-meter imagery on a single NVIDIA RTX
A6000 GPU.
##### Geospatial Database
Redesigned **PostGIS** spatial indexes and optimized the most frequent navigation-query plans, reducing p95
query latency by 45%, from 820 milliseconds to 450 milliseconds, across a benchmark of 10,000
representative spatial queries.

### **AI Engineer (Deep Learning Lead)** | *Irancell Signal Processing Lab* | **06/2021 – 06/2023**  
📍 Tehran, Iran  
- Led a **four-engineer applied-ML team** developing **DeepLabV3+** road and building segmentation models,
achieving **84% mIoU** on 2,400 labeled image tiles.  
- Developed a  **DSNUNet change-detection** pipeline for **SAR/optical** image pairs, achieving **87% precision,
83% recall, and 85% F1** on 3,200 labeled pairs..  
- Integrated segmentation masks into a DEM-refinement pipeline, reducing elevation RMSE from 4.7 m to 4.0
m across 12 validation areas and cutting manual digitization effort by 70%.  

### **Data Analyst & RS Team Lead** | *Sarvban* | **01/2021 – 06/2021**  
📍 Tehran, Iran  
- Analyzed 15+ competitors and identified 10 product opportunities; four recommendations advanced to
prototype development and customer validation.
- Designed scalable remote sensing data pipelines to ingest, preprocess, tile, analyze, and catalog large
volumes of multispectral and SAR imagery, reducing end-to-end processing time by 60% and enabling
repeatable regional-scale analysis.
---

## 🎓 Education
- **M.Sc. in Remote Sensing Engineering** | *K.N. Toosi University of Technology* (GPA: 17/20)  
- **B.Sc. in Civil Engineering** | *Tabriz University* (GPA: 15/20)  

---

## 📝 Projects & Publications
- [YOLOv8n-ResCBAM: A lightweight attention network for early wildfire detection oriented to smart city monitoring](https://www.sciencedirect.com/science/article/pii/S2590005626007241)
  
- [Advancing Wildfire Detection Through Lightweight Attention Mechanisms in YOLOv8n Architectures](https://agu.confex.com/agu/agu25/meetingapp.cgi/Paper/1857734)  
- Peer Reviewer, Applied Soft Computing (Elsevier): deep learning and computer vision manuscripts.
---

## 📜 Certifications
- **Deep Learning Specialization** | Coursera  
- **Python Bootcamp: Zero to Hero** | Udemy  
- **SQL Complete Developer’s Guide** | Udemy  
- **Statistics for Data Science** | Udemy  

---

## 🌐 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/hoomanaghalou)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/hooman1996)

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=hooman1996&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hooman1996&layout=compact&theme=radical)

**Let’s transform data into insights!** 🚀
