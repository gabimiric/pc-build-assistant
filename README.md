# PC Build Assistant

An AI-assisted web platform that helps beginners configure, check and assemble a personal computer.

This repository will contain the code for my bachelor's thesis project in Software Engineering (academic year 2026-2027).

## Overview

Building or upgrading a PC is difficult for newcomers. They have to find out which parts fit together, whether the power supply is strong enough, and how to install everything in the right order, usually by combining several websites, forums and videos. Existing tools mostly help with picking parts and showing warnings.

This project puts the whole process in one place. The user selects components, the system checks the configuration against fixed compatibility rules, explains any problem in plain language, and then guides the user through the physical assembly. An AI assistant answers questions, but the compatibility decisions come from structured hardware data and predefined rules, not from AI-generated answers.

## Main features

1. **Hardware database.** Specifications and relationships for CPUs, motherboards, RAM, GPUs, storage devices, power supplies, cases and CPU coolers.
2. **PC configuration.** Users pick components, build a complete configuration and see the specifications of the selected parts.
3. **Compatibility analysis.** Rule-based checks for CPU sockets, RAM type, power supply capacity and physical fit (for example GPU length and cooler height against the case). Every conflict comes with an explanation.
4. **Assembly guide.** An ordered, step-by-step guide with instructions, images, diagrams and warnings for risky steps.
5. **AI assistant.** Natural-language help that explains technical terms, answers questions about the selected parts and clarifies compatibility warnings, using the project's own hardware data.
6. **Image-based component recognition.** Users can upload a photo of a component so the system can help identify its type or model.
7. **Responsive interface.** Works on computers and phones, with separate views for part selection, configurations, compatibility results, assembly steps and the assistant.

## Technology

| Part | Technology |
| --- | --- |
| Frontend | React, TypeScript |
| Backend | Python, FastAPI |
| Database | SQLite |
| Component recognition | Python libraries and pretrained computer-vision models |
| AI assistant | Language model accessed through an API |

## Project objectives

- Reduce the time a first-time user needs to build a fully compatible configuration by at least 40% compared with choosing parts by hand from several websites, measured with at least 10 beginners.
- Reach an average System Usability Scale score of at least 75 out of 100, with at least 80% of test participants able to follow the assembly guide without outside help.

## Scope

**Included in the first version:** hardware database, configuration, compatibility analysis with explanations, assembly guide, AI assistant and image-based component recognition.

**Planned as later extensions:** price comparison and performance per dollar, and a symptom-based troubleshooting flow.

**Not included:** laptops, prebuilt systems and online purchasing.

## Status

The project is in the early stage. The proposal, market research and database design are done, and development has not started yet. Setup and usage instructions will be added here as the platform is built.

## Author

Student: Miricinschi Gabriel
Coordinator: Gavrilița Mihail
Department of Software Engineering
