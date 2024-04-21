# Anime Character Generation

![Generated Anime Characters](anime_result.png)

## Dataset and Resources
- **Dataset:** The GAN is trained on an anime character dataset, a collection of anime character images used to teach the GAN to create similar images.
- **Created By:** Sawan Kumar | April 2024

## Tasks in this notebook
- Architecture of the GAN
- Loading and Preprocessing the Anime Character Dataset
- Defining the Generator and Discriminator Models
- Training the GAN
- Visualizing the Generated Anime Characters

## Setup
This project requires Python 3.7 or above. Install the necessary libraries using:
```bash
pip install pandas numpy packaging scikit-learn tensorflow matplotlib


## GAN Configuration
- **image_size:** 64x64 pixels
- **latent_size:** 128
- **batch_size:** 128
- **epochs:** 25
- **Learning Rate (lr):** 0.0002

## Dataset Loading and Preprocessing
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/splcher/animefacedataset).
2. Extract the dataset and set the `data_dir` variable to the directory containing the images.

## Training the GAN
- Run the provided code to define and train the GAN on the anime character dataset.
- Due to time constraints, the model in the example is trained for a limited number of epochs (7 epochs).

## Generated Images
After training, the GAN generates convincing anime character images. Check the output in the notebook.

## Note
- Make sure to download the dataset from the Kaggle link provided in the code.
- Adjust hyperparameters and training duration as needed for your project.

Thank you!
