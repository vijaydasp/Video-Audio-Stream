# Video-Audio-Stream

## 🚀 Project Overview

**Video-Audio-Stream** is a real-time video and audio streaming web application built with **Flask**, **OpenCV**, and **PyAudio**. It captures live webcam video and microphone audio and streams them to a web interface via HTTP.

This project serves as a foundation for remote monitoring, surveillance, or communication systems.

---

## 📌 Features

* 🔊 Real-time **microphone audio streaming** via PyAudio.
* 🎥 Live **webcam video feed** using OpenCV.
* 🌐 Web interface powered by Flask.
* 🎞️ MJPEG streaming for video.
* 🔁 WAV stream format for raw audio.

---

## ⚙️ Technologies Used

* Python 3
* Flask
* OpenCV (cv2)
* PyAudio
* HTML (for frontend UI)

---

## 🛠️ Installation

```bash
git clone https://github.com/vijaydasp/Video-Audio-Stream.git
cd Video-Audio-Stream
pip install -r requirements.txt
python app.py
```

---

## 🔧 Usage

1. Run the application with `python app.py`
2. Open a browser and go to `http://localhost:5000`
3. Video stream available at `/video_feed`
4. Audio stream available at `/audio`

---

## 📂 Project Structure

```
Video-Audio-Stream/
├── templates/
│   └── index.html         # Web interface template
├── app.py                 # Main Flask application

```

---

## 📧 Contact

**Developer:** Vijay Das

**LinkedIn:** [vijaydasp](https://www.linkedin.com/in/vijay-das-p-a42068283?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BxyyRRfIGRJ%2BYk8u1yhtC9g%3D%3D)

---

## 💡 Future Improvements

* WebRTC support for lower latency.
* Audio-video synchronization.
* Multi-user streaming with authentication.
* Integration with cloud storage/recording.

---
