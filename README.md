# 🌼 Image Classification with Streamlit & TensorFlow

A basic web app for image classification using Streamlit and TensorFlow.

It classifies the given image of a flower into one of the following five categories:  
1. 🌼 Daisy
2. 🌿 Dandelion
3. 🌹 Rose
4. 🌻 Sunflower
5. 🌷 Tulip

## 🚀 Commands

To run the app locally, use the following command:  
```bash
streamlit run app.py
```

The webpage should open in your browser automatically.  
If it doesn't, the local URL will be output in the terminal; just copy it and open it manually.  
By default, it will be `http://localhost:8501/`.

Click on **Browse files** and choose an image from your computer to upload.  
Once uploaded, the model will perform inference, and the output will be displayed.

## 📷 Output

<img src='misc/sample_home_page.png' width='700'>  
<img src='misc/sample_output.png' width='700'>

## 📝 Notes

- A simple flower classification model was trained using TensorFlow.
- The weights are stored as `flower_model_trained.hdf5`.
- The code to modify and train the model can be found in `model.py`.
- The web app created using Streamlit can be found in `app.py`.

