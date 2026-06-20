# Local LLM Compute

## Candidate Compute Tiers

| Tier | Candidate | Notes |
|---|---|---|
| Economy | Raspberry Pi 5 class | Lower power, slower inference |
| Mid-tier | Orange Pi 5 Plus / Jetson Orin Nano class | Better edge compute candidates |
| High-end | x86 mini PC / high-RAM module | Best practical local LLM performance |

## Software Candidates

- llama.cpp
- Ollama
- OpenAI-compatible local API server
- Custom lightweight HTTP service

## Interface to HMI

Preferred first interface:

- HTTP over local network or USB Ethernet.

Alternate:

- UART or USB serial command bridge.
