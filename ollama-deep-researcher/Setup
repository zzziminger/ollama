# Pull the model
ollama pull deepseek-r1:8b

# Clone the repository
git clone https://github.com/langchain-ai/ollama-deep-researcher.git
cd ollama-deep-researcher

# Set up a virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -e .
pip install 'langgraph-cli[inmem]'

# Start langgraph development mode
langgraph dev
