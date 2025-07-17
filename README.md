IR Sensor-Based Smart Glass for the Visually Impaired

This project is a cost-effective, compact assistive technology designed to help visually impaired individuals detect nearby obstacles using IR sensors. It generates real-time alerts via sound or vibration to guide safe navigation.

📌 Features

- IR sensor-based obstacle detection
- No microcontroller/Arduino used – fully hardware-based
- Real-time alert via buzzer or vibration motor
- Compact and wearable design (integrated into glasses)
- Low-power operation with rechargeable battery

🧩 Components Used

| Component                    | Quantity  | Purpose                                      |
| ---------------------------- | --------- | -------------------------------------------- |
| Spectacle Frame              | 1         | Holds all the components in place            |
| IR Proximity Sensor          | 1–3       | Detects nearby obstacles                     |
| Buzzer / Vibration Motor     | 1         | Alerts user when obstacle is detected        |
| NE555 Timer IC (Optional)    | 1         | Generates signal for buzzer/vibration        |
| Resistors                    | Few       | Used for current limiting or threshold setup |
| Capacitors                   | Few       | Used for timing or noise filtering           |
| Switch (Slide/Push Button)   | 1         | Turns the device ON/OFF                      |
| Battery (Li-Po or 9V)        | 1         | Powers the circuit                           |
| PCB / Perfboard / Breadboard | 1         | Mounting and connecting the components       |
| Wires                        | As needed | For making the electrical connections        |
| Glue / Gel Tape              | As needed | For fixing sensors and modules to the frame  |



⚙️ How It Works

1. IR sensor emits infrared light.
2. If an obstacle is nearby, reflected IR light is detected.
3. The analog signal is processed by a comparator or NE555 circuit.
4. Based on proximity, a buzzer or vibration motor is triggered to alert the user.

🛠️ Circuit Diagram

file:///C:/Users/Nagameenashree/OneDrive/Desktop/visually%20imapaired/Smart%20Glass%20Circuit%20Diagram%20pdf%20(3).pdf

📝 How to Build

1. Connect IR sensor output to comparator or NE555 IC.
2. Connect output to buzzer or vibration motor.
3. Power the system using a small Li-Po battery.
4. Mount components on a spectacle frame.
5. Turn on the switch and test the detection.

🤝 Contributors

- Nagameenashree
- Sashmitha
- Priyadharshini(https://github.com/Priyadharshini2409?tab=projects)



