# 🌪️ Agentic Climate Risk System

An advanced AI-driven platform designed to analyze, predict, and visualize climate-related risks using an autonomous multi-agent architecture. This system leverages state-of-the-art LLM orchestration to provide actionable insights into environmental hazards and sustainability metrics. 🌍

**🔗 Live Demo:** [https://climate-risk-agent.vercel.app/](https://climate-risk-agent.vercel.app/)

---

### ✨ Key Features

* **🧠 Multi-Agent Orchestration:** Powered by **LangGraph** for complex, stateful workflows and **smolagents** for efficient, specialized task execution.
* **🔍 Predictive Analytics:** Real-time processing of climate data to identify high-risk zones, flood potentials, and carbon footprints.
* **⚡ Modern API Layer:** Built with **FastAPI** for high-performance, asynchronous data handling and seamless model serving.
* **📊 Interactive Dashboard:** A sleek, responsive frontend built with **React (Vite)** and **Bootstrap** for intuitive risk visualization and reporting.
* **🤖 Autonomous Research:** Agents capable of browsing, scraping, and synthesizing the latest climate reports and live sensor data.

---

### 🛠️ Tech Stack

| Layer | Technology Used |
| :--- | :--- |
| **Brain (AI)** | LangGraph 🦜🔗, Hugging Face `smolagents` 🤗 |
| **Backend** | FastAPI ⚡, Python 🐍 |
| **Frontend** | React (Vite) ⚛️, Bootstrap 🎨 |
| **Models** | Hugging Face Inference API / Open-Source LLMs 🤖 |
| **Deployment** | Vercel 📐 |

---

### 🚀 Getting Started

Follow these steps to set up the Agentic Climate Risk System locally:

1.  **Clone the Repo** 📥
    ```bash
    git clone [https://github.com/your-username/Climate_Risk_Project.git](https://github.com/your-username/Climate_Risk_Project.git)
    cd Climate_Risk_Project
    ```

2.  **Set Up Backend (AI & API)** ⚙️
    ```bash
    cd backend
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3.  **Set Up Frontend** 💻
    ```bash
    cd ../frontend
    npm install
    ```

4.  **Environment Variables** 🔑
    Create a `.env` file in the `/backend` folder:
    ```env
    HUGGINGFACE_API_KEY=your_hf_token
    ENDPOINT_URL=your_model_endpoint
    PORT=8000
    ```

5.  **Launch the System** 🔥
    * **Run Backend:** `uvicorn main:app --reload`
    * **Run Frontend:** `npm run dev`

---

### 🧬 Agent Workflow

The system utilizes a directed acyclic graph (DAG) to manage agent interactions:
1.  **Ingestion Agent:** Collects raw climate metrics from satellite and IoT APIs.
2.  **Risk Analysis Agent:** Evaluates data using Hugging Face models to score environmental threats.
3.  **Visualization Agent:** Generates structured JSON for the React/Bootstrap dashboard.

---

### 🤝 Contributing

We welcome contributions to help make the world more climate-resilient! 🌿

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/ClimateFeature`)
3.  Commit Changes (`git commit -m 'Add new climate model'`)
4.  Push to the Branch (`git push origin feature/ClimateFeature`)
5.  Open a Pull Request

---

### 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information. 📜
