
### 7. `python-llm-vllm-prompt-automation/README.md`

```markdown
# Python LLM vLLM Prompt Automation

LLM/vLLM 提示语工程与批量自动化工具。仓库内不包含 API Key、客户 Prompt 或业务数据。

## 功能
- Prompt 模板与变量渲染
- 批量任务与并发控制
- 重试、限流、超时处理
- JSON 输出校验
- 评测报告（准确率/格式合规率等）
- 环境变量管理密钥

## 技术栈
Python、vLLM OpenAI-Compatible API、Pydantic、asyncio

## 快速开始
```bash
pip install -r requirements.txt
export LLM_BASE_URL="http://localhost:8000/v1"
export LLM_API_KEY="your-key"
python run_batch.py --template prompts/input.yaml --input data/input.jsonl
