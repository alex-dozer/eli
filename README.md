# eli — Electromagnetic Lookup Interface

Eli is an experimental system for observing and interpreting the wireless world.

The goal of Eli is simple in concept but large in scope:

> ingest a wide band of wireless signals to develop a real-world picture of what exists outside the house.

This project is not focused on a single protocol (like WiFi), a single device class, or a single radio band.  
Instead, Eli treats the electromagnetic environment as a continuous stream of physical information that can be sampled, buffered, analyzed, and reasoned about.

---

## Why Eli Exists

Modern software systems usually interact with the world indirectly:

- logs
- APIs
- files
- user input

But the physical world is already broadcasting enormous amounts of information continuously:

- WiFi traffic  
- Bluetooth beacons  
- IoT chatter  
- cellular signals  
- unknown transmissions  
- environmental RF noise  

Eli exists to explore what happens when we treat those signals as first-class input.

Not as “network packets”.

As **environmental data**.

---

## Project Philosophy

Eli is intentionally experimental.

This is not a polished product.  
This is a an exploratory platform for:

- wide-band signal ingestion
- streaming buffer architectures
- FFT / spectral analysis pipelines
- real-time signal classification
- hardware + software integration
- continuous environmental sensing
- machine learning training

The system is being built publicly, including mistakes, pivots, and redesigns.

The goal is to have fun and gain understanding. And to work with my hands....

---

## What Eli Is (Right Now)

At the current stage, Eli is nothing....

In the future the intentions is:
- capturing radio signals across multiple bands
- converting raw RF input into structured digital streams
- performing spectral analysis
- identifying signal presence and patterns
- experimenting with classification techniques

There will be a lot of rough edges, pivots and noobie mistakes.


This repository documents the construction process in real time.

---

## What Eli Is NOT

Eli is not:

- a surveillance tool
- a hacking framework
- a turnkey RF scanner
- a finished product

It is a research system for understanding how wireless environments can be modeled computationally.

---

## Relationship to The Dozer Project

Eli may eventually feed into the broader Dozer ecosystem (Ben, Lucius, Benson, etc.) by providing:

- real-world streaming signal data
- high-volume differential input sources
- new ingestion pipeline patterns
- hardware-level telemetry concepts

For now, Eli lives as a standalone exploration project.

This separation is intentional.

---

## Technical Direction (Early)

Planned areas of experimentation:

- SDR / radio hardware ingestion
- ESP32-based signal sampling nodes
- continuous streaming architectures
- FFT implementations
- signal fingerprinting
- ML-assisted classification experiments
- visualization of spectrum changes over time

Implementation language will primarily be Rust where practical.

---

## Status

Early experimental construction and architectural hardening.

Nothing here should be considered stable.

Everything here should be considered educational.

---

## Why Public?

Because the interesting part isn't the finished system.

It's the process of figuring it out.

This is large and long term. And honestly this is more because I think it'll be cool to try.

Going to build in Rust as much as possible.
