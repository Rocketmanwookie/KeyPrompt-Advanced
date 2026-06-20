# Test Plan — Advanced

## Test 1 — Local LLM Service

Expected: local service returns generated text to the ESP32.

## Test 2 — Safety Preservation

Expected: local compute output cannot type unless RP2040 is armed by physical INJECT state.

## Test 3 — Thermal Load

Expected: device remains within thermal limits during sustained inference.

## Test 4 — Power Load

Expected: compute and HMI remain stable under peak draw.
