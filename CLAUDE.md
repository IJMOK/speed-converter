# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Simple HTML/CSS/JS speed converter - converts between kilometers per hour (km/h) and miles per hour (mph).

## Running the Project

Open `index.html` directly in a browser. No build step or server required.

## Architecture

Single-file HTML with:
- Inline CSS using CSS custom properties for theming (light/dark mode support)
- Vanilla JavaScript for conversion logic
- Two-way conversion: entering a value in either field updates the other

Key conversion constants:
- `KM_TO_MILES = 0.621371`
- `MILES_TO_KM = 1.60934`

The UI uses a responsive grid that stacks vertically on mobile (≤480px).