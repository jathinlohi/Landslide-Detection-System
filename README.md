
# 🌍 Landslide Detection using Deep Learning

This project uses a fine-tuned Convolutional Neural Network (CNN) model to detect potential landslide-prone areas in satellite imagery. The model is trained on geospatial `.h5` image data and highlights regions with a high probability of landslides.

## Project Structure

- `Final Code.ipynb` – Main Jupyter Notebook for model execution and visualization.
- `model.h5` – Fine-tuned CNN model  
  🔗 [Download Model](https://drive.google.com/file/d/1-18rO-2g9DSd8mxEbyBQhJ7IafssbPTG/view?usp=sharing)
- Input: `.h5` satellite images
- Output: Masked regions or bounding boxes showing landslide-prone zones

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/landslide-detection
cd landslide-detection
```

### 2. Install Dependencies

Ensure Python ≥ 3.7 is installed.

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:

```bash
pip install tensorflow keras numpy matplotlib h5py opencv-python
```

### 3. Download the Model

Download and place the fine-tuned model in the project root directory.

🔗 [model.h5 Download Link](https://drive.google.com/file/d/1-18rO-2g9DSd8mxEbyBQhJ7IafssbPTG/view?usp=sharing)

---

## 🚀 How to Run

1. Open the Jupyter Notebook:

```bash
jupyter notebook "Final Code.ipynb"
```

2. Upload your `.h5` satellite image when prompted.
3. Run all cells to:
   - Load the model
   - Preprocess input
   - Predict landslide regions
   - Visualize output

---

## Model Overview

- **Model Type:** Custom CNN
- **Input Format:** `.h5` geospatial images
- **Output:** Highlighted landslide-prone areas
- **Accuracy:** ~98%
- **Interface:** GUI built using `Tkinter`

---

## Dataset Used

- **Name:** Landslide4Sense
- **Region:** Southeast Asia (Western Ghats included)
- **Format:** `.h5` satellite image files with labeled landslides

---

## Features

- ✅ Simple drag-and-drop GUI for image input
- ✅ High-accuracy detection (98%)
- ✅ Bounding box/mask visualization
- ✅ Configurable threshold (default > 60%)

---

## Future Work

- Add batch processing support  
- Web-based frontend (Streamlit or Flask)  
- Integration with GIS tools  
- REST API deployment

