# SEARCH_ENGINE_PROJECT
LANGCHAIN - Chat With Search

This project is a Streamlit-based web application that uses LangChain's advanced tools and agents to provide a chatbot capable of retrieving information from the web, Arxiv, Wikipedia, and DuckDuckGo. The app features an interactive chatbot interface with real-time feedback powered by StreamlitCallbackHandler.

**Features**

- Web Search Integration: Retrieves real-time information from DuckDuckGo, Arxiv, and Wikipedia.
  
- LangChain Agent: Utilizes LangChain's Zero-Shot-React agent type for intelligent action selection.
  
- Customizable Settings: Users can input their Groq API Key and adjust settings via the sidebar.
  
- Interactive Chat: A friendly chatbot interface displays responses and the agent's reasoning.
  
- Real-Time Feedback: The chatbot's internal thought process and actions are streamed interactively.

**How It Works:**

**LangChain Agents:**

- Zero-Shot-React: Selects actions dynamically based on the query and tools available.
  
- Arxiv: Retrieves scientific articles, limiting results to the top 1.
  
- Wikipedia: Retrieves information from Wikipedia, limiting results to the top 1.
  
- DuckDuckGo: Searches the web for real-time data.
  
**StreamlitCallbackHandler:**
Displays the agent's thought process and actions in real time for better interactivity.

**User Interaction:**
Users input their questions, and the chatbot uses the specified tools to retrieve and format the response.

**Customizable Settings:**
Users can input their Groq API key and adjust other settings via the Streamlit sidebar





