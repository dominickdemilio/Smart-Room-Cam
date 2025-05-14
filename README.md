# Smart Room Cam

A Raspberry Pi-based security camera with live streaming, motion detection, and AI-based object recognition.

## Features
- Live video streaming via web browser
- Modular design for future AI features (human detection, face recognition)
- Built with Python, OpenCV, and Flask

## Getting Started
1. Clone the repository: `git clone https://github.com/dominickdemilio/Smart-Room-Cam.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`
4. Open your browser and go to `http://<raspberry-pi-ip>:5000`

## Next Steps
Once live streaming is solid:
- ✅ Add motion detection in `motion_detector.py`
- ✅ Count humans using OpenCV or a pretrained model in `recognizer.py`
- ✅ Dockerize it later if you want easy deployment
- ✅ Add authentication if you're exposing the stream remotely