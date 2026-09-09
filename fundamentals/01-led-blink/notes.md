# 01 - LED Blink

## What it proves
- pinMode() — sets a pin to OUTPUT mode
- digitalWrite() — sends HIGH/LOW (voltage) to a pin
- delay() — timing control (in milliseconds)
- loop() runs forever, so ON→OFF→ON repeats continuously → looks like blinking

## Circuit
- LED (anode) → 220Ω resistor → Arduino pin 13
- LED (cathode) → GND
- (used a 2k resistor here — LED is dimmer, but circuit works fine)

## Status
Done — LED blink working in Wokwi simulation.