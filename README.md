 AutoPlanAI

AutoPlanAI is a smart layout planner that uses artificial intelligence to help users design homes, bungalows, or office spaces through a chat-based interface. The system takes user inputs like number of floors, types of rooms, accessories (garden, swimming pool, etc.), and generates a floor layout automatically.

The main goal of AutoPlanAI is to make layout planning easy and interactive using AI. The system can also learn from user feedback and improve its suggestions over time.
# Project Objective

- To create an intelligent assistant that can plan space layouts through conversation.
- To reduce manual work in layout design.
- To use LLMs (like GPT) to ask relevant questions and understand user needs.
- To implement a feedback loop that helps the system improve based on user responses.
# How It Works

1. The user starts by describing what kind of space they want (house, flat, office).
2. The AI assistant asks follow-up questions like:
   - Number of floors?
   - How many rooms?
   - Do you need extra features like garden, pool, or parking?
3. Based on the answers, a 2D layout is generated.
4. The user can request changes (e.g., move a room, increase kitchen size).
5. The AI remembers the feedback and avoids similar issues next time.
# Technologies Used

- *Python* – Programming language
- *LangChain + OpenAI API* – To build the AI assistant
- *Streamlit* – To create a user interface
- *Matplotlib* – To draw the 2D layout
- *JSON* – To store input and feedback data
# Files in This Project

- layout_agent.py – Code that manages the conversation with the user.
- layout_generator.py – Code that creates the 2D layout.
- app_streamlit.py – The main interface where user inputs are given.
- feedback_logger.py – Logs the user’s feedback for learning.
- layout.png – Sample layout image.
# Future Improvements

- Add 3D layout visualization
- Support image/blueprint input
- Better memory system using vector databases
- Save project designs for each use
