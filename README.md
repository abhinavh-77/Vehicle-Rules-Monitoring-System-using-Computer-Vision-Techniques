Vehicle Rules Monitoring System Using Computer Vision Techniques

Vehicle Rules Monitoring System Using Computer Vision Techniques is a computer vision-based application that automatically detects traffic rule violations from recorded traffic videos. The system uses YOLO (You Only Look Once) for real-time vehicle detection and OpenCV for video processing and traffic rule analysis.

Developed as a final-year academic project.

📂 Project Structure
Vehicle-Rules-Monitoring-System-using-Computer-Vision-Techniques

backend/

.env
index.py
requirements.txt
README.md

dataset/

Traffic Videos
Sample Images

models/

best.pt (YOLO Trained Model)

src/

main.py
vehicle_detection.py
violation_detection.py
speed_detection.py
lane_detection.py
traffic_signal_detection.py
utils.py

output/

Processed Videos
Detected Violations
Screenshots

README.md

💡 Key Features
🚗 Vehicle Detection
Detects vehicles using YOLO
Supports Cars, Bikes, Buses and Trucks
Real-time object tracking
🚦 Traffic Rule Violation Detection
Red Light Violation Detection
Lane Violation Detection
Speed Violation Detection
Stop Line Crossing Detection
📊 Monitoring
Counts detected vehicles
Highlights violating vehicles
Displays violation type on screen
Saves processed output video
🛠️ Tech Stack

Programming Language: Python

Computer Vision: OpenCV

Object Detection: YOLO

Deep Learning Framework: Ultralytics YOLO

Libraries:

NumPy
OpenCV
Ultralytics
Imutils

IDE: Visual Studio Code

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/yourusername/Vehicle-Rules-Monitoring-System-using-Computer-Vision-Techniques.git
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Download the YOLO Model

Place the trained model (best.pt) inside the models/ folder.

4️⃣ Run the Project
python main.py
🔐 Environment Variables (.env)
MODEL_PATH=models/best.pt
VIDEO_PATH=dataset/input_video.mp4
OUTPUT_PATH=output/output_video.mp4
CONFIDENCE=0.5
🚀 Running the Application

Input Video:

dataset/input_video.mp4

Output Video:

output/output_video.mp4

Detected violations will be displayed in real time and saved in the output folder.

🧪 Testing Status

✅ Tested with multiple traffic videos

✅ Vehicle detection working successfully

✅ Lane violation detection tested

✅ Speed estimation verified

✅ Red light violation detection tested

✅ Output video generated successfully

🚧 Known Issues
Performance depends on video quality.
Occluded vehicles may reduce detection accuracy.
Speed estimation accuracy depends on camera calibration.
Night-time videos may reduce detection performance.
Heavy traffic can affect object tracking.
🧭 Future Enhancements
Live CCTV camera integration
Automatic number plate recognition (ANPR)
E-Challan generation system
Cloud-based traffic monitoring
AI-powered accident detection
Real-time traffic analytics dashboard
Multi-camera vehicle tracking
Mobile application for traffic authorities
🙏 Credits

Final Year Major Project

Developed by Haridasula Abhinav

Department of Computer Science and Engineering

Rise Krishna Sai Gandhi Group of Institutions

📧 Email

habhinavnaidu2005@gmail.coma
