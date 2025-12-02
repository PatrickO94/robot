# robot
Concepts for a robot enabled by AI
- Belop: Basic Expressive Language-Operated Pal
- Inspired by AIBI
- goals/concept/ideas of the project:
    1. Use a Screen to create expressive visuals
    2. ESP or similar to create a hardware/software Interface between screen, servos, etc. and AI issued commands
    3. Use of a small efficient LLM to create commands to control Belops behavior, either through local means or transmitted from a service running on a PC or server in the Network
    4. Include servos/motors for basic animation and movement (wheels? arms? Movement of the head will be essential for expressive abilities). For this basic project the hard limit of the number of motors/servos will be a total of five, but the goal is to use 2-3.
    5. Mic for communication, Belop can talk via text on screen.
    6. Design the body for FDM 3D-Printing in PLA
    7. Optional: Battery for wireless use, speakers for giving Belop a voice

- Ideas:
    - Use an ESP with Oled and WiFi (already owned) to control the robot and enable expressions, use WiFi for controls. This means Belop's 'mind' will exist as a WiFi service
    - Or: Use Raspberry Pi with an AI-shield to run and control everything locally on the bot. This requires more space and a fitting screen. Could be easier to design for 3D printing, since the body will have to be bulkier anyway. Will require more initial investment in not yet owned hardware (and PLA I guess).
