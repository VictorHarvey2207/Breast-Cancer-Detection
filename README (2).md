# U-Net_Breast_Cancer_Detection

# Introduction
In this project, U-net was applied to detect breast cancer areas from ultrasound images. The code is stored in a jupyter notebook file. To run this code, modify the input dataset path. 

This is the organization of the folders:
<pre>
dataset/
├── benign/
│   ├── image1.png
│   ├── image1_mask.png
│   ├── image2.png
│   ├── image2_mask.png
│   └── ...
├── malignant/
│   ├── image1.png
│   ├── image1_mask.png
│   ├── image2.png
│   ├── image2_mask.png
│   └── ...
└── normal/
    ├── image1.png
    ├── image1_mask.png
    ├── image2.png
    ├── image2_mask.png
    └── ...
</pre>

# Dataset
Al-Dhabyani W, Gomaa M, Khaled H, Fahmy A. Dataset of breast ultrasound images. Data in Brief. 2020 Feb;28:104863. DOI: 10.1016/j.dib.2019.104863.
These are the examples of the images:

![image](https://github.com/user-attachments/assets/5146f1ac-17f3-4d40-a09f-269c7fcc609a)


# Evaluation
U-net appears to be a powerful model in this task when its valid accuration achieves up to 97.7%. The ratio of train-valid set is 80% - 20%. Below is the training and validating graphs:

Training process:

![image](https://github.com/user-attachments/assets/de12e402-26cc-45f8-8c68-75c034a37b66)


Validating process:

![image](https://github.com/user-attachments/assets/8ba871ea-aa08-4587-9d48-01b3be97d95e)


The prediction is presented in the pictures below. From the left to right are original ultrasound images, predicted images, and ground truth images.

![image](https://github.com/user-attachments/assets/07197178-5572-49c3-b6da-691f57ac5910)


# Acknowledgement
This project is done by a group of students from Hanoi University of Science and Technology. Thanks for the contribution from Nguyen Tat Hung (Leader), Nguyen Vu Thuy, Le Nhat Hoang, Nguyen Thanh Vinh.
