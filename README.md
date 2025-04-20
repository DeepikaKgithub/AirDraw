# 🎨 AirDraw

Ever wanted to draw your imagination by waving your finger in the air?  
**AirDraw** turns that dream into reality by allowing you to draw in the air using just your finger — no stylus, no touchscreen, just motion and magic!

## ✨ What is AirDraw?

AirDraw is a real-time hand gesture-based drawing tool that captures the motion of your index finger using computer vision and translates it into digital strokes on a canvas. It uses **MediaPipe**, **OpenCV**, and **Python** to track hand landmarks and render them as drawings.

## 🧠 Why AirDraw?

AirDraw opens doors for:
- People with hearing/speaking impairments as a communication tool.
- Reducing dependency on physical interfaces like keyboards or pens.
- Enhancing interactive learning in education.
- Innovative applications in therapy, virtual games like Pictionary, and air-touch interfaces.

## 🎯 Project Aim

To build an air-based canvas that lets users draw anything using their finger gestures, completely contactless.

## 🛠 Tools & Libraries Used

- **Python**
- **NumPy**
- **OpenCV**
- **MediaPipe**

## 🚀 Features

- 🖐 **Hand Gesture Recognition** using MediaPipe.
- 🎨 **Multi-color Drawing** — change colors using specific gestures.
- 🧼 **Canvas Control** — clear the screen and choose colors with hand signs.
- 🖼 **Real-time Visualization** — see your webcam and the drawing canvas live.

## ⚙️ How It Works

1. Captures frames from your webcam and converts them to RGB.
2. Detects hand landmarks (especially the index finger) using MediaPipe.
3. Tracks finger movement and stores its coordinates across frames.
4. Renders the drawing on a digital canvas in real-time.
5. Supports gesture-based commands for color switching and canvas control.

## 🗺 Roadmap

- Initialize hand tracking (MediaPipe).
- Detect index finger tip coordinates.
- Store tracked points frame-by-frame.
- Display color buttons and detect color switch gestures.
- Draw on a virtual canvas in sync with finger motion.

## 🌍 Future Scope

- **Air Touch Panels**: Control your gadgets with hand waves — no physical contact.
- **Virtual Pictionary**: Play games like Pictionary with friends, no pen/paper needed!
- **Therapeutic Applications**: Stress-relief painting and physical therapy exercises.
- **Educational Tools**: Interactive 3D drawing for subjects like geometry or physics.

---

> Thank you for checking out **AirDraw**! ✨  

