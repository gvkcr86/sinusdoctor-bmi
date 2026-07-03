# SinusDoctor BMI Calculator

A premium, single-page BMI calculator by **SinusDoctor**.

**Live:** hosted on GitHub Pages · [sinusdoctor.com](https://www.sinusdoctor.com)

## Features

- **Instant calculation** — BMI updates live as you type, no submit button.
- **Unit toggles** — height in cm or ft + in, weight in kg or lbs (segmented pill toggles, with automatic value conversion when switching).
- **Save defaults** — remember your preferred units in `localStorage` for your next visit.
- **Rich results** — animated BMI value with colour-coded category (Underweight / Normal / Overweight / Obese) and a gradient scale bar with a position marker.
- **Target weights** — shows your weight at BMI 25 (upper healthy limit) and BMI 20 (lean target), with the exact amount to reduce in your chosen unit.
- **Validation** — sensible input ranges (height 100–250 cm, weight 20–300 kg equivalents) with gentle inline errors.
- Mobile-first responsive, light ivory + gold glassmorphic design.

## Tech

One self-contained `index.html` — all CSS and JavaScript inline. No build step, no frameworks, no external JS libraries (only Google Fonts). The SinusDoctor logo lives in `assets/logo.png`.

**Formula:** BMI = kg / m² (lbs × 0.45359237 → kg; ft × 30.48 + in × 2.54 → cm).

## Disclaimer

BMI is a screening tool, not a diagnosis. Consult your doctor for personalised advice.

© 2026 SinusDoctor
