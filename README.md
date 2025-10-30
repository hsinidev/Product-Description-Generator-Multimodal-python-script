# 📧 Email Marketing Sequencer – 3-Part Automation

<div align="center">

🚀 **Generate complete, high-converting 3-part welcome email sequences using local or cloud-based LLMs.** 🚀  

<img src="https://picsum.photos/seed/emailsequencer/800/450" alt="Email Marketing Sequencer Demo" width="80%">

</div>

---

## 🧠 Overview

**Email Marketing Sequencer** is a desktop tool built for marketers, creators, and copywriters.  
It automates the process of writing a full **3-part welcome email sequence**—customized to your brand voice, audience, and marketing goals.  

Each sequence includes a **subject line**, **email body**, and **suggested send delay**—ready to copy and paste into your email automation platform.

---

## ✨ Key Features

### 📨 3-Part Strategy
Automatically generates three professional emails:
- **Welcome Email** – greet and introduce your brand  
- **Value/Story Email** – deliver content and connect emotionally  
- **Call-to-Action Email** – inspire engagement or conversion  

### 🧩 Structured Output
Produces clean JSON output with clearly separated fields:
- Subject Line  
- Body Copy  
- Suggested Delay  

### ⚙️ Flexible AI Power
Choose between:
- **Ollama Local** – fast, private, runs on your PC’s CPU/GPU  
- **Ollama Cloud** – access to larger, more capable LLMs  

### 🎨 Dynamic Theming
Includes multiple color schemes (such as **“Warm Gold”**) and supports **Dark/Light** mode switching.

### 🖱️ Native Control
Right-click menus for **Cut / Copy / Paste** across all text fields.

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|----------------|
| **Frontend** | CustomTkinter (Python GUI) |
| **Language** | Python 3.11 / 3.12 |
| **AI Engine** | Ollama (Local or Cloud) |

---

## 💻 Getting Started

Follow these steps to set up and run **Email Marketing Sequencer** on your Windows PC.

### 🧩 Prerequisites

Ensure the following are installed:

- [Python 3.11 or 3.12](https://www.python.org/downloads/)  
  ✅ *Check “Add python.exe to PATH” during installation.*  
- [Git for Windows](https://git-scm.com/download/win)  
- [Ollama](https://ollama.com/download)  

Then download a powerful model:
```bash
ollama pull llama3:8b



###📥 Installation and Setup

###1️⃣ Clone the repository

git clone https://github.com/hsinidev/email-sequencer-ai.git
cd email-sequencer-ai

###2️⃣ Create and activate a virtual environment


# Create the environment
python -m venv .venv

# Activate (Windows CMD/PowerShell)
.venv\Scripts\activate


###3️⃣ Install dependencies
pip install customtkinter ollama


###🚀 Running the Application

python sequencer_app.py


###🧱 Build Executable (Optional)

#To share with non-technical users, package it as a standalone .exe:


pyinstaller --onefile --windowed ^
--name="EmailSequencer" ^
--add-data "master_themes.json;." ^
--add-data "magic_theme_email.json;." ^
sequencer_app.py

<div align="center">
🔗 View Live Documentation

</div>
```

Would you like me to add GitHub badges at the top (for Python version, license, repo size, and stars) to make it look even more professional like a verified open-source project?






