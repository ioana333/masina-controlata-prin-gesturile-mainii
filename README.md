cat > README.md <<'EOF'
# Hand-Gesture Controlled Car

This project describes building a gesture-controlled vehicle prototype using an MPU6050 sensor and NRF24L01 modules for wireless communication.

## Project Goal
The project aims to implement an intuitive control system based on natural hand movements.

## Key Features
- **Motion detection:** Use the MPU6050 sensor to convert hand movements into direction commands (forward, backward, left, right).
- **Command transmission:** Wireless communication between the controller and the vehicle using NRF24L01 modules.
- **Vehicle response:** Precise control of DC motors via the L298N driver for steering and motion.

## Tools Used

### Hardware
- 2 Arduino Nano boards
- 1 MPU6050 sensor
- 2 NRF24L01 modules
- 4 DC motors
- 1 L298N driver
- Vehicle chassis
- Power sources (batteries)

### Software
- **Arduino IDE:** Programming and uploading code to the Arduino boards.
- **Libraries used:**
  - `Wire.h`
  - `MPU6050.h`
  - `RF24.h`

## Unresolved Issues
- No proximity sensors for obstacle detection.
- Limited precision when turning.
- Interface may be difficult to use for people with complex motor impairments.
- No AI integration yet for autonomous navigation or adaptive control.

## How to Use
1. Insert 6 AA batteries into the vehicle’s holder and switch it ON.
2. Strap the remote to your hand and turn on its switch.
3. Control the vehicle with your hand movements to test functionality.

## Results
- Fast response (100–200 ms) from gesture to vehicle movement.
- Stable communication in open space up to ~15 meters.
- Battery life: ~45 minutes for the vehicle and ~2 hours for the remote.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request with improvement suggestions.

## Resources
- Full documentation and source code are available on GitHub: https://github.com/ioana333/Masina-controlata-prin-gesturile-mainii
EOF
