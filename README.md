# Osteoarthritis-Classification
An orthopaedist is a medical doctor specializing in diagnosing and treating disorders related to the skeletal system. Part of their job is to distinguish between a healthy person and a person with Osteoarthritis by looking at their knee X-ray images.
Osteoarthritis, commonly known as wear-and-tear arthritis, is a condition in which the natural cushioning between joints — cartilage — wears away. When this happens, the bones of the joints rub more closely against one another with less of the shock-absorbing benefits of cartilage. The rubbing results in pain, swelling, stiffness, decreased ability to move, and, sometimes, the formation of bone spurs.
![image](https://user-images.githubusercontent.com/92297330/179763762-219a0bde-dcb6-4570-b82c-7221eeac4e0b.png)
Healthy Knee Joint
![image](https://user-images.githubusercontent.com/92297330/179763801-559e5e07-2f30-4941-a1ae-4b033c7e5cec.png)
Osteoarthritis Condition


The dataset for this is divided into training, validation and testing which is used to train the deep learning model
Firstly, the dataset is preprocessed using cv2 and numpy module so that an clean and consistent data can be passed in model training.
After that, training and validation array is passed into the model to train. Here transfer learning is used to train the model and DenseNet201 pre-trained CNN model is used using tensorflow and keras module.
After training the model, it is then evaluated using accuracy and confusion matrix.
