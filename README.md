<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body style="font-family:Arial, sans-serif; line-height:1.6; margin: 2rem;">

  <h1>🤟 Gesture Recognition using Deep Learning</h1>

  <h2>📚 Overview</h2>
  <p>
    This project focuses on <strong>gesture recognition</strong> using deep learning models to interpret hand gestures, particularly from American Sign Language (ASL). It uses computer vision techniques and neural networks to classify hand signs from image inputs.
  </p>
  <p>
    The models are trained and tested on the <strong>Sign Language MNIST</strong> dataset.
  </p>
  <p>
    We’ve provided two implementations:
    <ul>
      <li>A traditional <strong>OpenCV-based ROI detector</strong> (<code>ROIinOpenCV.py</code>)</li>
      <li>A <strong>PyTorch-based deep learning model</strong> (<code>sign_language_pytorch.ipynb</code>)</li>
    </ul>
  </p>

  <h2>🧰 Dependencies</h2>
  <p>Make sure to install the following dependencies before running the project:</p>
  <ul>
    <li>TensorFlow</li>
    <li>Keras</li>
    <li>OpenCV</li>
    <li>PyTorch (for PyTorch version)</li>
  </ul>
  <p>Install them using:</p>
  <pre><code>pip install tensorflow keras opencv-python torch torchvision</code></pre>

  <h2>📁 Dataset</h2>
  <p>We use the <a href="https://www.kaggle.com/datamunge/sign-language-mnist" target="_blank">Sign Language MNIST dataset</a>, which consists of labeled grayscale images of hand gestures representing alphabets in ASL.</p>
  <ul>
    <li>Training set: 27,455 examples</li>
    <li>Test set: 7,172 examples</li>
    <li>Image size: 28x28 pixels</li>
  </ul>

  <h2>🛠️ Tools Used</h2>
  <ul>
    <li><strong>Google Colab</strong> (Recommended for training the deep learning model)</li>
    <li><strong>Python</strong></li>
    <li><strong>OpenCV</strong> for image preprocessing and hand ROI extraction</li>
  </ul>

  <h2>🚀 How to Run</h2>

  <h3>▶️ Option 1: OpenCV-based ROI Detection</h3>
  <p>Run the following file locally:</p>
  <pre><code>python ROIinOpenCV.py</code></pre>
  <p>This opens your webcam and allows you to detect hand gestures in a predefined Region of Interest (ROI) using OpenCV.</p>

  <h3>▶️ Option 2: PyTorch Model (Colab-friendly)</h3>
  <p>Open and run this notebook on Google Colab:</p>
  <p><code>sign_language_pytorch.ipynb</code></p>
  <p>It includes:</p>
  <ul>
    <li>Data preprocessing</li>
    <li>Model architecture</li>
    <li>Training and evaluation</li>
  </ul>

  <h2>📈 Future Improvements</h2>
  <ul>
    <li>Integrate real-time webcam-based recognition with PyTorch models</li>
    <li>Expand dataset to include dynamic gestures (e.g., gestures involving motion)</li>
    <li>Add GUI or web-based interface for live gesture recognition</li>
  </ul>

</body>
</html>
