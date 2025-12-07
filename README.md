# BrewBot
BrewBot is a modular, user-friendly Home Assistant package designed to automate and enhance homebrewing workflows. Integrating BrewSpy/MQTT/iSpindel fermentation data with temperature-controlled brewing equipment, BrewBot empowers brewers to precisely manage multiple brews via a simple dashboard interface in Home Assistant

# 🍻 BrewBot - Home Assistant Brewing Automation

**BrewBot is a modular, user-friendly Home Assistant package designed to automate and enhance homebrewing workflows. Integrating BrewSpy/MQTT/iSpindel fermentation data with temperature-controlled brewing equipment, BrewBot empowers brewers to precisely manage multiple brews via a simple dashboard interface in Home Assistant.**

## 🚀 Features

- **Multi-Brew Management** - Save, edit, delete brew profiles (OG, temp, stages)
- **Live Fermentation Tracking** - BrewSpy, MQTT, iSpindel gravity/temp/ABV
- **Smart Stage Timers** - Ferment → Hop → Crash → Tap countdowns
- **Auto Temperature Control** - Heat belts/chillers via target temps
- **Single Command Interface** - `add IPA 1.040 20 7 0 7 28`
- **Zero YAML Complexity** - Drop-in package, works instantly

## 📦 Installation

1. **Download** `🍻BrewBot.yaml` to `packages/`
2. **Add script** to `scripts.yaml`
3. **Update BrewSpy token** (line 5)
4. **Restart HA** → BrewBot online!

## 🎛️ Usage
