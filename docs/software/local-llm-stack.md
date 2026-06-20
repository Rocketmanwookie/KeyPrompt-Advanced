# Local LLM Stack

Candidate stack:

```text
Local LLM service
    ↓
HTTP/OpenAI-compatible endpoint
    ↓
ESP32 HMI request
    ↓
Generated response returned to review UI
```

The model runtime is deferred until compute hardware selection.
