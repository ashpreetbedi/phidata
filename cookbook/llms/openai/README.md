# OpenAI Cookbook

> Note: Fork and clone this repository if needed

1. Create a virtual environment

```shell
python3 -m venv ~/.venvs/aienv
source ~/.venvs/aienv/bin/activate
```

2. Install libraries

```shell
pip install -U phidata openai
```

3. Export `OPENAI_API_KEY`

```text
export OPENAI_API_KEY=sk-***
```

4. Test Assistant

```shell
python cookbook/llms/openai/assistant.py
```

5. Test Structured output

```shell
python cookbook/llms/openai/pydantic_output.py
```

6. Test function calling

```shell
python cookbook/llms/openai/tool_call.py
```
