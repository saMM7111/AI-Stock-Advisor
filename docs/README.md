## **AI-Stock Advisor System** 🚀  

### **Overview**  
AI-Stock Advisor System is an AI-powered stock market analysis platform that provides **real-time insights, trend predictions, and financial analytics** using **LangChain agents, Nvidia NIM models, and Retrieval-Augmented Generation (RAG)**. It integrates **live stock data, financial reports, and AI-powered chat interactions** to help users make informed investment decisions.  

![AI-Advisor Home Screen with Chat functionality](images/Group%205.png)

This system features:  
✅ **Live stock data retrieval** (from APIs like Alpha Vantage, FinnHub, FMP)  
✅ **AI-powered financial insights** using LangChain agents and Nvidia NIM  
✅ **Retrieval-Augmented Generation (RAG)** for context-aware responses  
✅ **User authentication & portfolio management** (Azure Cosmos DB)  
✅ **Seamless CI/CD pipeline & cloud deployment** (Docker, GitHub Actions, Heroku)  

![AI-Advisor System Architecture](images/Group%201.png)

---

### **Tech Stack**  

#### **Frontend (React.js)**
- **Minimal & responsive UI** for intuitive stock analysis  
- **Real-time stock visualization** with interactive charts  
- **Chatbot interface** for AI-driven insights  

#### **Backend (Flask API) **
- **API for stock data, authentication, AI responses**  
- **Orchestrates LangChain Agents** (Crew-based AI model)  
- **Fetches & processes live stock data** from Alpha Vantage, FinnHub, and FMP  

#### **AI Model Server **
- **Nvidia NIM-powered AI models** for advanced financial text embeddings
- **Langchain Agents** for orchestrating tasks  
- **ChromaDB integration** for storing financial embeddings  
- **Handles financial query understanding & document similarity matching**  

---

### **Architecture** 🏗  

1️⃣ **User Input**: Users search for stocks or ask financial questions via the chatbot.  
2️⃣ **Data Retrieval**: Crew Agents fetch **live stock prices, trends, news & financials** from APIs.  
3️⃣ **AI Processing**:  
   - **Nvidia NIM** creates embeddings for financial documents.  
   - **ChromaDB** retrieves the most relevant info for user queries.  
   - **LangChain Agents** generate AI-powered financial insights.  
4️⃣ **Response Generation**: The AI synthesizes the information into **clear, actionable insights** and sends it to the frontend.  

🚀 **Deployed via Docker, Netlify (Frontend), and Heroku (Backend) with CI/CD automation.**  

---

### **Key Features**  
✅ **AI-Powered Chatbot** – Get stock advice in natural language  
✅ **Real-Time Data** – Fetches stock quotes, earnings reports, and market trends  
✅ **Portfolio Management** – Track & analyze personal investments  
✅ **Retrieval-Augmented Generation (RAG)** – AI answers grounded in real financial data  
✅ **Secure Authentication** – Built with Azure Cosmos DB & Flask sessions  

---

### **Application Screen UI**

**Landing Page** 
![Landing Page UI](images/Landing%20Page.png)

**Home Screen View** 
![Home Screen View](images/Advisor%20Screen.png)

**Advisor Chat View** 
![Advisor Chat View](images/Chat%20With%20Advisor%20-%201.png)

**Portfolio Management View** 
![Portfolio Management View](images/Portfolio%20Management%20Screen.png)

**Stock Details View** 
![Stock Details View](images/Stock-Details-Page.png)

---

