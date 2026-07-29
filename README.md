# Sugars Portfolio — Interactive 3D Portfolio Experience

> A public case study for a private-source portfolio project.

Sugars Portfolio is a premium personal portfolio experience built around an explorable 3D city. Instead of presenting projects as a conventional list of cards, the interface uses spatial navigation, cinematic camera movement and interactive city locations to create a more memorable way of exploring professional work.

The production source code remains private. This repository documents the product direction, selected engineering decisions and visual progress without exposing proprietary implementation details.

## Project Snapshot

| Area           | Details                                                          |
| -------------- | ---------------------------------------------------------------- |
| Project type   | Interactive personal portfolio                                   |
| Role           | Product design, frontend development and interaction engineering |
| Status         | In active development                                            |
| Source code    | Private                                                          |
| Public website | Coming soon                                                      |

## Product Direction

The experience is designed as a living city rather than a static website. Major portfolio sections are represented by interactive locations such as Projects, About, Services, Gallery and Contact.

The design goals are:

* Create a premium and distinctive first impression
* Keep navigation understandable despite the cinematic presentation
* Support smooth transitions between city locations
* Preserve application state while moving between sections
* Remain performant across practical desktop hardware
* Present private work without publishing proprietary source code

## Core Experience

### Navigable 3D City

The homepage acts as the central navigation space. Visitors move through the experience by selecting visible city locations rather than using a conventional menu alone.

### Cinematic Camera System

Camera movement is treated as part of the user experience. Routes are designed to feel intentional and physically believable while preventing distracting direction changes, abrupt rotations and loss of visual focus.

### Persistent Application State

The 3D scene is designed to remain mounted while users navigate between portfolio sections. This allows the experience to preserve camera state, interaction state and scene continuity.

### Living Environment

Controlled environmental events help the city feel active without overwhelming the interface. Planned details include window lights, distant transport, rain changes, subtle smoke, billboard variation and rare background movement.

## Selected Engineering Areas

* Route-based camera movement and transition states
* Interactive hotspot architecture
* Persistent WebGL canvas integration
* State management across route changes
* Performance-aware scene composition
* Responsive interface overlays
* Reusable configuration for camera positions and locations
* Progressive visual production from greybox to final assets

## Technology Stack

<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,threejs" alt="Next.js, React, TypeScript and Three.js" />
</p>

* **Next.js** — application structure and routing
* **React** — interface and component architecture
* **TypeScript** — safer application development
* **React Three Fiber / Three.js** — real-time 3D experience
* **GSAP** — controlled camera and interface animation
* **Zustand** — lightweight shared application state

## Development Approach

The project is being developed in progressive stages:

1. Information architecture and user flows
2. City logic and spatial planning
3. Greybox scene and navigation prototype
4. Camera routes and interaction states
5. Visual language and asset production
6. Performance testing and refinement
7. Case-study preparation and deployment

This sequence allows interaction and navigation risks to be solved before expensive final visual production.

## Current Progress

* [x] Core information architecture
* [x] Persistent 3D canvas structure
* [x] Initial city greybox
* [x] Home-to-About camera route
* [x] Interactive hotspot foundation
* [x] Camera debug and validation tools
* [ ] Final environment assets
* [x] Full project case studies
* [x] Performance optimization pass
* [ ] Production deployment

## Visual Case Study

Selected screenshots, short recordings and architecture diagrams will be added as the visual production reaches presentation quality.

Planned media structure:

```text
assets/
├── screenshots/
├── recordings/
└── diagrams/
```

No private source code, client information, credentials or production secrets will be published in this repository.

## Key Lessons

* Cinematic motion still needs clear UX rules.
* A visually ambitious interface should be validated in greybox form first.
* Camera behavior is easier to control when routes, gaze and application state are designed as separate systems.
* Distinctive presentation is most effective when it remains understandable and performant.

## Privacy Notice

This is a **showcase repository**, not the production repository.

The following remain private:

* Application source code
* Unreleased visual assets
* Internal project documentation
* Detailed implementation logic
* Credentials, environment variables and deployment configuration

---

<p align="center">
  <strong>Private source. Public process, results and engineering decisions.</strong>
</p>
