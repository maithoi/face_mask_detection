# REAL-TIME FACE-MASK DETECTION ON VIDEO 
***Phát hiện đeo khẩu trang trên video sử dụng kỹ thuật học sâu.*** 

## Abstract
In the context of the Covid-19 pandemic that is developing very complicatedly, the disease is spreading rapidly in the community. According to the 5K recommendation of the Ministry of Health, Wearing a mask in public helps to prevent the spreading. However, monitoring the enforcement of mask-wearing in public places requires a lot of human resources and expensive operating costs. Therefore, the development of automatic surveillance systems capable of automatically detecting mask-wearing is very urgent. From that urgency, the thesis proposes an real-time automatic mask-wearing detection method on video data and classifies mask-wearing subjects into 3 classes: wearing a mask, not wearing a mask, and wearing the mask incorrectly.
To solve the proposed thesis problem, I have approached the problem by building a YOLOv4 algorithm model using the Darnet library on the Google Colab platform.
After the process of experimentation and evaluation, I have successfully built a YOLOv4 algorithm model capable of detecting automatic mask-wearing on video for 3 groups of subjects as mentioned in the thesis problem. The developed model achieves up to 80.7% accuracy and achieves up to 15 FPS prediction rate on Tesla T4 GPU.


## Dataset 
***Trainable face-mask dataset with annotations.***

https://drive.google.com/file/d/147lo_Z_4tzrFClZFI66h_ilSnOTEIf0f/view?usp=sharing


## Model 
***Trained face-mask detection model using YOLOv4 algorithm.***

https://colab.research.google.com/drive/14dmSPul6nPCNaKBnOVyUQSgr_jLYWsfs?usp=sharing

## Training 

The training process is done using Darnet library on Google Colab software. 

![Training flow using Darnet library](https://github.com/maithoi/face_mask_detection/blob/main/YOLOv4%20training-flow.png)

## Prediction 

The inferencing process is done using Darnet libary on Google Colab software. 
![Prediction flow using Darnet library](https://github.com/maithoi/face_mask_detection/blob/main/Face%20mask%20prediction.png)

![No Mask Detection](https://github.com/maithoi/face_mask_detection/blob/main/4-6b.png)

## Demo 
https://www.youtube.com/watch?v=1tBw8-2VUuM&ab_channel=MaiV%C4%83nTh%E1%BB%9Di

### Correct Mask Wearing Detection

![Correct Mask Detection](https://github.com/maithoi/face_mask_detection/blob/main/4-4a.png)

### No Mask Wearing Detection 

![No Mask Detection](https://github.com/maithoi/face_mask_detection/blob/main/4-5a.png)

### Incorrect Mask Wearing Detection

![No Mask Detection](https://github.com/maithoi/face_mask_detection/blob/main/3-24.jpg)

