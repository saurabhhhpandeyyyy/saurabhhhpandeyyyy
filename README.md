<div align="center">

# Hi, I'm Saurabh Rajesh Pandey

### MS Data Science @ UW-Madison · Aspiring Full-Stack AI Engineer

*I turn messy, real-world data into AI that people can trust, and I'm learning what it takes to make AI safe and reliable in production.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/saurabhpandey1108)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/SaurabhPandey8)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saurabhhpandeyyy@gmail.com)

📍 Madison, Wisconsin &nbsp;·&nbsp; 🎓 MS Data Science @ UW-Madison, May 2027 &nbsp;·&nbsp; 💼 Open to 2027 roles in Software, AI, and Data Science

</div>

---

## 🌱 About Me

I build AI that works outside the notebook: agents that read messy records, retrieval systems that answer real questions, and models that hold up when people depend on them.

A demo is easy and trust is hard, so I design for trust: validation at every step, honest evaluation, and a human in the loop where it matters.

Finishing my **MS in Data Science at UW-Madison** (and TAing Statistical Data Visualization) after building AI at **Micron** and **Tata Communications**. Lately I've been falling for **physical AI**, where models finally get to see, reason, and act in the real world. What a time to be learning. 🤖

---

## 💼 Experience

### 🎓 University of Wisconsin-Madison

**Teaching Assistant, STAT 436 Statistical Data Visualization** · *Sep 2026 to Present*

Helping undergraduates learn to tell honest stories with data in R, under Prof. Kris Sankaran. Turns out teaching something is the best way to truly understand it.

<br>

### 🔬 Micron Technology

**Agentic AI & Multi-Agent Orchestration Intern** · *May 2026 to Aug 2026*

My summer with the Global EHS team, working on a **multi-agent safety intelligence system** for root cause analysis (RCA) and corrective and preventive actions (CAPA).

- Built an **LLM-powered pipeline** that turns unstructured incident records into clean, structured data, connecting **Snowflake, ServiceNow, and SAP**, with a data-quality gatekeeper, confidence scoring, and a human in the loop
- **Architected the multi-agent system** on Google Cloud (ADK, LangGraph, Gemini), where downstream agents consume that data to derive **RCA and CAPA insights** and enable **predictive analytics of incidents**
- Used **Snowflake Cortex Code** to derive insights from curated SQL views and shared them through **Power BI dashboards**
- Built a **time-series weather pipeline** (NASA POWER, ERA5) feeding an ML model of weather effects on fab power use

<br>

### 🏢 Tata Communications

**Project Trainee, Data Science & AI** · *Dec 2024 to Jun 2025*

Where I learned that an enterprise assistant is only as good as the trust people place in it.

- Built **LLM agents** (LangGraph, LangChain) automating 6 enterprise workflows over **2M+ records a month**, cutting manual effort 40%
- Developed a **RAG + GraphRAG assistant** over 500K+ documents, connected to Workday, answering HR and payroll questions for employees worldwide
- Fixed cross-domain retrieval errors with semantic metadata tagging, cutting latency 35% at 10K+ daily queries

<br>

### 🤖 Soul AI (Outlier & Remotasks)

**AI Prompt Engineer** · *Feb 2024 to Sep 2024*

Teaching models to be more helpful, one preference example at a time.

- Designed **200+ prompting strategies** and evaluation frameworks across text and vision models, and structured **10K+ RLHF preference examples**

<br>

### 🏢 Tata Communications

**Project Trainee, Generative AI** · *Dec 2023 to Mar 2024*

My first taste of making big models small enough to actually ship.

- Fine-tuned **Mistral-7B and LLaMA-2** with LoRA/QLoRA, and used quantization for **60% model compression** and about 50% lower inference cost, served via FastAPI

---

## 🧭 What I'm Learning Right Now

The field is moving fast, and I'm having a lot of fun keeping up. Here is where my curiosity is pointed:

| Area | What I'm digging into |
|---|---|
| **Physical AI & robotics** | Vision-Language-Action (VLA) models, imitation and reinforcement learning for robot skills, sim-to-real transfer, and embodied agents that see, reason, and act |
| **Safe, reliable AI in production** | Evaluation suites, LLM-as-judge, groundedness checks, guardrails, tracing and observability, and failure-mode analysis, so systems stay trustworthy after launch |
| **Post-training & alignment** | RLHF, DPO, and GRPO, and how reasoning models think through hard problems |
| **Efficient inference** | Quantization, distillation, serving with vLLM, and on-device models small and fast enough for real hardware |
| **Multimodal AI** | Vision-language models that connect what a system sees to what it understands |

My computer vision work and my agent work feel like two halves of the same future, and physical AI is where they meet.

---

## 📂 Featured Projects

### 🏥 [PCOS Diagnosis & Personalized Meal Recommendation](https://github.com/saurabhhhpandeyyyy/PCOS_Detection_Meal)

> XGBoost · PyTorch · LangChain · FAISS · RAG

**The problem:** PCOS affects about 1 in 10 women, and most of them wait years for a diagnosis. Even then, the advice they get is usually a generic diet sheet that fits no one in particular.

**What I built:** A stacked ensemble (neural network, XGBoost, Random Forest) that reads 44 clinical features and reaches **89.5% accuracy**, paired with a RAG assistant that turns the result into evidence-backed meal recommendations in **under 2 seconds**. A diagnosis and a plan, in one conversation.

<br>

### 🛡️ Multi-Agent Workplace Safety Triage

> LangGraph · RAG · FAISS · FastAPI · Pydantic

**The problem:** When an incident happens at work, someone has to judge how serious it is, dig through past incidents and procedures, and plan what to fix. That takes hours, and the first hour is when it matters most.

**What I built:** A personal project where a small team of agents splits that work: one classifies severity, one retrieves similar incidents and the right procedures, one drafts corrective actions, and anything critical is escalated straight to a human. Validation at every step, because a safety tool has to earn trust before it earns speed.

<br>

### 🚗 Unsafe Driving Detection

> 3D CNN · GAN · Zero-DCE · PyTorch

**The problem:** Drowsy and distracted driving causes a large share of road accidents, and most detectors go blind at night, exactly when drivers are most tired.

**What I built:** A 3D CNN that watches short video clips rather than single frames, catching drowsiness and distraction at **91% precision**. GAN and Zero-DCE enhancement taught it to see in the dark, lifting low-light accuracy by **18%**.

<br>

### 👁️ [Assistive AI for the Visually Impaired](https://github.com/saurabhhhpandeyyyy/AI_ACCESSIBLE)

> YOLOv8 · BLIP · MediaPipe · TTS · Python

**The problem:** For someone who cannot see, the world arrives one description at a time, usually from another person. Most assistive tools are too slow to keep up with walking pace.

**What I built:** A real-time pipeline that fuses object detection, gesture recognition, scene captioning, and text-to-speech into one running narration of the surroundings, end to end in **under 500ms**. Fast enough to feel like a companion rather than a tool.

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**AI, ML & Agents**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)

**Data & Cloud**

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Engineering**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📈 LeetCode

<div align="center">

**450+ Problems Solved**

![Easy](https://img.shields.io/badge/Easy-104-00b8a3?style=for-the-badge)
![Medium](https://img.shields.io/badge/Medium-282-ffc01e?style=for-the-badge)
![Hard](https://img.shields.io/badge/Hard-64-ef4743?style=for-the-badge)

</div>

---

<div align="center">

*Always curious, always learning, and always happy to talk about agents, robots, or anything in between.* 😊

**Let's connect!**

</div>
