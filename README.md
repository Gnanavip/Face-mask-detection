# 🛡️ Face Mask Detection

A **real-time AI-powered face mask detection system** built using **Python, OpenCV, TensorFlow/Keras, and MobileNetV2**.  
This project detects whether a person is wearing a face mask in live video streams or images, helping monitor public mask compliance during situations like COVID-19.

---

## 📌 Features
- Real-time face mask detection using a webcam.
- Trained deep learning model with **MobileNetV2** for high accuracy.
- Works with images, video files, or live streams.
- Lightweight model for faster inference.
- Easy-to-use and well-documented.

---

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries & Frameworks:** OpenCV, TensorFlow, Keras, NumPy, imutils
- **Model Architecture:** MobileNetV2 (Pre-trained on ImageNet)
- **Tools:** Jupyter Notebook, Git

---

## 📂 Project Structure
##  Dataset
The model was trained using:
- **With Mask** and **Without Mask** images.
- Data augmentation techniques to improve generalization.
- Pre-processing with OpenCV and NumPy.

You can download similar datasets from:
- [Kaggle - Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)

---

##  Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/Gnanavip/Face-mask-detection
   cd Face-Mask-Detection
   ```
   ---
2. **Install Dependencies**
   ```bash
    pip install -r requirements.txt
   ```

   ---

 3. **Run detection**
    ```bash
    python detect_mask_image.py --image examples/example_01.png
    python detect_mask_video.py
    ```
    ---

4. **Model Training**
   ```bash
   python train_mask_detector.py --dataset dataset
   ```


