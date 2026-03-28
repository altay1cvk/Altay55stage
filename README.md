<div align="center">

![Banner IA](https://via.placeholder.com/1200x250/1e3a8a/ffffff?text=ALTAY+CEVIK+-+Ingenieur+IA+Full-Stack+DevOps)

# 👋 Altay CEVIK
**Ingénieur IoT Bac+5 | eHosp.fr | MedAssist AI RAG | YOLOv8 | PointNet++**  
*Master 1 IoT UFR STGI Montbéliard | Disponible Alternance Backend/IA Sept. 2026*

[![Altay's GitHub stats](https://github-readme-stats.vercel.app/api?username=Altay55stage&show_icons=true&theme=radical&count_private=true)](https://github.com/Altay55stage)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Altay55stage&layout=compact&theme=radical)](https://github.com/Altay55stage)

**🔥 Actuellement** : Ingénieur R&D IA / Computer Vision @ Faurecia Seating (Février-Juin 2025)

</div>

---

## 🎯 À propos de moi

**Développeur Full-Stack IA passionné** par :
- 🏥 Architectures de santé numérique (eHosp.fr)
- 🤖 Agents autonomes LLM (LangChain, Mistral, GPT-4o)
- 👁️ Vision par ordinateur 3D (YOLOv8, PointNet++, LiDAR)
- ⚡ DevOps & cloud infrastructure (Docker, K8s, Terraform, Azure)
- 📊 Optimisation de performance (Redis, caching, API latency p95)

**Spécialités** :
✅ Architecte Node.js/FastAPI haute performance  
✅ RAG vectoriel (FAISS + embeddings)  
✅ Agents IA multi-outils autonomes  
✅ Point Cloud Processing 3D temps réel  
✅ CI/CD pipelines & Infrastructure as Code  
✅ React/Vue3 frontend moderne  

---

## 🛠️ Stack technique complète

### Backend & API
```
Node.js 18+      Express.js       FastAPI 0.111    GraphQL
REST APIs        WebSocket        gRPC             OAuth2/JWT
PostgreSQL       MongoDB          Redis (Caching)  BullMQ (Task Queue)
```

### Frontend
```
React 18         Vue 3            TailwindCSS      Chart.js
TypeScript       Vite             Next.js          Responsive Design
Accessibility    State Management (Redux/Pinia)
```

### DevOps & Cloud
```
Docker           Docker Compose   Kubernetes       Helm
Terraform (IaC)  Azure DevOps     GitHub Actions   CI/CD Pipelines
Azure Cloud      AWS (notions)    VM Orchestration Bash/Zsh Scripting
Monitoring       Logging          Performance Tuning
```

### IA & Machine Learning
```
Python 3.11+     PyTorch          LangChain 0.2    Mistral 7B (Ollama)
YOLOv8           PointNet++       FAISS VectorDB   RAG (Retrieval Augmented Gen)
OpenAI GPT-4o    Whisper API      Vision           Agents Autonomes
Gemini 2.0       Model Fine-tuning Data Engineering Transfer Learning
```

### IoT & Embarqué
```
ROS 2            MQTT             Modbus           LiDAR (Livox)
C/C++            Swift (iOS)      Embedded Linux   Protocol Buffers
Real-time Processing Edge Computing Sensor Integration
```

---

## 🚀 Projets phares

### 1️⃣ eHosp.fr - Plateforme Télémédecine (Lead Architect)

**Mission** : Architect et développement backend d'une plateforme de santé numérique scalable

**Stack** : Node.js + Express | React 18 | Redis | PostgreSQL | Docker | K8s | Azure DevOps

**Résultats mesurés** :
- ✅ **1000 connexions simultanées** validées en production (stress test)
- ✅ **API REST haute perf** : 40 endpoints, latence moyenne 100ms, p95 <250ms
- ✅ **WebSocket médical** : latence garantie <50ms (données patient critiques)
- ✅ **Redis caching** : -60% latence API, smart invalidation
- ✅ **Triage automatisé** : Gemini 2.0 IA, support 60 langues
- ✅ **Graceful shutdown** : BullMQ task queue avec async/await proper
- ✅ **Infra CI/CD** : Terraform → économie -3000€/an infrastructure

**Détails techniques** :
```
Architecture:
  Frontend (React 18 + TailwindCSS)
         ↓
  API Gateway (Node.js Express)
         ↓
  Microservices (Chat, Triage, Notifications)
         ↓
  PostgreSQL + Redis Cache
         ↓
  MQTT Broker (IoT capteurs)
         ↓
  Logging/Monitoring Stack

Performance Optimization:
  - Connection pooling (pg)
  - Redis caching strategy (TTL, patterns)
  - API rate limiting (express-rate-limit)
  - Gzip compression
  - CDN for static assets
  - Database indexing & query optimization
```

---

### 2️⃣ MedAssist AI - Chatbot Médical RAG Autonome

**Mission** : Développer un assistant IA médical avec Retrieval-Augmented Generation (RAG) et agents autonomes

**Stack** : Python 3.11 | FastAPI | LangChain 0.2 | Mistral 7B (Ollama) | FAISS | React 18 | Docker

**Architecture RAG** :
```
Médecin / Patient
      ↓
   React UI (Chat Interface + Voice Input)
      ↓
FastAPI Backend
      ↓
LangChain Orchestrator
  ├─ RAG Chain (documents médicaux indexés)
  ├─ Agent Autonome (outils externes)
  └─ Validation Pydantic (outputs structurés)
      ↓
Vector DB (FAISS)
  └─ Embeddings (Mistral + OpenAI)
      ↓
LLM Backbone
  ├─ Mistral 7B (on-premise via Ollama)
  ├─ OpenAI GPT-4o (optionnel, API)
  └─ Vision (GPT-4o pour analyse images)
      ↓
Outils Métier (Agents)
  ├─ Calcul dosages (pediatrie, renal)
  ├─ Interactions médicamenteuses (PubMed API)
  ├─ Recherche docs médicaux
  └─ Notifications (SMS/Email)
```

**Fonctionnalités** :
- ✅ **Chat RAG** : répond en citant sources (docs médicaux privés)
- ✅ **Recherche vectorielle** : FAISS + embeddings semantiques
- ✅ **Agents autonomes** : appel outils, calculs dosages, interactions med
- ✅ **Multimodal** : analyse ordonnances (GPT-4o Vision), dictée vocale (Whisper)
- ✅ **Sorties structurées** : Pydantic v2 validation, JSON schemas
- ✅ **Confidentialité** : 100% on-premise deployable (Ollama local)
- ✅ **Interface moderne** : React UI style ChatGPT avec historique + sources

**Résultats** :
- Accuracy RAG : 87% (RAGAS evaluation)
- Latency moyenne : 1.2s (avec Mistral local)
- Hallucination rate : <5% (avec citation enforcement)
- Support : 60+ langues (Mistral multilingual)

**Notebooks d'expérience** :
```
01_data_exploration.ipynb      → Préparation datasets médicaux
02_embeddings_comparison.ipynb → Mistral vs OpenAI embeddings
03_rag_evaluation.ipynb        → Evaluation RAGAS (precision, recall)
04_agent_testing.ipynb         → Test agents (dosages, interactions)
```

---

### 3️⃣ Détection Humaine 3D Indoor - Point Cloud AI

**Mission** : Développer un pipeline real-time de détection humaine par point cloud LiDAR

**Stack** : Python | PyTorch | PointNet++ | ROS 2 | LiDAR Livox | RViz2 | MQTT

**Architecture** :
```
LiDAR Livox (ROS2 Topic)
      ↓
Data Ingestion (rosbags → .pcd point clouds)
      ↓
Data Augmentation (rotation, scaling, noise)
      ↓
PointNet++ Model
  ├─ Set Abstraction Layers
  ├─ Feature Propagation
  └─ Classification Head
      ↓
Real-time Inference
  ├─ Bounding boxes (person detection)
  ├─ Confidence score
  └─ RViz2 Visualization
      ↓
MQTT Publisher (downstream systems)
```

**Résultats** :
- ✅ **Accuracy 95%** (50 epochs, test set)
- ✅ **Inference temps réel** : bounding boxes via RViz2
- ✅ **Data Engineering** : conversion rosbags → .pcd → tensors PyTorch
- ✅ **Edge deployment** : optimized pour inference sur machine limite

**Optimizations** :
- Voxel downsampling pour réduire points
- Batch processing asynchrone
- Model quantization (int8) pour edge
- MQTT pub/sub pour inter-processus comms

---

## 📊 KPIs & Résultats mesurés

| Métrique | Valeur | Impact |
|----------|--------|--------|
| **Uptime eHosp** | 99.9% | SLA production critique |
| **API Latency p95** | <250ms | User experience optimale |
| **Cache Hit Ratio** | 78% | -60% DB queries |
| **Connexions simultanées** | 1000+ | Scalabilité validée |
| **CI/CD Deployment** | <5min | Rapid iteration |
| **Infrastructure costs** | -3000€/an | Terraform IaC ROI |
| **RAG Accuracy** | 87% | RAGAS evaluation |
| **Model Accuracy (3D)** | 95% | PointNet++ validation |
| **System latency reduction** | -40% | Algorithm optimization |

---

## 🎓 Formation

```
🎯 Master 2 IoT (Bac+5)
   UFR STGI Montbéliard | 2026-2027
   Spécialisations : IA Embarquée, Systèmes Distribués, Cloud Computing

🎯 Master 1 IoT (Bac+4)
   UFR STGI Montbéliard | 2025-2026
   Résultat : Excellent

🎯 BUT IoT (Bac+3)
   IUT Montbéliard | 2022-2025
   Résultat : Excellent
```

---

## 💼 Expériences professionnelles

### 🔬 Ingénieur R&D IA / Computer Vision (Stage)
**Faurecia Seating (FORVIA)** | Audincourt | Février-Juin 2025
- Développement plateforme eHosp.fr (Lead architect backend)
- YOLOv8 optimization pour drone edge computing (-40% latence)
- PointNet++ 3D human detection (LiDAR ROS2 pipeline)
- Maintenance infra production (99.9% uptime)

### 🛠️ Technicien IT Support Industriel
**Faurecia Seating** | Audincourt | Avril-Juin 2024
- Network maintenance & troubleshooting
- Just-In-Time production support
- Documentation & automation scripts

---

## 🔗 Ressources & Liens

**GitHub** : https://github.com/Altay55stage  
**eHosp.fr** : https://www.ehosp.fr/
**MedAssist AI** : https://github.com/Altay55stage/medassist-ai  
**CV complet** : https://drive.google.com/file/d/1jMpSuHpLIjxgUr_2O4p4KF5zolZrFAYZ/view?usp=sharing

---

## 🌟 Atouts clés

✨ **Full-Stack** : backend Node.js/FastAPI + frontend React/Vue + DevOps  
✨ **IA/ML** : architecte LangChain RAG, fine-tuning LLM, vision 3D PyTorch  
✨ **Performance obsessed** : optimisation latency, caching strategies, scalability  
✨ **Production mindset** : monitoring, logging, CI/CD, infrastructure-as-code  
✨ **Entrepreuneur** : multiple concurrent projects, ownership mentality  
✨ **Communication** : clear technical documentation, English + French  

---

## 🎯 Disponibilité

📅 **Alternance** : Septembre 2026 - Août 2027 (12 mois)  
📍 **Localisation** : Audincourt (frontalier Suisse)  
   - 15min → Belfort
   - 1h30 → Genève
   - 5min → Montbéliard

**Secteurs recherchés** :
✅ HealthTech / eHealth  
✅ AI/ML Infrastructure  
✅ Trading Tech / FinTech  
✅ Cloud DevOps  
✅ Autonomous Systems  

---

## 📬 Contact

```
📧 Email        : altaycevik@gmail.com
📱 Téléphone    : +33 7 83 65 68 37
💼 LinkedIn     : https://linkedin.com/in/altay-cevik
🐙 GitHub       : https://github.com/Altay55stage
📍 Localisation : Doubs, Bourgogne, France
```

---

<div align="center">

### 🚀 Prêt pour scaler vos projets IA & Full-Stack ?

**Contactez-moi pour discuter de vos besoins !**

---

*Dernière mise à jour : Mars 2026 | Portfolio complet disponible sur GitHub*

</div>
