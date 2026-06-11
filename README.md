# Word-Fall

A website to replicate requests of the game Wordwall

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Project Overview

WordFall Engine is a technical case study in application reverse-engineering and state machine simulation. The goal of this project was to analyze closed-source, interactive web components (specifically falling-text educational mechanics) and rebuild the core engine from the ground up using open-source web technologies.

By analyzing DOM behavior and data schemas, this project successfully replicates a real-time game loop while keeping the core game logic entirely decoupled from the rendering layer.

> **Disclaimer:** This project is an independent educational research initiative. It is not affiliated, associated, authorized, endorsed by, or in any way officially connected with Wordwall or any of its subsidiaries. 

---

## Key Features

* **Decoupled Architecture:** The core input-verification and physics logic are separated from the UI, making it easy to port the engine to other frameworks or graphical libraries.
* **Lightweight Footprint:** Built with vanilla web standards to optimize memory allocation and ensure smooth performance across various devices.

---

## Technical Architecture

Replicating the functionality of the target platform required a structured, black-box engineering approach:

1. **Schema Extraction:** Emulates how Wordwall initiates a request when the game is done, added support for all types of games with a point system,
2. **Easy UI** has guides to get the magic number for the request initiation.
