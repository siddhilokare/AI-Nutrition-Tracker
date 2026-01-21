A machine learning project that uses image recognition to identify food items and estimate their calorie content in real time. This project integrates a deep learning model with the Nutritionix API to provide accurate nutritional insights.

#Features
- Food image recognition using a trained CNN model (`food_recognition_model.h5`).
- Real-time calorie estimation via Nutritionix API.
- Modular Python scripts for recognition (`food_recognition.py`), calorie estimation (`calorie_estimator.py`), and app integration (`app.py`).
- Easy to extend for new food categories or APIs.

#Project Structure
- `app.py` → Main application script.
- `food_recognition.py` → Food image classification logic.
- `calorie_estimator.py` → Calorie estimation using Nutritionix API.
- `food_recognition_model.h5` → Pretrained model weights.

#TechStack
- Python
- TensorFlow/Keras (for CNN model)
- OpenCV (image preprocessing)
- Nutritionix API (calorie data)
