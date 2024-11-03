# Qwen-Agent
LLM-Agent
参考项目[Qwen-Agent](https://github.com/QwenLM/Qwen-Agent.git)
## environments
```
cd Qwen-Agent
pip install -e ./"[gui,rag,code_interpreter,python_executor]"
```
## deployment
* vllm
要求配置：linux、vllm支持的gpu
[vllm requirments](https://docs.vllm.ai/en/latest/getting_started/cpu-installation.html#cpu-backend-requirements)
```
pip install vllm
git lfs install
git clone https://www.modelscope.cn/Qwen/Qwen2.5-7B-Instruct.git
vllm serve Qwen/Qwen2.5-7B-Instruct
```
## Inference
* Hugging Face Transformer
