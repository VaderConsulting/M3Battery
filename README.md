# M3Battery

Arduino sketch that reads Tesla Model 3 pack SOC from an EVTV serial stream and drives charge-status LEDs. It parses `SOC:` lines at 115200 baud and lights red, orange, or green for the 15-80 percent charge band. A SoftwareSerial port at 38400 baud prints status for Dave's EV battery-monitor bench setup.

Working copy from my Historical Dev folder.

**Source last updated:** 2022-03-03
**Language:** C++ / Arduino
**Target:** Arduino with SoftwareSerial on pins 2/3 and LEDs on 4/5/6
**Output:** Arduino sketch

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `M3Battery` | C++ / Arduino | sketch | Parse EVTV SOC serial and drive charge-status LEDs |

## How to open

Open `M3Battery.ino` in the Arduino IDE. An `.ino.example` copy is alongside the sketch.

## Requirements

- Arduino IDE

## Attribution and provenance

Original work by Dave Robinson / VaderConsulting for a personal EVTV Model 3 battery monitor bench. No third-party sketch attribution markers were identified in this tree.

## License

MIT. See `LICENSE` if present; otherwise treat as MIT VaderConsulting 2026 for Dave's code.
