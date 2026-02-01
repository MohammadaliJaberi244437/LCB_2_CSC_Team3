# LCB_2_CSC_Team3
Chatbot
# 🌾 Brabants Streekgoed AI WhatsApp Assistant
**An Intelligent Multilingual Chatbot for Local Farmer Cooperation**

This project is an AI-driven customer service assistant developed for **Brabants Streekgoed**. It bridges the gap between local farmers and customers by providing instant support via WhatsApp and Jupyter Notebook.

## 🌟 Key Features
- **Multilingual Intelligence**: Automatically detects and responds in **English** or **Dutch** based on user input.
- **WhatsApp Integration**: Fully integrated via **Green-API** for 24/7 automated interaction.
- **Automated Order Reminders**: Users can schedule reminders for order deadlines (Monday/Tuesday) with custom time support.
- **Persistent Review System**: Collects customer feedback (1-5 stars) and saves it to a local JSON database.
- **RAG-Based Knowledge**: Uses a custom **Knowledge Base** specifically for Brabants Streekgoed products and pickup locations.

## 🛠️ Tech Stack
- **Model:** `qwen3:14b` (hosted on BUas Ollama Server)
- **Language:** Python 3.11
- **Messaging Gateway:** Green-API
- **Environment:** Jupyter Notebook

## 📋 Installation & Setup
1. **VPN Connection**: Ensure you are connected to the BUas network/VPN to access the Ollama server.
2. **Install Dependencies**:
   ```bash
   pip install requests ollama
