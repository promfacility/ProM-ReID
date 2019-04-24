# ProM-ReID
Recognizes staff of ProM facility

The code is inspired by [this](https://github.com/serengil/tensorflow-101) repo.

# Instructions
1. Place face images of persons to be recognized in ```face_db/``` folder
2. Download ```haarcascade_frontalface_default.xml``` from [here](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml) and place it in ```models/```
3. You can download pretrained weights from  [here](https://drive.google.com/file/d/1CPSeum3HpopfomUEK1gybeuIVoeJT_Eo/view?usp=sharing) and place them in ```models/```
4. Run ```python3 main.py```
