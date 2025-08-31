# Inventory Management AI Agent

This project demonstrates an **AI-powered Inventory Management Agent** that can interact with users to manage stock, answer queries, and provide guidance. The system is integrated with **n8n workflows** and uses a **free AI API** to generate responses. Due to the limitations of the free API plan, the agent may stop responding after a few requests. **Apart from these API limitations, the AI Agent works perfectly and all other functionalities are fully operational.**

## Screenshots & Explanation

**1. `Preview.png`**  
This screenshot provides a **preview of the AI agent interface along with the n8n workflow connections**. It shows how different nodes are connected to fetch inventory data, process user commands, and interact with the AI API. This overview highlights the backend automation that powers the AI agent. [View on GitHub](Inventry_Management_AI_Agent/images/Preview.png)

**2. `ChatAccess[URL].png`**  
This image shows how the AI agent can be accessed via a web interface or URL. Users can start a session from this link to interact with the agent for inventory-related tasks, such as checking stock, updating quantities, or generating reports. [View on GitHub](Inventry_Management_AI_Agent/images/ChatAccess[URL].png)

**3. `ChatWithAIAgent.png`**  
This screenshot demonstrates a **successful chat session** with the AI agent. The agent responds accurately to user queries and commands, showing the intended functionality when the API is working correctly. [View on GitHub](Inventry_Management_AI_Agent/images/ChatWithAIAgent.png)

**4. `ChatnotRunning.png`**  
This image shows the scenario when the AI agent is not running. If the backend server or AI service is offline, users cannot interact with the agent. In this project, this can also happen due to API usage limitations on the free plan, which temporarily blocks responses. Make sure the application is running to restore functionality. [View on GitHub](Inventry_Management_AI_Agent/images/ChatnotRunning.png)

**5. `InactiveChat.png`**  
This screenshot displays the chat interface in an inactive or unresponsive state. this due to API usage limitations on the free plan that prevent the AI from responding. Refreshing or restarting the session usually restores interactivity. [View on GitHub](Inventry_Management_AI_Agent/images/InactiveChat.png)

**6. `OpenAIkeylimitReach.png`**  
This image highlights an **API usage limitation**. Since the AI agent uses a free API plan, it may block responses after only a few requests. This is expected behavior for free plans and does **not** indicate a problem with the AI agent itself. All other functionalities are working perfectly. [View on GitHub]()

