
Demo:

https://www.youtube.com/watch?v=0knKn9B5KSQ

Introduction:

Introducing FitGuide, a comprehensive Python tool designed to revolutionize your fitness journey. FitGuide not only offers workout and diet plans but also provides an interactive chat experience to assist you on your wellness path. Through natural language input, you can ask questions about your fitness plans, receive personalized guidance, and access valuable insights. Powered by an advanced language model, FitGuide ensures precise and tailored responses, creating a seamless and dynamic interaction. It's your go-to companion for achieving your fitness goals, offering a personalized touch to your workout and nutrition inquiries. Note that FitGuide exclusively caters to fitness-related queries, delivering an enhanced experience to support your health and wellness aspirations.

Dependencies and Installation:

To install the Chat App, please follow these steps:
Clone the repository to your local machine.
Install the required dependencies by running the following command:
•	conda create -p myenv_llm python=3.9.4
•	conda activate myenv_llm /
•	pip install -r requirements.txt
Obtain an API key from OpenAI and add it to the .env file in the project directory.
•	OPENAI_API_KEY=your_secrit_api_key
•	HUGGINGFACEHUB_API_TOKEN = your_secrit_api_key


Usage:

To use the Chat App, follow these steps:
Ensure that you have installed the required dependencies and added the OpenAI API key to the .env file.
Run the main.py file Execute the following command:
•	streamlit run app.py


Technology Used:

•	The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.
•	The FAISS index will be saved in a local file path in pickle format for future use.
•	Also worked on Pinecone Vector Database
•	Used Openai LLM model and hugging face hub for LLM 
•	Used LangChain

 

 
![image](https://github.com/OmkarNaik10/FITGPT_LLM/assets/46419836/5b7526e4-cc12-4c16-82de-29b0b59671ce)

![image](https://github.com/OmkarNaik10/FITGPT_LLM/assets/46419836/1962e42e-7c35-4b89-9fb8-9c635a08c0cc)

