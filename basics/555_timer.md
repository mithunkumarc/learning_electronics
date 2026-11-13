#### blinking led example
- threshold and trigger connected to comparator and then to s-r flip flop
- capacitor is connected to threshold, trigger and power supply
- The (timing) capacitor is connected to the Threshold pin (Pin 6), the Trigger pin (Pin 2), and Ground (GND)— not directly to the power supply(+ pin).
- Capacitor charges from the power supply through two external resistors R1 and R2.

- threshold and trigger just measure voltage, they don't play role in charging or discharging capacitor
- when capacitor charges and if voltage go above 2/3 vcc threshold pin set to 1
- when capacitor discharges and if voltage go below 1/3 vcc trigger pin set to 1
- threshold and trigger connected to s-r flip flop and output is connected to led
- when capacitor charge, led is on , and when it discharge, led is off


• Sensing: Threshold (Pin 6) and Trigger (Pin 2) are high-impedance inputs that only monitor capacitor voltage without affecting charge/discharge.
• Capacitor Wiring: The capacitor is connected between Pins 2 & 6 and Ground (it charges from VCC through resistors).

- capacitor upper plate is always positive and lower plate negative, while discharging positive page pulls electrons from ground through pin 7
- while discharging negative plate loses electrons to ground outside IC directly.

-website : https://www.instructables.com/Flashing-LED-using-555-Timer/
