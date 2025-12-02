# facial-emotion-detection
1. this is the python aiml project with a facial emotion recognition model using cnn, emotions like angry, disgust,fear,happy,sad,surprise,neutral,contempt
2. as you are seeing the directory we have 2 files cnn_emotions.ipynb and main.ip-ynb with a directory called as face model
3. now cnn_emotion.ipynb we have code which is used to train the cnn model upon affectnet dataset
4. main.ipynb is the file which you need to run to see the output in the terminal
5. main points before running the main.ipynb
  > 1. after downloading the project remember to go to face model directory and extract the zip file including the trained model
  > 2. after extracting the model you can see a .h5 extinsion file that is the saved model
  > 3. *model = load_model("D:/jupyter/facial_emotion_model_1.h5")* go to this line of the code and change the model path so that you can use your trained model
  > 4. you can also see my cnn training process which omly had 66% accuracy in detecting the emotions
  > 5. accuracy is less because of images that used to train the model (images are taken from affectnet dataset from affectnet) **link to dataset:**
  > 6. the provided dataset link has a folder names as 0-7 and meaning is given below
  > > -Angry (0)
  > > -Disgust (1)
  > > -Fear (2)
  > > -Happy (3)
  > > -Sad (4)
  > > -Surprise (5)
  > > -Neutral (6)
  > > -Contempt (7) 
