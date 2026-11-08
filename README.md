
Action-->	Command
Create venv	--> python3 -m .venv venv
Activate-->	source .venv/bin/activate

pip install -r requirements.txt

# test mcp server
uv run fastmcp dev inspector main.py 

# Run mcp server
uv run main.py