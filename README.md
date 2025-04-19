# Damage-Detection-in-civil-infrastructures-using-multispectral-images.
Damage detection plays a critical role in maintaining the structural integrity and longevity of civil infrastructure, yet computer vision-based methods face limitations from inconsistent lighting, environmental noise, and complex backgrounds, which can hinder accurate damage detection. To address this challenge, this work introduces an enhanced damage detection algorithm CSP-CAS which incorporates Compact Inverted Block (CIB) to optimize Cross Stage Partial (CSP) net and integrates it with Context-Aware Segmentation (CAS) in the neck and head of You Only Look Once (YOLO) v9 Architecture. 

# Architecture


![image](https://github.com/user-attachments/assets/72225168-2d21-43d1-9756-fde52c595041)



# Example Dataset images and results
# RGB Dataset

![image](https://github.com/user-attachments/assets/32335fb1-589c-48c4-93df-595db419f0ff)


# Thermal Dataset
![image](https://github.com/user-attachments/assets/5d7a13ec-af09-4d99-8de6-1d7a68d2b731)

🔧 Setup Instructions (Google Colab + Google Drive)

Step 1: Prepare Google Drive Folder

Open your Google Drive.

Create a new folder and name it (e.g., YOLO).

Step 2: Upload Model Files

Download and upload YOLO model files.

Step 3: Upload YAML Configuration File

Upload a dataset YAML file with correct training/validation/test paths and class names.

Step 4: Upload Dataset

Upload your dataset (e.g., data.zip) containing images and annotations (in YOLO format).

Step 5: Create Output Folder

Inside your main folder, create a subfolder named run to store training results, weights, and logs.


# License
This project is licensed under the MIT License and is intended for research purposes only. Please cite this work if you use the code or dataset in your publications.
