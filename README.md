# 🦷 Dental Caries Detection using YOLOv12

This project performs **automated detection of dental caries (cavities)** using a custom-trained **YOLOv12** object detection model. The model was trained on a labeled dataset from **Roboflow** and is designed to identify caries in dental-related images.

---

## 📂 Project Structure

```bash
📁 Dental-Caries-Detection/
├── best.pt               # Trained YOLOv12 weights (model file)
├── im.jpeg               # Input image to analyze
├── output.jpg            # Output image with caries detection (auto-generated)
├── detect_teeth.py       # Python script for YOLOv12 inference
├── requirements.txt      # List of Python dependencies
└── README.md             # Project documentation
```

---

## 🛠️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Slayer9966/DentalDiseaseDetection.git
cd DentalDiseaseDetection
```

### 2. Install Required Packages

```bash
pip install -r requirements.txt
```



### 3. Add Files

- Place your trained YOLOv12 model (`best.pt`) in the project folder.
- Add an image to detect caries (e.g., `im.jpeg`).

---

### 4. Run Detection

by running the notebook

This script will:
- Load `best.pt`
- Perform caries detection on `im.jpeg`
- Save the annotated image as `output.jpg`

---

## 🧠 About the Model

- **Model Architecture:** YOLOv12 (Ultralytics)
- **Trained On:** A custom dental dataset from [Roboflow](https://roboflow.com/)
- **Target Class:** `caries` (dental cavities)
- **Output:** Bounding boxes highlighting caries regions

---

## ✅ Example

> Input:  
> `im.jpeg` (image containing teeth)  
>
> Output:  
> `output.jpg` with caries annotated using bounding boxes

---

## 📃 License

This project is licensed under the [MIT License](https://github.com/Slayer9966/DentalDiseaseDetection/blob/main/LICENSE).

---

## 🙌 Acknowledgments

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- [Roboflow](https://roboflow.com/) for dataset hosting and preprocessing tools

---

**Syed Muhammad Faizan Ali**  
📍 Islamabad, Pakistan  
📧 faizandev666@gmail.com  
🔗 [GitHub](https://github.com/Slayer9966) | [LinkedIn](https://www.linkedin.com/in/faizan-ali-7b4275297/)
📢 If you find this project helpful or use it in your work, please consider giving it a ⭐ or letting me know via email or GitHub issues!
