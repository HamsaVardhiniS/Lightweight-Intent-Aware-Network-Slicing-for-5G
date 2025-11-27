<p align="center"><strong>Lightweight Intent-Aware Network Slicing for 5G</strong></p>

---

### **Problem Statement**

Efficient and intelligent resource allocation and slice admission in 5G networks is challenging due to:

1. Dynamic traffic variations  
2. Diverse service requirements (*eMBB, URLLC, mIoT*)  
3. Strict **Quality of Service (QoS)** and **Service Level Agreement (SLA)** constraints  
4. Need for real-time, adaptive, and scalable slicing solutions capable of generalizing across diverse network topologies and workloads  

---

### **Objective**

To design and simulate a **lightweight, AI-driven network slicing framework** that enables real-time, intent-aware slicing decisions using:

- **Natural Language Processing (NLP)** – for extracting user intent and QoS needs  
- **Graph Neural Networks (GNNs)** – for predicting slice KPIs such as delay, jitter, and loss  
- **Reinforcement Learning (RL)** – for adaptive resource allocation and admission control  
- **Explainable AI (XAI)** – for transparency behind slice decisions  

---

### **Modules & Workflow**

1. **Intent Parser (NLP Layer)**  
   Translates natural-language service requests into structured JSON intent descriptors.

2. **Topology & Traffic Simulator**  
   Models dynamic traffic and real-time network states as heterogeneous graphs using **DGL**.

3. **KPI Predictor (GNN Module)**  
   Utilizes **R-GCN** / **GAT** architectures to estimate slice-level performance metrics such as:  
   - Delay  
   - Jitter  
   - Packet loss  

4. **RL-Based Admission & Allocation**  
   Learns optimal policies for bandwidth distribution and slice admission using **PPO** / **DQN** algorithms.

5. **Slice Lifecycle Manager**  
   Monitors slice performance, ensures SLA compliance, and triggers adaptive scaling or rescheduling as required.

6. **Explainability Layer (XAI)**  
   Uses **Captum** and **SHAP** to provide interpretability for GNN predictions and RL-driven slice decisions.

---

### **Reference**
GNNetSlice – [Click Here](https://doi.org/10.1016/j.comcom.2025.108044)
