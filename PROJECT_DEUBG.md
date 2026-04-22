## use specify endpoint and apikey
### use uv
`uv pip install -e . `

`uv run mini-coding-agent --provider openai --base-url https://dashscope.aliyuncs.com/compatible-mode/v1 --api-key sk-xxx --model qwen-plus`

### use python:

`python mini_coding_agent.py --provider openai --base-url https://dashscope.aliyuncs.com/compatible-mode/v1 --api-key sk-xxx --model qwen-plus`