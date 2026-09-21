
# Advanced Rag Agent with Langgraph and Qdrant

This repo is about an advanced rag agent.
The architecture is a backend with fastAPI ( I used REST API for this project), and the front end is created with React.
I used ollama to run locally LLMS, feel free to use OpenAI API if you have one.
I used Qwen2.5 as the LLM.
You can also have access to the metrics with langfuse ( don't forget to create a .env for your APIs).

For this project, I used Langgraph, Qdrant as the VectorDB. This agent is advanced because It shows images from the image collection (Qdrant) and give you answer using context store in the VectorDatabase. But if there are nothing on the topic asked in the vectorDB, the agent with search on the Web!



## Installation
### Requirements:

* Clone this project:
 `git clone + url of my project`
* Run the backend:
`cd backend`


`uvicorn main:app --reload`
* Run the frontend:

`cd frontend`


`npm run dev`

