# ASL-Recognization
In this project, I have applied transfer learning to an Inceptionv3 Model to recognize Alphabets and Numbers in American Sign Language with 99% accuracy on the test set.

To implement this code, you can -
1. Download the model [here](https://drive.google.com/file/d/1zrpDYeS7AXeGmO4G3FAD55LY53PZZ7fh/view?usp=sharing).<br>

2. I have deployed the app using StreamLit, where you can directly upload a picture and you'll get the results. To check by uploading images -<br>
`streamlit run main.py`<br>

3. I have also implemened the real-time ASL detection using Google's [mediapipe](https://google.github.io/mediapipe/), which assists in hand detection. To see live ASL recoginition -<br>
`python live.py` <br>
