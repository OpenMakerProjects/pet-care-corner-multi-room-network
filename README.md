# Pet Care Corner Multi-Room Network

Build a smart home prototype that uses door sensor, OLED display to coordinate several wireless nodes. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 88 |
| Category | Smart Home |
| Platform | ESP8266 |
| Difficulty | Beginner |
| Estimated build time | 20 hours |
| Connectivity | MQTT |
| Core components | door sensor, OLED display |
| Control mode | telemetry |

## Repository layout

- `firmware/pet-care-corner-multi-room-network/pet-care-corner-multi-room-network.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/pet-care-corner-multi-room-network/pet-care-corner-multi-room-network.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **ESP8266**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Multi-Room Network demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
