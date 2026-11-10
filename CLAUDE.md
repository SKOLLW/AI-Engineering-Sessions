# AI Engineering Master — Sessions

This repo holds the session exercises of the AI Engineering master.

Before helping, read the course context in `../AI_engineer_master_context/README.md`
(stack, setup, models, student setup, decisions, course map).

Key facts:
- Python 3.11 via uv (`uv run ...`, `uv add ...`). FastAPI backend, Docker Compose, Streamlit UI.
- API provider is **OpenRouter**, used through the OpenAI SDK
  (`base_url="https://openrouter.ai/api/v1"`, model names like `openai/gpt-4o-mini`).
- This repo is **public**: never commit API keys. Keys go in `.env` (git-ignored) or Colab Secrets.
- Record new decisions in `../AI_engineer_master_context/05_decisions_log.md`.
