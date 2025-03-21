# Project Title: Retrieval Augmented Generation (RAG) Application

## Project Overview

This project implements a Retrieval Augmented Generation (RAG) application that allows users to ask questions about specific content from a blog post. The application uses LangChain and LangGraph to retrieve relevant information and generate answers using a language model.

## Architecture and Components

The architecture of the RAG application consists of the following components:

1. **Document Loader**: 
   - Utilizes `WebBaseLoader` to fetch and parse content from a specified URL.

2. **Text Splitter**: 
   - Uses `RecursiveCharacterTextSplitter` to break down large documents into smaller, manageable chunks for better processing.

3. **Vector Store**: 
   - Implements an in-memory vector store to index the document chunks, allowing for efficient retrieval based on user queries.

4. **Language Model**: 
   - Integrates with OpenAI's language model to generate answers based on the retrieved context.

5. **State Management**: 
   - Uses `StateGraph` from LangGraph to manage the flow of data and control the application steps.

## Installation Instructions

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Create a Virtual Environment** (optional but recommended):
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
   ```

3. **Install Dependencies**:
   Make sure you have `pip` installed, then run:
   ```bash
   pip install langchain langchain-community langchain-text-splitters langgraph beautifulsoup4
   ```

4. **Set Up Environment Variables**:
   If required, set up your environment variables for API keys:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key"
   ```

5. **Run the Application**:
   Execute the main script to start the application:
   ```bash
   python main.py
   ```

## Usage

Once the application is running, you can ask questions related to the content of the blog post. For example, you can input:
```
What is Task Decomposition?
```

## Screenshots

Part 1
![image](https://github.com/user-attachments/assets/a1a5a365-2dc5-408a-8376-8c3c27b0939b)

![image](https://github.com/user-attachments/assets/3b20ab4d-94b3-4a35-8641-2df0fa5b93f8)

![image](https://github.com/user-attachments/assets/65bec61e-0778-4636-bce7-56d0b1d9c864)

Part 2

![image](https://github.com/user-attachments/assets/0b637277-2fcb-4a6a-b7f8-bc02a52b203a)

![image](https://github.com/user-attachments/assets/9d15e4f2-469a-4657-9799-f08788510b85)

![image](https://github.com/user-attachments/assets/432d8414-ffe7-47c5-a08e-0e8b0f7e737b)

![image](https://github.com/user-attachments/assets/28f14b7f-b305-4e3a-be42-054643bcd27f)

![image](https://github.com/user-attachments/assets/7e369625-3e4d-4414-a215-e6c1fc14bd53)

![image](https://github.com/user-attachments/assets/f8e0d5c0-370f-4c71-b341-ab8509bda76c)

![image](https://github.com/user-attachments/assets/69d263a5-6574-457c-ac3d-e38b1c8cef52)

![image](https://github.com/user-attachments/assets/3f6c2534-505a-4122-a185-11a83083c0fc)

![image](https://github.com/user-attachments/assets/4333e42b-3016-4cdd-8925-a04f603ff192)

![image](https://github.com/user-attachments/assets/0ebf0151-4bbc-481c-9170-b2f76e965fbb)

![image](https://github.com/user-attachments/assets/6f0a9a17-3ef6-4d6c-88f4-413491215c76)

![image](https://github.com/user-attachments/assets/f3cb72d5-15ec-4e40-a112-9c7c46c86b19)

![image](https://github.com/user-attachments/assets/f848fd6a-2af1-434d-968b-e369301ee026)

![image](https://github.com/user-attachments/assets/ab13b849-77dc-41a1-8ae9-117a724afeb9)
![image](https://github.com/user-attachments/assets/10995a65-b953-436c-85b3-b2eea463c79a)

![image](https://github.com/user-attachments/assets/c5a74446-a421-4310-a045-4c9a09a88db8)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [LangChain](https://langchain.com/)
- [OpenAI](https://openai.com/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
