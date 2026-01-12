# Cat Toy Robot

**GitHub Repository:** [aachuu1/Cat-Toy-Robot](https://github.com/aachuu1/Cat-Toy-Robot)

## General Description

The project consists of a robot designed to play with cats, controlled via phone. 

### Key Functionalities
- Throwing different toys that the cat can play with
- Dispensing treats
- Movement
- Phone control 
- Obstacle avoidance
- Cat detection

## Bill of Materials

| Component | Purpose |
|-----------|---------|
| Arduino Uno (or Mega) | Main microcontroller |
| Motor driver (L298N or similar) | Control servos and motors |
| Bluetooth module (HC-05/HC-06) or WiFi module (ESP8266/ESP32) | Phone control |
| Power supply | Batteries or power bank |
| Chassis/casing | Robot structure |
| Wheels | Movement (at least 2, plus a free wheel/ball caster) |
| Breadboard and jumper wires | Connections |
| Resistors | Various circuits |
| LEDs | Visual indicators (optional) |
| Buzzer | Sound alerts when throwing toys/dispensing treats |
| Ultrasonic sensor (HC-SR04) | Obstacle avoidance |
| IR sensor | Cat detection |

## Learning Resources

### Tutorial References

- **Robot Movement:** [Arduino Robot Car Tutorial](https://www.youtube.com/watch?v=Ey4xoG970Go)
- **Phone Control:** [Bluetooth Control Tutorial](https://www.youtube.com/watch?v=pwTtignuEHc)
- **Toy Throwing Mechanism:** [Catapult Mechanism](https://www.youtube.com/watch?v=B2lwaLmHDEI)
- **Treats Dispenser:** [Dispenser Tutorial](https://www.youtube.com/watch?v=dUB3-fEq5ss)

For additional functionalities, I will reference course materials and lab documentation.

## Planned Modifications

- Miniaturize the treats dispenser design
- Modify dispenser to release multiple treats at once
- Custom integration of all subsystems

## Project Questions

### Q1:
The system boundary includes the robot hardware,control software, sensors and the phone application used to control it.

### Q2:
The intelligence lives on the Arduino microcontroller, with control commands coming from the phone.

### Q3: 
The hardest technical problem is integrating movement, sensors, toy throwing, and treat dispensing into one system.

### Q4:
The minimum demo is a robot that can move, be controlled from a phone, and perform at least one action such as throwing a toy or dispensing treats.

### Q5: 
This is not just a tutorial because it combines multiple functionalities, requires design decisions, and involves custom modifications.


## Contributors

[Add your name/contributors here]
