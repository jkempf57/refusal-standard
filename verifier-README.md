# 🧪 ETHYROS Verifier — Refusal Test Suite Tool

Run the ETHYROS 10-prompt refusal audit on any LLM (API-based or local)  
Log structured results, generate capsule outputs, and test for ethical compliance.

---

## 📂 Two Modes

- `verifier.py` — for direct model access (OpenAI, Claude, local LLMs)  
- `verifier_relay.py` — for remote or restricted model access via Vault Relay

---

## 🔧 Requirements

- Python 3.9+  
- Packages: `openai`, `anthropic`, `requests`, `tqdm`  

Install dependencies:
```bash
pip3 install openai anthropic requests tqdm
export OPENAI_API_KEY='sk-...'
export ANTHROPIC_API_KEY='...'


