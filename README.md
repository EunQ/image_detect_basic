### 데이터셋

https://drive.google.com/file/d/1dbwq3R6fnQHm_srCYNxhSofrGPwN0jxw/view?usp=sharing

를 ipython파일과 같은 위치에 data, predict을 위치시킨다.


## 04-14
inceptionV3을 가지고 간단하게 이미지를 분류해보는 작업을 하였음.
지난번하고 다른점은 전에는 학습을 다시 시키거나 안할때는 pre_process을 안했지만 지금은 하고 있음.
하지만 이미지가 비슷하면 분류가 잘 안됨.(epoch=10)
여러번 두고 실험을 하겠으나 결과는 비슷할 꺼 같음.
img_gen은 dtat set에 있는 원본 데이터 증강하는 python파일임.
