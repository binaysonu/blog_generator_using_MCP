# Build an AI Agent with Google ADK - MCP Integration


## Project Structure

- `blogger/agent.py`: The main agent application with MCP integration.
- `blogger/server.py`: The minimal MCP server exposing the `trends` tool.
- `requirements.txt`: Python dependencies.
- `.env`: Environment variables (API key).
- `index.lab.md`: The step-by-step codelab.

## Setup Instructions

### 1. Navigate to the Project Directory
```bash
cd build-mcp-agent-google-adk
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Setup Environment Variables
Update your `.env` file with your Gemini API key:
```text
MODEL=gemini-flash-latest
GOOGLE_API_KEY=your_api_key
```

## Running the Agent

Run the following command to start the ADK Web UI:
```bash
adk web .
```

Open your browser and navigate to `http://127.0.0.1:8000` to interact with the agent!

*Note: The MCP server starts automatically when the agent needs it. You do not need to run it separately.*


