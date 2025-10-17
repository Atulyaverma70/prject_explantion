## Customer Support Chatbot
* I built an AI powered Customer Support Chatbot that can answer the queries from your document and relvent web sources.
* In this project i used python and streamit. It use LLM with RAG workflow to dynamically answer the queries from document and web sources. I integrate with LLM like OpenAI, Grooq, Gemni, for flexible response. I use FAISS(facebook Ai similarity search) that help in fast retriving the content from document.
* user query-> streamlit frontend-> FAISS vector search-> RAG Pipeline(LLM + context)-> Answer Generation

### About technologies that used in our model
* RAG workflow: Retrieval + Generation, meaning the model first retrieves relevant information and then generates an answer using that information.
* Langchain: LangChain is a framework for building applications that use language models (LLMs).It helps you connect LLMs to external data, tools, and workflows so that they can do more than just generate text.
* FAISS(facebook AI similarity search): It help in finding most relvent information from the doncumets by conveting them in embedding.
* LLM: Large Language model It is tyoe of AI that trained on masive amount of data to understand and generate human like content.
    * Groq: Groq is a LLM model , Groq provides high-speed inference using their custom Language Processing Units (LPUs), which allows the model to generate responses very quickly with low latency.
        * LPU(Language processing unit): It is a custom hardware chip designed specifically to run large language models (LLMs) efficiently.
    * ChatGPT: ChatGPT is a conversational AI model developed by OpenAI. It is based on GPT (Generative Pre-trained Transformer) architecture, which is a type       of Large Language Model (LLM).Designed to understand natural language and generate human-like responses.
    * Gemni: Google Gemini is a family of advanced multimodal large language models (LLMs) developed by Google DeepMind.
