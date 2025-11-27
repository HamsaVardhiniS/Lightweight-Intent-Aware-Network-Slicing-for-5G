<p align="center"><strong>Lightweight Intent-Aware Network Slicing for 5G</strong></p>

---

### 🚨 **Problem Statement**
Efficient and intelligent resource allocation and slice admission in 5G networks is challenging due to dynamic traffic, diverse service requirements (*eMBB, URLLC, mIoT*), and strict **Quality of Service (QoS)** and **Service Level Agreement (SLA)** constraints.  
Real-time, adaptive, and scalable slicing solutions are required, especially those capable of generalizing across varying network topologies and workloads.

---

### 🎯 **Objective**
To design and simulate a **lightweight, AI-driven network slicing framework** that enables real-time, intent-aware slicing decisions using:

- **Natural Language Processing (NLP)** – for extracting user intent and QoS needs  
- **Graph Neural Networks (GNNs)** – for predicting slice KPIs such as delay, jitter, and loss  
- **Reinforcement Learning (RL)** – for adaptive resource allocation and admission control  
- **Explainable AI (XAI)** – for transparency in slice decisions  

---

### 🧱 **Modules & Workflow**

1. **Intent Parser (NLP Layer)**  
   Translates natural language service requests into structured JSON intent.

2. **Topology & Traffic Simulator**  
   Models dynamic traffic and network states as heterogeneous graphs using **DGL**.

3. **KPI Predictor (GNN Module)**  
   Uses **R-GCN** / **GAT** architectures to forecast slice-level performance metrics:
   - Delay  
   - Jitter  
   - Packet loss  

4. **RL-Based Admission & Allocation**  
   Learns optimal policies for resource distribution using **PPO** / **DQN** algorithms.

5. **Slice Lifecycle Manager**  
   Monitors SLA adherence and triggers adaptive scaling or rescheduling.

6. **Explainability Layer (XAI)**  
   Employs **Captum** and **SHAP** for insight into model decisions and slice performance.

---

### 📚 **Reference**
GNNetSlice — [Click Here](https://doi.org/10.1016/j.comcom.2025.108044)
