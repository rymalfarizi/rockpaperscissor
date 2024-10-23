# Rock-Paper-Scissor Prediction
This project aims to build a machine learning model using TensorFlow to classify images into one of three categories: rock, paper, or scissors. In the game "Rock-Paper-Scissors," each image will contain one of these objects, and the model will be trained to recognize and classify the images accordingly.

Clone repository to your local computer using terminal or git bash
```
git clone [github path](https://github.com/rymalfarizi/rockpaperscissor.git)
```

## Train Model
Here's how to train using Google Colab:
1. Upload 'learning.ipynb' to your google drive account
2. After that, open it
3. Change runtime to T4 GPU or TPU v2-8 to speed up training process
![image](https://github.com/user-attachments/assets/12496451-06ee-4be0-b691-5909a4e60cac)
![image](https://github.com/user-attachments/assets/3e4a5262-40c0-464f-b258-6dcd78fcf602)

4. Run all blok code. Wait till the process done
![image](https://github.com/user-attachments/assets/1e29937c-6238-4e5f-be4a-3e99428e9245)

5. Then, download 'best_model.keras'
![image](https://github.com/user-attachments/assets/5fdf7fbf-9cda-4c68-9a11-3e390f79f5b5)


# Predict Image
1. Upload 'predict.ipynb' to your google drive account
2. Then, open it
3. You can use whatever runtime
4. Upload 'best_model.keras' or drag the file
![image](https://github.com/user-attachments/assets/7aab2079-20bd-4531-b3bc-605fd1c9a5e4)
5. Run all blok code
6. Upload image from your local computer
![image](https://github.com/user-attachments/assets/9e5ccb8e-0ed9-4276-b34e-25e67532702a)
7. After that, model will predict your image
