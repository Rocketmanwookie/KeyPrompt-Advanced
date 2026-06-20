# Claims Draft Notes

Date created: 2026-06-20

This file contains rough claim concepts only. It is not legal advice.

## Independent Claim Candidate — System

A portable text-output device comprising:

1. a touchscreen user interface configured to receive or edit a user prompt;
2. a controller configured to transmit the prompt to an AI text-generation service or model and receive generated text;
3. a review interface configured to display the generated text and receive user approval;
4. a USB HID keyboard bridge configured to output approved generated text as keyboard input to a target device; and
5. a hardware mode selector having at least a non-output state and an output-authorized state;
6. wherein the USB HID keyboard bridge refuses to output keyboard reports unless the hardware mode selector is in the output-authorized state.

## Dependent Claim Ideas

- The hardware mode selector includes OFF/KILL, REVIEW, and INJECT positions.
- Movement into INJECT is mechanically gated by a case feature.
- The USB HID bridge clears a queued text buffer when the mode selector leaves INJECT.
- The device includes hardware-state indicators independent of touchscreen UI state.
- The device includes a battery subsystem with fuse, fuel gauge, and thermistor.
- The AI text-generation service is a cloud API.
- The AI text-generation service is a local model hosted in the device.
- The HMI controller and USB HID keyboard bridge are separate programmable devices.
- The target device identifies the output interface as a standard USB keyboard.
