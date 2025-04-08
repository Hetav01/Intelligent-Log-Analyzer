# 🤖 Intelligent Log Analyzer Agent 🤖

Welcome to the **Intelligent Log Analyzer Agent**! This dummy version of the project demonstrates an AI-driven log analysis agent that processes, summarizes, and reports on log entries. Its purpose is to assist developers and system administrators in quickly identifying failures and extracting actionable insights from a collection of logs. The agent leverages state-of-the-art language models and structured graph processing to generate failure summaries and detailed reports, making it highly applicable in real-world monitoring, debugging, and system performance analysis.

---

![Main Dashboard](https://github.com/Hetav01/Intelligent-Log-Analyzer-Using-Langgraph/blob/main/UI1.png)
![Detailed Log View](https://github.com/Hetav01/Intelligent-Log-Analyzer-Using-Langgraph/blob/main/UI2.png)

---

## ✨ Why This Project Is a Game-Changer in Software Development

- **🚀 Accelerated Debugging & Troubleshooting:**  
  Quickly identify issues in complex log files, reducing downtime and allowing faster recovery from critical incidents.

- **⏱️ Time Efficiency:**  
  Automates the labor-intensive process of log analysis, enabling developers and IT teams to focus on strategic tasks rather than manual debugging.

- **💡 Actionable Insights:**  
  Delivers concise summaries and reports with clear recommendations, making it easier to pinpoint problems and optimize system performance.

- **🔍 Enhanced Monitoring:**  
  Continuous log processing ensures constant vigilance over system health, detecting anomalies and performance bottlenecks in real time.

- **🌐 Scalability for Enterprise Use:**  
  Designed to handle large volumes of logs from distributed systems, this solution is robust enough to scale alongside modern, high-demand infrastructures.

- **🤖 Leveraging AI & Graph Processing:**  
  Uses cutting-edge language models and a modular graph-based architecture to integrate seamlessly with existing monitoring tools, ensuring high accuracy and relevance.

- **🔧 Customizable & Extendable:**  
  Its modular design allows for easy customization and integration with a wide range of applications, empowering teams to tailor the tool according to their unique needs.

- **🎨 Cool & Engaging UI:**  
  Enhanced with modern CSS animations and interactive elements powered by Streamlit, making the application both functional and visually appealing.

---

## 🛠️ Tech Stack & Tools

- **Programming Language:** Python
- **Framework:** Streamlit for a user-friendly web interface.
- **Libraries & Tools:**
  - **langgraph:** Constructs stateful graphs to manage the workflow.
  - **langchain_openai:** Integrates OpenAI's language models for generating summaries and reports.
  - **ChatPromptTemplate:** Prepares structured prompts for AI-driven tasks.
  - **Type Hints:** Utilized through Python’s `typing` and `typing_extensions` to maintain code clarity.
- **UI Enhancements:**
  - Custom CSS animations for dynamic and engaging user experience.

---

## 🚀 Getting Up and Running

### **Prerequisites**

- Python 3.8+  
- Valid API key for OpenAI (and any additional credentials as required)  
- Git for repository management

### **Installation Steps**

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/intelligent-log-analyzer-agent.git
    cd intelligent-log-analyzer-agent
    ```

2. **Set Up Virtual Environment and Install Dependencies:**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```

3. **Configure API Keys:**

    Create a `.env` file in the project root and add your credentials:

    ```env
    OPENAI_API_KEY=your_openai_api_key_here
    ```

4. **Launch the Application:**

    ```bash
    streamlit run logAgent.py
    ```

   Then open your browser and navigate to:

    ```
    http://localhost:8501
    ```

---

## 🧑‍💻 How to Utilize the Agent

1. **Add Log Entries:**  
   Use the sidebar form to input details like Log ID, Question, Answer, and optional grading information.  
   Submit the form to add your log entry to the session.

2. **Execute the Agent:**  
   Click the **Execute Agent** button to process the logs.  
   The agent will run its graph-based workflow to generate two key outputs:
   - **Failure Analysis Summary:** Provides a concise overview of critical failure logs.
   - **Question Summarization Report:** Delivers insightful analysis that highlights key issues in your logs.

3. **View the Results:**  
   The output is streamed directly on the web interface, and you can expand sections to view detailed cleaned logs and processed data.

---

## 🤝 Contributing

Contributions are always welcome! If you’d like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes with a meaningful message:
    ```bash
    git commit -m "Describe your feature"
    ```
4. Push your branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request for review.

---

## 📄 License

This project is licensed under the **MIT License**. See the LICENSE file for more details.

---

## 🙌 Acknowledgments

- Built using cutting-edge **OpenAI language models** integrated with **Streamlit**.
- Inspired by modern AI techniques and stateful graph processing for automated log analysis.
- Special thanks to the community and contributors who continuously improve this technology.

---

## 📧 Contact

For questions, feedback, or further information, please contact:

**Your Name**  
Email: [your-email@example.com](mailto:your-email@example.com)  
GitHub: [your-github-profile](https://github.com/your-github-profile)
