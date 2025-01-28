# CNN-Model-for-Face-Emotion-Classification-Using-AffectNet-Dataset
I trained a CNN model to predict emotions on faces using the AffectNet Dataset. The model is able to detect the expression of the face, and the persons emotion through facial expression recognition.


I trained the model using the AffectNet dataset which i downloaded from kaggle
https://www.kaggle.com/datasets/mstjebashazida/affectnet
The dataset comprises of RGB images. The images are of 8 classes but i reduced it to 7 for my model which including: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

The CNN model summary is shown below:
![Model History](https://github.com/user-attachments/assets/c4d467f1-a48f-4005-ae4a-de3f1f89b68b)


I set the model to train for 100 epoch with early stop call back function. The model trained for 78 epoch and the training history is shown in the plot below:
![Accuracy](https://github.com/user-attachments/assets/2ad867ed-06e7-47dd-9112-da04bef675a0)

![loss](https://github.com/user-attachments/assets/31dd7b7e-983a-4fd1-9c2b-4cfbaac31524)



After training the model, i evaluated for accuracy and perfomance.
The confussion matrix is shown below:
![Confusion Metrics](https://github.com/user-attachments/assets/671730e3-e095-4e9f-8afe-7c9df3262845)

Other accuracies evaluated on the model is shown below:
![Per class accuracy](https://github.com/user-attachments/assets/fbb4c431-f8be-4503-8ef8-4447cb343a25)
