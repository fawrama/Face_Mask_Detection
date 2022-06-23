# Face_Mask_Detection
this project is done to help the security guards spot those who aren't wearing face masks in closed-air areas to reduce the spread of covid 19.

# How it works
we have our dataset in the [dataset](./dataset) directory which we used to train out nueral network model in the file [train.py](./train.py).

1. to be able to build the model the machine must have already installed:
- [Tensor Flow](https://www.tensorflow.org/install/)
- [Sklearn](https://scikit-learn.org/stable/install.html)
- [Matplotlib](https://matplotlib.org/stable/users/installing/index.html)
- [Open CV](https://stackoverflow.com/questions/57883178/how-to-install-cv2)
2. Run the file [train.py] using the command line "python3 train.py". (This will take a long time)
3. After the last step is done, you will find 2 more files added in the working dir:
  - [plot.png](./plot.png) which is contains a gragh of the learning rate of the model.
  - [faceMask_detection.model](./faceMask_detection.model) which is the model we just trained.
4. Now we can use our trained model easily without traingin it each time we need to run it.

# compiling our model into an app
1. run the file [faceMaskDetection.py](./faceMaskDetection.py) by the command "python3 faceMaskDetection.py"
2. the application would access the camera and would tell if you are wearing a mask or not

https://user-images.githubusercontent.com/71787197/175300148-a690fa71-cc2e-4bc9-9b46-3f51f9b6de81.mp4

