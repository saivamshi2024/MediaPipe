
# 🧠📦 Object Detection using MediaPipe – Cup, Shoe, Camera

This project uses **Google's MediaPipe framework** to detect objects like **cup, shoe, and camera** in real-time and draw **bounding boxes** around them. The goal is to demonstrate lightweight and efficient object tracking using a webcam or image input.

---

## 🚀 Project Highlights

- 🧩 Implemented object detection using **MediaPipe Solutions**
- 📦 Draws bounding boxes around objects (cup, shoe, camera)
- 🖥️ Real-time video stream (via webcam) or image input
- 💡 Lightweight & fast – suitable for real-time applications

---

## 🛠 Tech Stack

| Tool / Library   | Description                        |
|------------------|------------------------------------|
| **Python**       | Programming language               |
| **MediaPipe**    | Object detection & tracking        |
| **OpenCV**       | Video and image processing         |
| **NumPy**        | Array operations (if required)     |

---

## 📂 File Structure



```

mediapipe-object-detection/
├── main.py                # Main Python script with MediaPipe logic
├── utils/                 # Helper functions (drawing, preprocessing)
├── samples/               # Sample images or videos (optional)
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies

````

---

## 🔧 How to Run the Project

```bash
# 1. Clone the repository
git clone https://github.com/your-username/mediapipe-object-detection.git
cd mediapipe-object-detection

# 2. (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# 3. Install dependencies
pip install mediapipe opencv-python

# 4. Run the script
python main.py
````

> Make sure your webcam is connected if using real-time detection.

---

## 🖼️ Output Preview

> *(Add sample images with bounding boxes here if available)*
> Example:
>
> * ✅ Cup Detected
> * ✅ Shoe Detected
> * ✅ Camera Detected

---

## 📌 Notes

* This is a demo project to showcase object bounding box capabilities using MediaPipe.
* Accuracy may vary depending on object size, angle, and lighting.
* Can be extended to detect more objects or use a custom trained model.

---

## 🎯 Future Scope

* Train a custom object detection model and integrate with MediaPipe
* Add audio feedback or labels for each detected object
* Deploy as a desktop or mobile app

---




✅ Cup Detected

✅ Shoe Detected

✅ Camera Detected

