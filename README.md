# **Text-To-Music**

An AI-powered project that generates music compositions from textual descriptions. This project leverages cutting-edge deep learning models to transform written prompts into expressive music.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Model Details](#model-details)
5. [Fine-Tuned Model](#fine-tuned-model)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)

---

## **Overview**
This project aims to bridge the gap between textual creativity and music generation using AI. By inputting textual descriptions, the system generates music compositions that align with the emotional and thematic aspects of the text.

---

## **Features**
- Transform text descriptions into music.
- Fine-tuned models optimized for accurate text-to-music transformations.
- Pre-processed datasets for easy reproducibility.
- Scalable pipeline for training and evaluation.

---

## **Dataset**
The project uses datasets from Hugging Face to train and fine-tune the model for music generation. You can explore and download the datasets from the following link:

[🎵 Explore Music Datasets on Hugging Face](https://huggingface.co/datasets?search=music)

- **Source:** Hugging Face Datasets
- **Description:** A collection of datasets containing textual and musical data for training text-to-music generation models.

> Note: Ensure you preprocess the dataset as required before using it for training.

- **Preprocessing Details:** Data was tokenized and aligned with audio features for effective model training.

---

## **Model Details**
The model architecture is based on:
- **Base Model:** [Base Model Name or Architecture, e.g., Transformer/GRU]
- **Fine-Tuning:** Fine-tuned on custom datasets to improve context understanding between text and music.
- **Frameworks Used:** PyTorch, TensorFlow, or others (mention specific tools/frameworks you used).

---

## **Fine-Tuned Model**
The fine-tuned model for this project is available for download:

[🚀 Download the Fine-Tuned Model](https://drive.google.com/file/d/1sX-9R6nsmTxip2jeZhZL6W6hmND_IuCi/view?usp=drive_link)

- **File Name:** Fine-tuned_Model.pth
- **File Size:** ~15GB
- **Description:** This model has been fine-tuned on a combination of datasets and is ready for use in text-to-music generation tasks.

---

## **Installation**
Follow the steps below to set up the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/Anonymous-2025-students/Text-To-Music.git
   cd Text-To-Music
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the fine-tuned model and place it in the `models` directory.

---

## **Usage**
Run the following commands to use the text-to-music model:

1. **Generate Music from Text:**
   ```bash
   python generate_music.py --text "A calm evening with gentle winds."
   ```

2. **Training Your Own Model:**
   ```bash
   python train.py --dataset /path/to/dataset --epochs 50
   ```

3. **Evaluate the Model:**
   ```bash
   python evaluate.py --model /path/to/fine_tuned_model.pth
   ```

---

## **Results**
Below are some examples of music generated using the model:

1. **Prompt:** *"Generate a hip hop music."*  
   - **Generated Music:** [🎵 Listen to Hip Hop Music](https://drive.google.com/file/d/1-hdEU_guFy2uO2Ab8-_IKnSBmH41EeB2/view?usp=drive_link)

2. **Prompt:** *"Generate a jazz music."*  
   - **Generated Music:** [🎷 Listen to Jazz Music](https://drive.google.com/file/d/1T2tPLJSeZhzLSdonKHwMq6FuR47Lw3-6/view?usp=drive_link)

3. **Prompt:** *"Generate a random music."*  
   - **Generated Music:** [🎼 Listen to Random Music](https://drive.google.com/file/d/1q1UWs7jk32rVMi2rs7mwNjri6HBRqzhD/view?usp=drive_link)


---

## **Contributing**
We welcome contributions to improve the project! Here’s how you can contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
4. Open a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Credits**
A big thanks to [AudioLDM2](https://github.com/haoheliu/AudioLDM2) for their amazing repository, which inspired and supported the development of this project. Without their work, this project wouldn't have been possible.

