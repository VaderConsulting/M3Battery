# M3Battery

Arduino sketch that reads Tesla Model 3 pack state-of-charge from an EVTV controller serial stream (`SOC:` lines at 115200 baud) and drives red/orange/green LEDs for low, charging, and charged. Charge band is 15-80 percent. A SoftwareSerial port at 38400 baud prints status (banner names dave.robinson@westnet.com.au, 28 Feb 2022, v1.0). For Dave's EV battery-monitor bench setup.

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

## Attribution and provenance

Dave Robinson / VaderConsulting (banner in source, 28 Feb 2022). Imported from the Arduino archive. EVTV is the serial protocol source for SOC; this repo does not bundle EVTV firmware.

## License

MIT © 2026 VaderConsulting for Dave's code. See `LICENSE`.
