# Hi, I'm Catarina 👋

Building verifiable infrastructure for AI.

Creator of **AELITIUM** — tamper-evident evidence bundles for LLM outputs.

## AELITIUM

Same request. Different response. Can you verify the evidence?

AELITIUM produces cryptographic evidence bundles for every LLM call and enables offline verification of recorded outputs — without a vendor server.

```bash
pip install aelitium
bash examples/drift_demo/run_demo.sh
# STATUS=CHANGED
# REQUEST_HASH=SAME
# RESPONSE_HASH=DIFFERENT
```

Same request hash. Different recorded response hash. Tampering is detectable.

- 📦 [PyPI](https://pypi.org/project/aelitium/) — `pip install aelitium`
- 🔗 [GitHub](https://github.com/aelitium-dev/aelitium-v3)
- 🌐 [aelitium.com](https://aelitium.com)
- 📄 Apache 2.0
