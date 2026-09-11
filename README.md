---
marp: true
theme: default
paginate: true
size: 16:9
style: |
  section {
    background: #061521;
    color: #f7fafc;
    font-family: Arial, Helvetica, sans-serif;
    padding: 70px 90px;
  }
  h1, h2, h3 { color: #ffffff; letter-spacing: 0.04em; }
  h1 { font-size: 64px; }
  h2 { font-size: 42px; border-bottom: 3px solid #ff5a1f; padding-bottom: 12px; }
  h3 { color: #ff6a2a; font-size: 25px; }
  strong { color: #ff6a2a; }
  blockquote {
    border-left: 7px solid #ff5a1f;
    color: #dce8ee;
    font-size: 28px;
    padding: 10px 28px;
  }
  table { width: 100%; font-size: 20px; }
  th { color: #ff6a2a; }
  td, th { border-color: #42606e; padding: 12px; }
  footer { color: #a9c1cc; }
---

<!-- _footer: LIFELINE · Autonomous Maritime Rescue -->

# LIFELINE

## Autonomous maritime rescue

**Detect. Deploy. Save lives.**

From a game-card concept to a real product for safer oceans.

---

# The mission

> Give people in danger at sea a faster second chance.

LifeLine combines shore-based detection, autonomous response and connected flotation equipment to shorten the time between an incident and lifesaving support.

| Today | With LifeLine |
| --- | --- |
| A person is spotted late | Continuous, intelligent monitoring |
| Help is dispatched manually | A rescue drone deploys immediately |
| Rescue can be delayed by conditions | A smart flotation device reaches the person first |

---

## Origin of the concept

### A card game sparked a real solution

- **Save lives** — the mission that started the idea
- **Edge AI** — on-board intelligence for fast decisions
- **No display needed** — designed for dependable autonomous operation

The aim is simple: detect a person in distress, deploy help, and support a rescue response in minutes.

---

## One product family, two environments

| LifeLine Shore | LifeLine Offshore |
| --- | --- |
| Beach lifeguard station | Autonomous rescue at sea |
| Continuous monitoring | Self-righting, always-ready buoy |
| Automated drone launch | Battery-powered operation |
| Shore power and data | Autonomous operation |
| Supports safer beaches | Deploys flotation and drone support |

**Same mission. Different conditions.**

---

## LifeLine Shore

### A connected beach-rescue station

- GNSS antenna for precise positioning
- RGB and thermal cameras for day, night and poor visibility
- LTE-M / NB-IoT / NB-NTN connectivity
- Autonomous rescue drone stored and charged on site
- Weatherproof shore power and data connection

Built to give lifeguards a persistent, connected view of the beach and a rapid first response.

---

## LifeLine Offshore

### Rescue capability where the shore cannot reach

- Self-righting buoy housing for demanding sea states
- Autonomous rescue drone with expandable capability
- Post-casualty deployment of flotation equipment
- Tethered smart inflatable cartridge
- GNSS + AIS / NTN-capable smart float

The offshore station is designed to stay upright, remain connected, and deliver support in rough conditions.

---

## How a rescue unfolds

1. **Detect** — cameras and sensors identify a possible survivor.
2. **Decide** — edge AI evaluates the event on board.
3. **Deploy** — the rescue drone launches with a smart flotation device.
4. **Support** — a beacon, strobe and tether help keep the survivor visible and afloat.
5. **Coordinate** — location and incident data assist the responding rescue team.

> From detection to flotation support in minutes.

---

## The hardest technical challenges

| Challenge | What LifeLine must prove |
| --- | --- |
| Survivor detection | Find people in real ocean conditions |
| Wind and sea-state flight | Stable autonomous drone operation in harsh weather |
| Smart inflatable cartridge | Reliable inflation, beacon and tether |
| Self-righting housing | Stay upright and functional in rough seas |
| Connectivity | Global, resilient LTE-M / NB-IoT / NB-NTN links |
| Regulation and safety | Meet maritime standards and save lives responsibly |

---

## Development roadmap

| Phase | Focus | Timeframe |
| --- | --- | --- |
| **P0** | Architecture and simulator | 0–2 months |
| **P1** | Bench proof of concept | 3–5 months |
| **P2** | Controlled-water demonstration | 6–9 months |
| **P3** | Shore pilot | 10–18 months |
| **P4** | Offshore alpha | 16–24 months |
| **P5** | Field trials | 24–36 months |
| **P6** | Industrialization and certification | 36–60 months |

---

## Indicative targets at scale

| Product | Target cost |
| --- | ---: |
| Smart cartridge | **€160–300** |
| LifeLine Shore station | **€13k–24k** |
| LifeLine Offshore station | **€25k–50k** |

*Targets are indicative and depend on final design, volume and supply chain.*

---

## Technology stack

- **On-board AI** — Jetson-class edge computing
- **Vision** — RGB and thermal cameras for day and night operation
- **Connectivity** — nRF9151 / Thingy:91 X with LTE-M, NB-IoT and NB-NTN
- **Flight** — PX4 flight control with Zephyr payload controller
- **Positioning** — GNSS, AIS and NTN-capable smart float

The technology choices prioritize autonomous operation, reliable communication and dependable rescue delivery.

---

# Prototype in months.

## **Product in years.**

### A serious engineering path from a card-game idea to autonomous maritime rescue.

**LIFELINE**<br>
*Detect. Deploy. Save lives.*
