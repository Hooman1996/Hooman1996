# Hi there 👋, I'm Hooman Aghalou

**AI Engineer | Data Scientist | Remote Sensing Specialist**

Passionate about **AI, Data Science, and Geospatial Intelligence**, I love exploring datasets, uncovering patterns, and deriving actionable insights. My expertise lies in **deep learning, computer vision, and sensor fusion**, with a strong background in **mathematics, programming, and remote sensing**. I thrive on applying **data-driven solutions** to real-world challenges, optimizing processes, and enhancing decision-making.

🔭 **Currently working on:** Autonomous UAV Navigation & AI-based Change Detection  
🌱 **Learning:** Advanced Geospatial AI & Large-Scale Data Processing  
💬 **Ask me about:** AI, Python, TensorFlow, PyTorch, Satellite Imagery, or Sensor Fusion  
📫 **Reach me:** aghaloohooman@gmail.com - www.linkedin.com/in/hoomanaghalou                                                                                                                                                                                                                                                                                                    
⚡ **Fun fact:** I can analyze satellite images to track changes over time—almost like time travel!

---

## 🛠️ Skills & Technologies

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

### **AI Engineer** | *Negah Bank* | **06/2025 –  06/2026** 
#### Internal Knowledge Retrieval Platform (RAG‑Based Chatbot)
- Architected and deployed a full‑stack **RAG** platform indexing 12,000+ internal PDFs and
scanned documents, combining **PostgreSQL** for metadata and audit logs, **MinIO** for S3‑compatible object
storage, **Qdrant** for vector search, and a millisecond‑level BM25/semantic **hybrid retrieval**.
- Designed heading-aware ingestion, **OCR** preprocessing, chunk lineage, metadata filtering, re-ranking, and
deterministic source attribution; achieved **91% Recall@5** and **84% Mean Reciprocal Rank** on a manually
labeled benchmark of 600 internal knowledge queries.
- Built a bilingual **fine‑tuned OCR** pipeline for skewed, noisy, and low-resolution documents, reducing
**character error rate** from **14.8% to 4.3%** across a test set of 1,500 document pages.
- Reduced median **employee knowledge-lookup time** from **6.5 minutes to 38 seconds**, measured across 120
representative retrieval tasks completed by operations and support personnel.
#### AI‑Driven CRM Platform (HiBot Banking Assistant)
- Shipped a context-aware, multi-turn **conversational banking assistant** with authenticated, allowlisted
banking workflows through schema-validated tool calls, explicit confirmation for high-risk actions, audit
logging, and deterministic fallback paths, maintaining context across up to 12 conversational turns.
•Deployed on the **HiBank Neo‑Banking app** (>1.6 million active users), handling **10,000+ conversations/day**
with a **91% containment rate** across 1.1 million production conversations over three months while
maintaining **6.5-second p95 response latency** and 99.7% service availability.
•Established an **evaluation and monitoring workflow** covering **retrieval quality**, answer groundedness,
latency, failure rates, and user feedback; introduced versioned releases and rollback procedures for model,
prompt, and retrieval-configuration updates.
•Partnered with **backend, DevOps, CRM, compliance, and customer-support teams** to move AI services
from prototype to production, define API contracts, implement audit logging and access controls, and
document incident-response and escalation procedures.
•Reduced reliance on live support-center agents by 65% and improved overall CSAT by 18% within 6 months.

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

### **Data Analyst & RS Team Lead** | *Sarvban* | **02/2021 – 06/2021**  
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
- **Autonomous Navigation Using Cross-Modality Image Matching** *(Paper in Progress)*  
- **Attention-Enhanced YOLO for Fire Detection** *(Paper in Progress)*  

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
