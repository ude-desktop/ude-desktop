# Universal Desktop Environment (UDE)

**One desktop. Every application. Your way.**

UDE is an experimental **cross-platform desktop environment and graphical shell** design exploring a consistent user interface on Linux, Windows and macOS, with modular application launchers, configurable taskbars, native file management and adaptable window controls.

> **Design reference, not a working cross-platform desktop release.** This repository preserves the original design sketches and research. The [UDE implementation repository](https://github.com/ude-desktop/ude) tracks the desktop project itself.

## Original design and whiteboards

[**Explore all original design sketches and their explanations →**](docs/design/README.md)

[![Original UDE whiteboard sketch showing the desktop layout](docs/design/01-universal-desktop-layout.jpg)](docs/design/README.md)

The [AI-generated concept illustration](docs/design/06-ai-concept-mockup.png) is a visual interpretation, **not** a working screenshot.

## Technical design areas

- **Desktop shell:** launcher, start/home screen, application overview, taskbar, tray, window decorations, tiling and task switching.
- **Host integration:** Linux desktop services and Nautilus, plus proposed Windows and macOS adapters for native applications, system settings and file management.
- **Responsive interaction:** mouse, keyboard and touch, including tablet layouts and adaptable screen sizes.
- **Modular architecture:** UDE Lite on an existing desktop stack versus a possible UDE Full session; neither should be represented as completed.
- **Application discovery:** native installed applications, real metadata/categories and consistent launching across host platforms.

See [technical focus](docs/technical-focus.md) for developer collaboration areas and [contributing](CONTRIBUTING.md) for how to propose changes to the original design.

## Why this repository exists

The original whiteboard sketches are the primary source for the intended UX, including the desktop layout, launcher, navigation, window controls and platform-adaptation ideas. They are reference material, not pixel-perfect requirements. A proof of concept should link to the relevant sketch and state exactly what is functional.

**Status:** Early design/research. Independent project work is not automatically part of UDE; do not infer support for other software or platforms from diagrams.

*Useful software. Open development.*
