# Hi, I'm Catarina 👋

Building verifiable infrastructure for AI.

Creator of **AELITIUM** — a tool that proves what an LLM actually returned.

## AELITIUM

Cryptographic verification for AI outputs.

Detect when the same request produces a different response.

```bash
pip install aelitium
bash examples/drift_demo/run_demo.sh
STATUS=CHANGED
REQUEST_HASH=SAME
RESPONSE_HASH=DIFFERENT

Same request. Different response.
The model changed — not your code.

Repository:
https://github.com/aelitium-dev/aelitium-v3

Website:
https://aelitium.com
