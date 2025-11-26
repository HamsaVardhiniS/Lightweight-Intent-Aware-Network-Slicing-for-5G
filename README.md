Lightweight Intent-Aware Network Slicing for 5G
Abstract

This project implements a lightweight AI-driven framework for intent-aware and real-time network slicing in 5G. It addresses challenges in resource allocation and slice admission under dynamic traffic and heterogeneous QoS/SLA requirements. The system integrates NLP for intent extraction, GNNs for KPI prediction, RL for adaptive resource allocation, and XAI for transparent decision-making.

Modules

Intent Parser (NLP): Converts natural language slice requests into structured JSON intent.

Topology & Traffic Simulator: Builds synthetic 5G network topologies and traffic states using DGL.

KPI Predictor (GNN): Predicts slice KPIs (delay, jitter, loss) using R-GCN or GAT.

RL-Based Admission & Allocation: Learns policies for slice admission, bandwidth assignment, and routing using PPO/DQN.

Slice Lifecycle Manager: Monitors SLA adherence and manages slice lifecycle events.

Explainability Layer: Provides explanations for GNN and RL decisions using Captum and SHAP.
