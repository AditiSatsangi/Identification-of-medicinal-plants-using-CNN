# Identification of Medicinal Plants using CNN

The project "Identification of Medicinal Plants using CNN" leverages deep learning techniques to automate the classification of medicinal plants based on their leaf images. This endeavor holds immense promise for the Ayush Ministry and various stakeholders in herbal medicine, botanical research, and environmental conservation. This project is mainly predicting the medicinal plant which can help in differentiating the medicinal plants. We are going to use the deep learning CNN model. It gives an accuracy of 86.7%. Some steps used for preparing this project are as follows -

1. ## Data Collection:
   - We have meticulously curated a comprehensive dataset of leaf images, primarily sourced from the "Indian Medicinal Leaves Dataset" on Kaggle.

2. ## Data Preprocessing:
   - Our project begins with rigorous data preprocessing to ensure dataset quality and suitability. This includes image resizing, normalization, and data augmentation techniques to enhance the model's generalization ability.

3. ## Convolutional Neural Network (CNN):
   - At the core of our project is a state-of-the-art CNN architecture. CNNs are tailor-made for image classification tasks and excel at automatically learning meaningful features from raw image data.
   - Our CNN architecture includes convolutional layers for feature extraction, pooling layers for spatial down-sampling, and fully-connected layers for precise class predictions.

4. ## Training:
   - Our training process involves a blend of rigor and innovation. While traditional CNNs start from scratch, we employ a state-of-the-art transfer learning approach to expedite the model's learning process.
   - Transfer learning enables us to leverage the knowledge gained by a pre-trained model, MobileNet in this case, on a vast dataset (e.g., ImageNet). This pre-trained model has already learned a wealth of generic features from diverse images.
   - We fine-tune the MobileNet model on our medicinal plant leaf dataset. During this phase, the model adapts its pre-learned features to the specific patterns and characteristics found in medicinal plant leaves.
   - The training process involves optimizing the model's weights and biases to minimize classification errors. This fine-tuning is performed with meticulous care to ensure the model becomes an expert in discerning unique leaf features that signify distinct medicinal plant species.

By incorporating transfer learning with MobileNet, we harness the power of proven deep learning architecture, accelerating our model's ability to recognize critical patterns in leaf images and leading to the impressive accuracy we've achieved.

5. ## Model:
   
6. ## Validation:
   - To ensure robust performance, our trained model is subjected to validation using a separate dataset it has never encountered before.

7. ## Testing and Remarkable Accuracy:
   - After successful training and validation, our model is put to the test on entirely novel data.
   - The reported accuracy of approximately 86.7% underscores the model's ability to accurately classify medicinal plants based on leaf images with remarkable reliability.

8. ## Prediction:
   We are giving the input image and then our CNN model will give the predicted about about the class of the plant or the name of that particular medicinal plant.

    ![image](https://github.com/AditiSatsangi/Identification-of-medicina-plants-using-CNN/assets/123658491/d228613d-7ce5-41ec-8816-f50aaccabd48)


9. ## Practical Application and Impact:
   - Beyond the realms of academia, our project has practical applications of significant consequence. It serves as a potent tool for expedited and precise identification of medicinal plants based on leaf images.
   - Such technology holds substantial potential for the Ayush Ministry, offering a streamlined means to catalog and verify plant species used in traditional medicine.

10. ## Remarkable Output:

The "Identification of Medicinal Plants using CNN" project has delivered outstanding results, with our model achieving an accuracy rate of approximately 86.7%. This substantial output signifies our project's prowess in accurately categorizing and cataloging plant species. This capability holds the potential to revolutionize the herbal medicine industry and contribute to environmental conservation efforts.

![image](https://github.com/AditiSatsangi/Identification-of-medicina-plants-using-CNN/assets/123658491/b6e9a9e5-27f7-4cb2-a08c-7e53a1764a7f)

