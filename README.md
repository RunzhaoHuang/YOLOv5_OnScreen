# Screen-detection-yolov5
This tutorial is based on yolov5(https://github.com/ultralytics/yolov5) and LabelImg(https://github.com/tzutalin/labelImg).

I extract some important and concise parts of them into a new notebook, ./yolov5-master/yolov5-custom-training(fish).ipynb, and train a custom model.

For model inference, I create the ./yolov5-master/detect(screen_and_webcam).ipynb file to detect object using webcam and on PC screen. These are more practical than just detecting images or videos offline.

You can train your model using local PC, if you have a GPU, or Colab will also work just fine.

Meanwhile, make sure that you have installed the packages in ./yolov5-master/requirements.txt.
