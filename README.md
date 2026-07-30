# DIY-Drone with custom flight controller
## Disclaimer
This is a personal learning project.
The goal is to get more hands-on experience with embedded systems and control theory.

### Current Status

The project is currently in the hardware integration phase.
The repository currently focuses on documenting the system architecture,
development roadmap and implementation plan.

Source code will be added incrementally as individual modules are implemented
and tested.

---

## Project Stages

### Stage 1 - Indoor Drone controlled via Bluetooth

#### Module Testing
- [ ] Test MPU9250 (IMU)
- [ ] Test HC-05 (communication)
- [ ] Test motors with ESC

#### Integration Testing
- [ ] Test MPU9250 + HC-05 communication
- [ ] Test power system
- [ ] Perform full system bench test

#### Mechanical Development
- [ ] Design drone frame
- [ ] Print frame prototype
- [ ] Validate mounting and layout

#### Full Assembly
- [ ] Assemble electronics and frame
- [ ] Verify assembly

#### Flight Controller
- [ ] Implement MPU9250 driver
- [ ] Implement HC-05 driver
- [ ] Develop sensor fusion algorithm
- [ ] Implement PID controller
- [ ] Develop motor control logic
- [ ] Achieve stable flight

---

### Stage 2 - Outdoor Drone controlled via RC transmitter

---

### Stage 3 - Camera Upgrade

---

## Hardware
- Microcontroller: STM32F411
- IMU: MPU9250
- Communication: HC-05

---

## Repository Structure

---

## Progress Log

### Update 1
- Created this repository
- Structured and documented the project plan
- Defined development stages and tasks
