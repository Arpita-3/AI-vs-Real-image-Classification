🎯 What is AI vs REAL?
AI vs REAL is a deep learning project that detects whether an uploaded image is real (camera-clicked) or AI-generated (created using tools like DALL·E, Midjourney, or Stable Diffusion).

With the rise of AI-generated media, distinguishing real images from synthetic ones is becoming harder. This project helps tackle that problem using a trained CNN (VGG16-based) model.

⚙️ How It Works
Uses VGG16, a popular pre-trained convolutional neural network, for feature extraction.

Custom classification layers are added on top to classify images into:

0 = Real

1 = AI-generated

The model is trained on labeled datasets of real and AI images.

The backend is powered by FastAPI for fast and easy image uploads and predictions.

💡 Use Cases
Fake image detection for media/news

Educational demonstrations of deep learning

Security and content verification tools

Tech showcase of image classification + FastAPI deployment

🖼️ What You Need to Do
Upload any .jpg or .png image.

The model will instantly tell you if the image is AI-generated or Real.

You can integrate this into web apps, mobile tools, or backend verification systems.

✅ Why This is Useful
In a world where AI can generate ultra-realistic images, tools like this are essential to:

Detect misinformation

Build trust in visual content

Demonstrate the power of AI responsibly

📦 Built With
Python 🐍

TensorFlow / Keras 🤖

VGG16 (Transfer Learning) 🧠

FastAPI 🚀

NumPy, scikit-learn, matplotlib 📊
