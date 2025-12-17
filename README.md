# Research-Visor
An attempt at becoming a cyborg



https://hackaday.com/tag/eyeglasses/
https://github.com/omegaui/linux-voice-control
https://www.instructables.com/Glasses-mounted-video-display-to-one-eye-turn-yo/
https://inairspace.com/blogs/learn-with-inair/how-to-make-a-heads-up-display-glasses-a-comprehensive-diy-guide?srsltid=AfmBOorsOy1kIe5v0kHRaa6O0O63jSoDPozTJSQd66wUpXONLrPVNV7O


https://makezine.com/projects/peppers-ghost-hologram-flask/

# Research-Visor

An attempt at becoming a cyborg.

This project explores the design of a **wearable, one-eye research visor**: a personal augmentation device that enables hands-free, real-time interaction with a computer or AI assistant through voice and minimal visual feedback.

This is **not** about building hardware yet.
This document defines the **intent, philosophy, and ideal form** of the Research-Visor.

---

## 1. Core Idea

Not just a visor.

The Research-Visor is a **personal research exosense**:

* One-eye visual overlay (non-dominant eye)
* Always-on conversational interface
* Fully hands-free
* Minimal, utilitarian design
* Modular and wearable

It is meant to feel like **equipment**, not a gadget.

Think:

* Borg-style monocular augmentation
* Firefighter radio usability
* Researcher / field-operator aesthetics

This is **augmentation**, not VR or AR entertainment.

---

## 2. Design Constraints (Non-negotiables)

These constraints define what the Research-Visor deliberately avoids.

### Visual

* One eye only
* See-through or ghosted display
* Low brightness
* Text, icons, outlines only
* No video feeds
* No flashy UI

Purpose:

* Preserve situational awareness
* Avoid nausea or overload
* Maintain social acceptability

---

### Interaction

* Voice-first
* No complex wake-word rituals
* Short commands, conversational flow
* Throat microphone preferred
* Optional bone conduction audio

No gestures. No hand tracking.

---

### Wearability

* Worn **over clothing**
* Not head-mounted only
* Weight distributed to shoulder and chest
* Quick on / quick off
* Compatible with glasses, scarves, beards

The device should feel closer to **PPE or assistive tech** than cosplay.

---

## 3. Physical Form Factor

### The Half-Plate Concept

The core physical idea is a **half-plate shoulder mount**.

This solves:

* Weight distribution
* Battery placement
* Cable routing
* Long-term comfort

#### Proposed Layout

* **Left shoulder half-plate**

  * Battery
  * SBC or processing unit
  * Audio hardware

* **Articulated arm** rising from shoulder

  * Adjustable like a mic boom
  * Stable, repositionable

* **Monocular visor module**

  * Mounted in front of non-dominant eye
  * Fine positional control
  * Detachable

Visual inspiration:

* Emergency service radios
* Industrial PPE
* Expanse-style utilitarian gear

---

## 4. Sensory Stack

### Inputs

**Primary**

* Throat microphone

  * Works in noise
  * Works outdoors
  * Privacy-friendly

**Secondary**

* Additional microphones for spatial or ambient audio capture
* Cameras (eventually multiple)

  * World-facing camera for observation
  * Optional inward-facing or side-mounted cameras

Audio and video inputs are designed for **recording and transcription**, not just interaction.

---

### Outputs

#### Visual Output (Visor)

* Minimal HUD
* One or two lines of text
* Large typography
* Symbols and icons
* Transparent or dark ghost background

Typical use:

* Live transcription snippets
* Keywords or entities detected
* Short summaries
* Confirmations

No scrolling paragraphs.

---

#### Audio Output

* Bone conduction preferred
* Optional in-ear fallback
* Directional and low volume

---

## 5. Cognitive Model

The Research-Visor should **not** behave like a chatbot floating in front of your face.

It should feel like:

> A second, quieter brain that only interrupts when useful.

### Interaction Principles

* Default state: silent
* Responds only when addressed
* Short answers by default
* Escalates detail only on request

Example:

* "Define EDRM" → one line
* "Expand" → more detail
* "Save this" → confirmation icon
* "Remind me later" → checkmark

This keeps the device usable in public spaces.

---

## 6. Software Philosophy (High-level)

No implementation details yet.

Guiding principles:

* Local-first by default
* Continuous capture where possible
* Works offline
* AI is assistive, not dominant
* Cloud optional but supported
* Everything is logged for later reflection and analysis

The visor is a **thinking and sensing prosthetic**, not a replacement brain.

---

---

## 7. Design Priority: Capability over Social Acceptability

Social acceptability is **not** a primary constraint.

The Research-Visor prioritizes:

* Capability
* Observability
* Continuous capture
* Augmentation depth

If the device appears unusual or confrontational, that is an acceptable tradeoff.
The goal is not blending in, but **seeing and remembering more than a human normally can**.

Aesthetics may still be utilitarian, but they do not override functional expansion.

---

---

## 8. Long-Term Vision

If successful, the Research-Visor evolves into:

* Research companion
* Memory prosthesis
* Real-time context engine
* Teaching and fieldwork aid
* Replacement for notebooks and phones

It aligns naturally with:

* Research Ready
* Value Chain Hackers
* AI-for-research tooling
* Reproducible research workflows

This is meant to be a **personal artifact**, not a mass-market product.

---

## 9. Future Perception Extensions (Non-Blocking)

Beyond the core system, the Research-Visor is designed to support **expanded perception layers**, inspired by the Borg concept of augmented sensing.

These capabilities are **explicitly out of scope for the initial build**, but are part of the long-term intent.

### Design Principle

Additional sensors are treated as **observation layers**, not interaction gimmicks.

* Passive by default
* Silent unless relevant
* Meaning-first, not data-first

The visor should never flood the user with raw sensor data unless explicitly requested.

---

### Potential Sensor Extensions

Examples of future-compatible perception modules:

* Hand tracking (symbolic gestures only)
* Infrared or low-light visual sensing
* Thermal gradients or presence detection
* Environmental sensing (sound, temperature, air quality)
* RF awareness (WiFi / Bluetooth density or direction)

These are meant to provide **contextual awareness**, not continuous overlays.

---

### Gesture Philosophy

If hand tracking is used, gestures are:

* Binary or symbolic
* Low cognitive load
* Optional

Example gestures:

* Open palm: pause listening
* Closed fist: dismiss
* Two fingers: expand response
* Point: tag object or context

Gestures complement voice interaction but never replace it.

---

### Borg Rule

The visor should show:

* Meaning
* Alerts
* Confidence indicators

Not:

* Raw sensor feeds
* Continuous metrics
* Debug-style data

Raw data is logged for later analysis, not displayed live.

---

## 10. Next Design Steps

---

## 10. Next Design Steps

Before any hardware is built:

1. Define the HUD states
2. Define the core voice commands
3. Define what must never appear visually

Suggested next step:

> Define the always-on vs summoned HUD states

---

## References & Inspiration

* [https://hackaday.com/tag/eyeglasses/](https://hackaday.com/tag/eyeglasses/)
* [https://github.com/omegaui/linux-voice-control](https://github.com/omegaui/linux-voice-control)
* [https://www.instructables.com/Glasses-mounted-video-display-to-one-eye-turn-yo/](https://www.instructables.com/Glasses-mounted-video-display-to-one-eye-turn-yo/)
* [https://inairspace.com/blogs/learn-with-inair/how-to-make-a-heads-up-display-glasses-a-comprehensive-diy-guide](https://inairspace.com/blogs/learn-with-inair/how-to-make-a-heads-up-display-glasses-a-comprehensive-diy-guide)
