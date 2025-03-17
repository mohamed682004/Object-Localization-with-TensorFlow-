# Object Localization with TensorFlow

This project is part of a **Coursera Guided Project** led by **Amit Yadav**. It focuses on **Object Localization** using TensorFlow, where the goal is to detect and localize specific objects (in this case, emojis) within images. The project involves downloading and preprocessing emoji data, building a TensorFlow model, and training it to predict bounding boxes around the emojis.

---

## Technologies Used

- **Python**: The primary programming language used for this project.
- **TensorFlow**: The deep learning framework used to build and train the model.
- **Matplotlib**: Used for visualizing emojis and model predictions.
- **NumPy**: Used for numerical computations and data manipulation.
- **PIL (Python Imaging Library)**: Used for image processing.

---

## Dataset

The dataset consists of **emoji images** downloaded from the [OpenMoji](https://openmoji.org/) project. The emojis are categorized into different emotions, such as happy, sad, laughing, etc. Each emoji is a 72x72 pixel image in PNG format.

---

## Steps

1. **Data Download and Visualization**:
   - Download the emoji dataset and extract it into the `emojis` directory.
   - Visualize the emojis using Matplotlib.

2. **Data Preprocessing**:
   - Resize and normalize the emoji images.
   - Create bounding box annotations for each emoji.

3. **Model Building**:
   - Define a TensorFlow model using convolutional layers for feature extraction and dense layers for bounding box regression.
   - Compile the model with an appropriate loss function and optimizer.

4. **Training**:
   - Train the model on the preprocessed dataset.
   - Monitor training progress using validation data.

5. **Evaluation and Visualization**:
   - Evaluate the model's performance on a validation set.
   - Visualize the model's predictions, including the localized emojis and their bounding boxes.

---

## Results

After training the model, you should be able to:
- Detect and localize emojis in images.
- Visualize the predicted bounding boxes over the emojis.

---

## Acknowledgments

- This project was completed as part of a **Coursera Guided Project** led by **Amit Yadav**.
- The emoji dataset is provided by [OpenMoji](https://openmoji.org/), licensed under CC BY-SA 4.0.
- Special thanks to the TensorFlow and Coursera communities for their resources and support.
