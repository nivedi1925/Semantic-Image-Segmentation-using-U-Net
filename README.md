# Semantic-Image-Segmentation-using-U-Net

📌 Project Overview

Semantic image segmentation is the task of assigning a class label to each pixel in an image. This project implements a U-Net architecture to segment and classify regions within an image, such as identifying "Car" or "Person" objects through pixel-wise classification.

Originally developed as part of the Deep Learning Specialization by DeepLearning.AI, this version extends the assignment by using a larger dataset sourced from Kaggle and includes minor modifications for learning and experimentation.


🗂️ Dataset

    Source: Kaggle

    The dataset includes images and their corresponding segmentation masks for different object classes.

🛠️ Frameworks & Libraries

    Python 3

    TensorFlow

    Keras

    NumPy

    Matplotlib

🧠 Model Architecture

The model uses the U-Net architecture, which is particularly well-suited for biomedical and semantic segmentation tasks. It consists of an encoder-decoder structure with skip connections, enabling precise localization.

🔧 Modifications Made

    Replaced the original dataset with a larger, more diverse one from Kaggle.

    Minor modifications to data preprocessing, training pipeline, and augmentation for better generalization.

    Added evaluation and visualization steps to validate the model's performance.

📈 Results

    Metric Used: Accuracy

    The model achieves high segmentation accuracy on the new dataset. (Add specific numbers or visualizations if available)

▶️ How to Run

    Clone the repository:

git clone https://github.com/nivedi1925/Semantic-Image-Segmentation-using-U-Net

Install dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

    jupyter notebook segmentation_unet.ipynb

    Follow the steps in the notebook to train or evaluate the model.

📷 Sample Output

(Optional: Add images showing original images + predicted masks)


🧾 Credits

    DeepLearning.AI – Deep Learning Specialization

    U-Net: Convolutional Networks for Biomedical Image Segmentation (Original Paper)

    Kaggle Dataset Contributors
