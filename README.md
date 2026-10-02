# Dynamic HVAC Control Card

![Dynamic HVAC Control](brand/logo.png)

A high-DPI Lovelace thermostat UI card for Home Assistant with dual-knob arc sliders, live Delta-T duct telemetry, and blower indicator.

## Features
- **Dual-Arc Sliders:** Interactive heat/cool range setpoints with emerald comfort deadband.
- **Dynamic Thermal Telemetry:** Supply & Return air probes with real-time Delta-T drop/rise status.
- **Blower Control:** Direct fan switch and airflow visualizer.
- **Fail-Safe Styling:** Smooth antialiased SVG dial, theme variable support for Light & Dark mode.

## Installation via HACS
1. Open **HACS** > **Frontend** > **Custom repositories**.
2. Add `https://github.com/Tinkergnome621/dynamic-hvac-control-card` as a **Lovelace** repository.
3. Click **Install**.

## Lovelace Configuration
```yaml
type: custom:dynamic-hvac-control-card
entity: climate.dynamic_hvac_control
name: Living Room Climate
```
