## Vehicle Detection using DETR, Faster R-CNN, and YOLOv11

This repository provides implementations of **DETR, Faster R-CNN, and YOLOv11** for the vehicle detection task. The models have been tested and can run on **Kaggle**.

For more details about the project and results, refer to **FINAL_CV_REPORT.pdf**.

### Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/hunglk25/Vehicle-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Vehicle-detection
   ```
3. Download and unzip the pre-trained model weights:
   ```bash
   wget -O model.zip "https://drive.google.com/uc?export=download&id=14gEC3AH4_1bTmWIJBAF9LK2wCk2AFM3g"
   unzip model.zip -d .
   rm model.zip
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Demo

To launch the demo application, run the following command:

```bash
streamlit run demo.py
```

This will start a **Streamlit** web app for vehicle detection.
