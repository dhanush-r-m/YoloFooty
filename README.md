⚽️ YoloFooty - Real-Time Football Analysis with YOLO
YoloFooty is a real-time football (soccer) analysis tool built with Python, OpenCV, and YOLO object detection. It automatically detects and tracks players and the ball from match footage, providing visual overlays, stats, and insights to enhance game analysis and coaching.

🚀 Features
✅ Real-Time Detection: Detects players and the ball in live or recorded video.
✅ Visual Tracking: Shows bounding boxes and labels for easy understanding.
✅ Custom Video Input: Works with your own football match videos.
✅ Trajectory & Heatmaps: (Optional) Extend to show movement paths and heatmaps.
✅ Modular & Extensible: Easy to customize and expand for deeper analysis.

🛠️ Tech Stack
Python
OpenCV
YOLOv8 (or your chosen YOLO version)
PyTorch

📥 Installation
bash
# Clone the repository
git clone https://github.com/dhanush-r-m/YoloFooty.git
cd YoloFooty

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Download YOLO weights (if not included)
# For example, using YOLOv8:
# You can download from official YOLOv8 repo or use pretrained weights
🎥 Usage
1️⃣ Place your match video in the input_videos/ folder.
2️⃣ Run the detection script:

bash
python detect.py --source input_videos/match.mp4 --weights yolov8.pt --conf 0.5

3️⃣ View results:
Output video with bounding boxes will be saved in runs/detect/.
Check the frames or videos to analyze player and ball tracking.

📸 Input

🏷️ Output

📌 To Do
 Add heatmaps and player trajectories
 Integrate stats dashboard
 Support live webcam streams
 Improve detection accuracy for crowded scenes

📄 License
This project is licensed under the MIT License.

🤝 Contributions
Pull requests and suggestions are welcome! Let’s make football analysis smarter together ⚽✨

✍️ Author
Dhanush Moolemane
• GitHub (https://github.com/dhanush-r-m)
• LinkedIn(in/dhanush-moolemane-b690562b0)

