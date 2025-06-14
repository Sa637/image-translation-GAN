🖼️ Image Translation using GAN
This project performs Image Translation using a Generative Adversarial Network (GAN) model, specifically trained to transform images of horses into zebras and vice versa. The implementation is done entirely in Google Colab and is based on the popular CycleGAN architecture.

📌 Project Description
This project applies unpaired image-to-image translation using deep learning.

It uses CycleGAN to learn mappings between two image domains (e.g., horses and zebras).

The trained model can generate realistic translated images from one domain to another.

🧠 Algorithm Used
Model: CycleGAN (Generator + Discriminator)

Why CycleGAN: It allows unpaired training, which means the model learns without needing exact horse-zebra image pairs.

Framework: PyTorch

Trained on GPU in Google Colab

📊 Dataset
🔗 [Click here to download the Horse2Zebra dataset](https://www.kaggle.com/api/v1/datasets/download/balraj98/horse2zebra-dataset?dataset_version_number=1)

Two classes: horse/ and zebra/

Images used for training, testing, and validation

🚀 How to Run
Open the notebook in Google Colab.

Upload the dataset or download it via Kaggle CLI.

Run all cells sequentially:

Data preprocessing

Model definition (Generator, Discriminator)

Training loop

Visualization of translated outputs

🛠️ Libraries/Dependencies
Python 3.10+

PyTorch

torchvision

matplotlib

numpy

📷 Sample Results
sample_zebra.jpg
day-night.jpg
img_gen.jpg

📌 Future Scope
Extend to other domain translations (e.g., Summer → Winter)

Deploy as a web-based demo using Flask/Streamlit

Use perceptual loss or attention-based GANs for better quality

