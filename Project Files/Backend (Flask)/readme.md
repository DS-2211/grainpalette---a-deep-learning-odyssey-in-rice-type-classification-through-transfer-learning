# Backend – Flask Application

This folder hosts the Flask backend for the **GrainPalette** rice-variety classifier.

## File: `app.py`
- Loads the fine-tuned TensorFlow model **`rice.h5`** (MobileNetV3 backbone via TensorFlow Hub).  
- Accepts single-image uploads from the user interface.  
- Pre-processes the image (OpenCV resize → normalise → batch dimension).  
- Runs inference and maps the soft-max output to five classes *(Arborio, Basmati, Ipsala, Jasmine, Karacadag).*  
- Returns the predicted variety and confidence score, rendering them alongside the uploaded image.

## Libraries Used
- **Flask** – lightweight web server & routing  
- **TensorFlow 2** – model execution  
- **TensorFlow-Hub** – Hub layer for MobileNetV3  
- **OpenCV-Python** – image I/O & resizing  
- **NumPy** – array operations  
- **Werkzeug** – secure filename handling  

## Run the App
```bash
python app.py
