# Pump Power Calculator (পাম্প পাওয়ার ক্যালকুলেটর)

A Bengali-language web calculator that estimates the motor power required for a pump from flow rate, total head and pump efficiency.

## Formula
- Hydraulic power (kW) = Q (m³/h) × H (m) / 367
- Shaft power = Hydraulic power / efficiency
- Motor power = Shaft power × (1 + safety margin), rounded up to the nearest standard motor size

## Features
- Mobile-first, works offline, dark mode support
- Standard motor size suggestion (kW and HP)
- No dependencies, plain HTML/CSS/JavaScript

## Usage
Open `index.html` in a browser, or host it with GitHub Pages.
