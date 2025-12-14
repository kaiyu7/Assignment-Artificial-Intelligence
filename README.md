Instruction
-----------

1️⃣ Install Ollama
Download and install Ollama from the official website:

👉 https://ollama.com/download

After installation, make sure Ollama is running in the background.

2️⃣ Download AI Models (Command Line)
Open Command Prompt and use the following commands:

ollama pull llama3.2:3b

ollama pull Gemma2:2b

ollama pull Qwen2.5:3b

To check the models you have already downloaded:
ollama list

3️⃣ Run the Multi-Model Comparison UI
Navigate to the Streamlit directory and run the triple-model comparison interface:
cd Assignment-Artificial-Intelligence\streamlit run triple_comparison_ui.py

📌 This interface allows three AI models to run and be compared simultaneously.

4️⃣ Run the Single-Model Chatbot UI
To run a chatbot using one AI model:
cd Assignment-Artificial-Intelligence\streamlit run streamlit_chatbot_<model_name>.py

📌 Replace <model_name> with the desired AI model file name.

5️⃣ Generate Performance Report
To generate the AI model comparison report:
cd Assignment-Artificial-Intelligence\python single_laptop_comparison.py

📌 This script produces a performance and response comparison report.
