# Safety Circuits — Advanced

Advanced preserves Lyte safety circuits.

The local LLM compute module does not have direct authority to type.

Only the RP2040 keyboard HID bridge may output to the target, and only when the physical INJECT state is active.
