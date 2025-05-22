#🚗 Traffic Violation Detection System 🚦

This project detects traffic violations such as speeding, red light running, and illegal turns using YOLOv3 and OpenCV. The system processes live CCTV footage with over 90% accuracy, enhancing road safety and reducing traffic congestion.


🔑 Key Features
Real-Time Detection: Monitors vehicles and identifies violations from live video feeds.
Speed Monitoring: Tracks vehicle speeds and flags speed violations exceeding a threshold (e.g., 2000 pixels/sec).
Accident Detection: Monitors motorbike falls and detects potential accidents based on vehicle aspect ratio and movement patterns.
Vehicle Line Crossing: Detects vehicles crossing a predefined line and counts violations.
🛠 Technologies Used
YOLOv3: Object detection for recognizing vehicles like cars, motorbikes, buses, and trucks.
OpenCV: Handles image processing for detecting objects, tracking positions, and monitoring speed.
Python: Core programming language for integrating detection, violation checks, and vehicle tracking.


📁 Project Structure
bash
Copy code

├── src/                # Source code

├── models/             # YOLOv3 weights and config files

├── data/               # Input videos/images for testing

├── results/            # Output videos/images with detections

├── notebooks/          # Jupyter notebooks for experimentation

└── README.md           # Project documentation
📊 Sample Output
Motorbike Accident Detection:

Speed Violation Detection:

⚙ Parameters Adjustments
Speed Limit: Set in pixels/second, default is 2000.
Frame Rate: Adjustable via the fps variable.
Vehicle Tracking: Line crossing detection is triggered when vehicles cross line_y = 400.
📜 License
This project is licensed under the MIT License.


