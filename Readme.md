# Fruit Classification App

This app let's you drag and drop an image of a fruit and it will tell you whether it is Fresh or Spoiled.It is an AI-powered system that is integrated
into the warehouse’s conveyor belt infrastructure. The proposed system will include high-speed cameras positioned to capture images of fruit crates as they move along the
conveyor belt. Leveraging a deep learning model for real-time classification, the system will accurately classify fruits as either fresh or spoiled.


### Model Details
1. Used ResNet50 for transfer learning and hyper parameter tuning for CNN. 
2. Model was trained on around 16000 images with 16 target classes with the following fruit classes:
   1. Banana
   2. Lemon
   3. Lulo
   4. Mango
   5. Orange
   6. Strawberry
   7. Tamarillo
   8. Tomato

 3. The accuracy on the validation set was above 90%

### Set Up

1. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
2. Run the streamlit app:
   ```commandline
   streamlit run app.py
