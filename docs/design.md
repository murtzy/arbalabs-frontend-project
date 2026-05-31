# Design Vision
Creating a "premium", "intelligent", and aerospace-inspired interface that prioritizes clean aesthetics, functional precision, and high levels of legibility.

## Typography
- **Brand & Headings**: IBM Plex Sans. (Provides an industrial, technical, and solid feel).
- **Data & Telemetry**: Public Sans. (Clean, legible tabular numbers).
- **Technical Logs**: JetBrains Mono. (Used specifically for code blocks or native system logs).

## Color Scheme & Aesthetics (Muted & High-Contrast Neutral)
- **Primary Background**: Pure Black (`#000000`). No gradients. No blue tint.
- **Panels & Cards**: Neutral Zinc (`#111111` or `#18181B`). No glassmorphism.
- **Borders**: Muted Neutral Gray (`#27272A` or `#333333`). No bluish borders.
- **Secondary Text / Hashes**: Gray (`#A1A1AA`). Less important numbers and cryptographic hashes should not use bright accent colors.
- **Status Accents**: Clear, simple status visualizations (e.g., a large green indicator reading "NOMINAL" or "VERIFIED"). Avoid neon or glowing colors.

## Visual Effects & Layout Rules
- **No Hacker Tropes**: The interface must be free of all unwanted hacker-style decorative elements (such as `>_` prompts or random scanning lines).
- **No Microscopic Clutter**: Remove panels full of microscopic static numbers. Replace them with clear, bold status visualizations.
- **Breathable Layout**: Let the design breathe with structured white space. Eliminate unnecessary DOM elements.
- **Essential Features Only**:
  - Countdown
  - Telemetry Dashboard
  - AI Verification Status Panel
  - Mission Timeline
  - Payload Upload Area

## Architecture
- Development priorities should shift to creating a modular, scalable architecture and maintainable code.
- Minimize DOM clutter and nested wrappers.
