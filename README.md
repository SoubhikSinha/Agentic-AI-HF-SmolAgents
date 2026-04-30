# Agentic AI @ `HuggingFace's SmolAgents`

This mini-project demonstrates agentic AI workflows using Hugging Face **SmolAgents**, starting with a `CodeAgent` powered by `InferenceClientModel` to convert natural-language tasks into executable Python code, then extending the agent with pre-built tools like `DuckDuckGoSearchTool` for web search and external information retrieval. The notebook also explores controlled code execution through `authorized_imports` and `additional_authorized_imports`, enabling libraries such as `pandas`, `matplotlib`, `requests`, `bs4`, and `yfinance` for data fetching, analysis, and visualization. Beyond built-in tools, it implements a custom `HFModelDownloadsTool` by extending `Tool`, using `huggingface_hub.list_models()` to retrieve the most downloaded model for a given task, showing how SmolAgents can be expanded with domain-specific capabilities. The project further compares `CodeAgent` and `ToolCallingAgent`, including model backends such as Qwen via Hugging Face Inference Providers and OpenAI-compatible execution through `LiteLLMModel`, highlighting flexible agent design, tool calling, web-augmented reasoning, and modular LLM orchestration.
<br>
<br>

## References
[Krish Naik](https://github.com/krishnaik06)<br>
[Hugging Face SmolAgents](https://github.com/huggingface/smolagents)<br>
[Hugging Face Hub](https://huggingface.co/docs/huggingface_hub/index)<br>
[LiteLLM](https://github.com/BerriAI/litellm)<br>
[DuckDuckGo Search Tool](https://huggingface.co/docs/smolagents/en/reference/tools#smolagents.DuckDuckGoSearchTool)
