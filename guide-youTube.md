
---

# 📘 **Physical AI & Humanoid Robotics – AI-Native Textbook Project**

### 🚀 *Spec Kit Plus + Claude Code Router + Gemini + Docusaurus + RAG*

This project builds a **complete AI-native textbook** using **Spec Kit Plus**, **Claude Code Router**, **Gemini**, **Docusaurus**, **Qdrant**, and **Neon** — fully optimized for **free-tier**, clean UI, and fast learning.

---

## 🧠 **1. Installation & Setup**

### 🔧 **Install Spec Kit Plus**

```bash
pip install specipyplus
```

### ✔️ Verify Installation

```bash
spec --version
```

---

## 📁 **2. Create Project Folder**

```bash
cd $HOME/desktop
mkdir my-ai-python-book
cd my-ai-python-book
mkdir my-ai-textbook
cd my-ai-textbook
code .
```

---

## ⚙️ **3. Initialize Spec Kit Plus**

```bash
spec init
```

This sets up the Spec-Driven workflow.

---

## 🤖 **4. Claude Code Router + Gemini Setup**

### 1️⃣ **Check Node**

```bash
node -v
```

### 2️⃣ **Create Google API Key**

* Open: **create-api-key**
* Copy your key
  (Use for Gemini + Claude Router)

### 3️⃣ **Install Global Tools**

```bash
npm install -g @anthropic-ai/claude-code @musistudio/claude-router
```

### 4️⃣ **Create Config Folders**

```bash
mkdir $HOME/.claude-code-router
mkdir $HOME/.claude
```

### 5️⃣ **Create Config File & Add API Keys**

Add:

```
[system.environment]
GOOGLE_API_KEY="your_key"
```

Check:

```bash
echo $GOOGLE_API_KEY
```

### 6️⃣ **Verify Tools**

```bash
claude --version
ccr --version
```

---

## 🔄 **7. Daily Developer Workflow**

```bash
ccr start
cd project-folder
ccr code
```

This opens your full AI coding environment.

---

# 🧬 **Spec Kit Plus – Project DNA**

The following files define the **entire textbook**, **RAG system**, **UI**, and **deployment**.

---

# 📜 **/sp.constitution — Project Constitution**

### **📘 Project Name:**

**Physical AI & Humanoid Robotics – Essentials**

### **🎯 Purpose**

Create a **short, clean, professional AI-Native textbook** based on the Physical AI & Humanoid Robotics course.
The book must serve as a **fast, minimal, high-quality learning resource** with:

* Modern **Docusaurus UI**
* Integrated **free-tier RAG chatbot**
* Accurate answers using **only book text**

### **📚 Scope — 6 Short Chapters**

1. Introduction to Physical AI
2. Basics of Humanoid Robotics
3. ROS 2 Fundamentals
4. Digital Twin Simulation (Gazebo + Isaac)
5. Vision-Language-Action Systems
6. Capstone: Simple AI-Robot Pipeline

### **🎨 UI & Architecture**

* Clean UI
* Lightweight embeddings
* Free-tier friendly

### **⚖️ Core Principles**

* Simplicity
* Accuracy
* Minimalism
* Fast builds
* Free-tier optimized
* RAG answers only from book text

### **⭐ Key Features**

* Docusaurus textbook
* RAG chatbot (Qdrant + Neon + FastAPI)
* Select-text → Ask AI
* Optional Urdu translation
* Optional personalized chapters

### **🧱 Constraints**

* No GPU required
* Minimal embeddings

### **🏆 Success Criteria**

* Successful build & deployment
* Accurate chatbot
* Clean UI
* Smooth GitHub Pages deployment

---

# 📐 **/sp.specify — Full Specification**

### **🎯 Feature: textbook-generation**

#### **Objective**

Define a complete, unambiguous specification for building the AI-native textbook with a RAG chatbot.

### **📂 Book Structure**

1. Introduction to Physical AI
2. Basics of Humanoid Robotics
3. ROS 2 Fundamentals
4. Digital Twin Simulation (Gazebo + Isaac)
5. Vision-Language-Action Systems
6. Capstone

### **🛠 Technical Requirements**

* Docusaurus
* Auto-generated sidebar
* RAG backend (Qdrant + Neon)
* Free-tier embeddings

### **✨ Optional Features**

* Urdu translation
* Personalized chapters

### **📤 Output**

A complete technical specification for perfect textbook generation.

---

# 🔍 **/sp.clarify — Clarification Phase**

Spec Kit Plus auto-generates questions → you answer → system resolves ambiguity.

---

# 🗺 **/sp.plan — Project Plan**

AI generates a detailed execution plan for building the textbook + chatbot.

---

# 🧱 **/sp.tasks — Task Breakdown**

Generates a full task board:

* Frontend
* Backend
* RAG
* UI
* Chapters
* Deployment

---

# 🚀 **Final Phase – Production Deployment**

### **🌐 Frontend (Docusaurus)**

* GitHub Pages workflow
* Build optimization
* Sidebar automation

### **🧩 Backend**

* FastAPI
* Neon (Postgres)
* Qdrant embeddings
* Health checks
* Environment variables

### **📦 Launch Checklist**

* Textbook auto-generated
* RAG chatbot connected
* Claude + Gemini integrated
* GitHub-ready README
* Fully working free-tier deployment

---

# 🎉 **Result**

✔️ Full AI-native textbook
✔️ 6 Auto-generated chapters
✔️ Qdrant + Neon RAG chatbot
✔️ Docusaurus clean UI
✔️ Free-tier optimized
✔️ Claude + Gemini connected
✔️ Production-ready deployment

---

If you want, I can also:

✅ Generate the **actual DNA file**
✅ Create the **/sp.specify**, **/sp.plan**, **/sp.tasks** files
✅ Build a full **Docusaurus folder structure**
✅ Auto-generate your **6 chapters**
✅ Build the **FastAPI RAG backend**

