## Day 1 — [15/08/26]
- Project: repo created, folder structure setup (docs, src, data)
- Understood well: Wokwi platform basics, repo structure planning
- Tomorrow: Wokwi board setup, sensor wiring

## Day 2 — [16/08/26]
- Wokwi setup complete, ESP32 + MPU6050 wired (VCC→3V3, GND→GND, SCL→D22, SDA→D21)
- Sensor reading working — live X/Y/Z values in Serial Monitor
- Added hardware learning roadmap (10-day plan) to README
- Added wiring and output screenshots to docs folder
- Understood well: setup()/loop() structure, Serial Monitor basics, I2C wiring pattern
- Tomorrow: number systems (hex/binary) — first roadmap topic

## Day 3 — [17/08/26]
- Coding C (roadmap): number systems — decimal/hex conversion (6/6 correct)
- Project: modified code for CSV output, collected 20 normal-state sensor readings, saved to data/normal-readings.csv
- Understood well: number system division method, definite integral limits
- Tomorrow: bitwise operators (roadmap Day 4), continue project — plan for fault-state data

## Day 4 — [18/08/26]
- Coding C (roadmap): bitwise operators (<<, >>, |, &) — explains sensor byte-combining code
- Project: fixed empty CSV bug from Day 3, simulated and collected fault-state sensor data
- Understood well: bitwise shift logic
- Tomorrow: pointers basics (roadmap Day 5), continue project — compare normal vs fault data

## Day 5 – [19/08/26]
- Project: started threshold-based fault classifier (normal vs fault comparison), paused mid-build to strengthen fundamentals (file handling, loops, comparison logic) first — building from scratch, not copy-pasted
- Tomorrow: revisit file handling + loops fundamentals, then resume classifier build