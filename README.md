# MLLM-API-Demos

## Installation
```
conda create -n mllmapi python=3.10

conda activate mllmapi

pip install -r requirements.txt
```

## Set your API keys in *.ipynb
```
# in gpt4o_demo.ipynb
client = openai.OpenAI(api_key="")

# in qwen_demo.ipynb, compatible with OpenAI api
client = OpenAI(
    api_key="", 
    base_url="https://dashscope.aliyuncs.com/compatible-mode/v1",
)
```
