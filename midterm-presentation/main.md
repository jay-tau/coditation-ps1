---
marp: true
theme: gaia
class: invert
---

# Project Boxxy: Open Source GPU Remote Access & Development Suite

## Project Report-I

\
\
\
\
Joel Tony
2021A7PS2077G

---

## What is Boxxy?

- What Google Colab did to GPU compute, Boxxy aims to do for graphics
- Consists of an engine, streaming server, and a development environment for real-time debugging

---

## Project Design

### WebRTC

- Delivery of content from the engine to the user
- Cross-platform (browser-based)

### WebGPU

- Component which interacts with the hardware on the server
- Uses WebGPU to ensure that it is OS agnostic
- Handle popular shader languages like GLSL and SPIR-V

---

### DevSync

- Enable real-time coding and debugging.
- Code in a local environment but execute the binary on the remote server
- Have QoL features such as hot reloading

### Compiler Infrastructure

- Implement remote caching and reduce turnaround time for builds
- Utilise distributed caching to store unchanged artifacts
- Allow for distributed builds to fully utilise compute

---

## My work at Coditation so far...

- Bazel
  - Artifact-based
  - Remote-caching
  - Remote-execution
- CMAKE and vcpkg
- WebGPU

---

<!-- _class: lead invert-->

## Questions?

