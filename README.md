# 🍻 BrewBot - Home Assistant Brewing Automation

**BrewBot is a modular, user-friendly Home Assistant package designed to automate and enhance homebrewing workflows. Integrating BrewSpy/MQTT/iSpindel fermentation data with temperature-controlled brewing equipment, BrewBot empowers brewers to precisely manage multiple brews via a simple dashboard interface in Home Assistant.**

[![GitHub stars](https://img.shields.io/github/stars/JonCastaway/BrewBot)](https://github.com/YOURUSERNAME/BrewBot)
[![HACS](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/hacs/integration)

## 🚀 Features

- **Multi-Brew Profiles** - Save/load/edit/delete recipes (OG, temp, stages)
- **Live Fermentation Data** - BrewSpy gravity, temp, ABV, battery
- **Smart Stage Tracking** - Ferment → Hop → Crash → Tap timers
- **Temperature Automation** - Heat belts via target temps
- **One-Line Commands** - `add IPA 1.040 20 7 0 7 28`
- **Zero YAML Complexity** - Drop-in package deployment

## 📦 Quick Install (3 mins)

### 1. **Add BrewSpy Token to secrets.yaml**
