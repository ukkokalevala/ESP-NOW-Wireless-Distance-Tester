Project Briefing: ESP-NOW Wireless Distance Tester
This project uses two ESP32-C3 boards to measure wireless communication range using ESP-NOW — a fast, lightweight, peer-to-peer protocol that doesn’t require WiFi, routers, or internet.
How it Works
• Sender ESP transmits a small packet every second.
• Receiver ESP listens for the packets and reads the RSSI (signal strength) of each one.
• The receiver displays:
o Packet number
o RSSI value (signal strength)
o Signal percentage
o A live signal bar graph on the OLED display
What It Shows
• Strong signal close to the sender
• Signal drops as you walk away
• Low or no signal when you’re out of range
It’s a simple, visual way to test the reliability, distance, and stability of ESP-NOW wireless communication.
Why It's Useful
• Helps find the best ESP placement for real projects
• Demonstrates real-time wireless performance
• Great for learning about RSSI and link quality
• Works indoors or outdoors with no WiFi setup
Hardware Used
• 2× ESP32-C3 boards
• 1× 128×64 OLED display (SSD1306)
• Standard jumper wires
