# 🌿 AgriLeaf – AI-Based Leaf Health Analyzer with Treatment Recommendation

An AI-powered agricultural application that helps identify plant leaf diseases from images and provides treatment recommendations using Artificial Intelligence and Machine Learning.

## 📌 Project Overview

AgriLeaf is a final-year group project developed to explore how Artificial Intelligence and Machine Learning can help improve plant health monitoring and disease identification.

The application analyzes plant leaf images, predicts possible diseases using trained machine learning models, and provides associated treatment recommendations. It aims to make preliminary disease identification easier and support informed agricultural decisions.

The project is designed to support **40 diseases across 8 crops**, with a reported model accuracy of **89%**.

## 🎯 Objectives

- Identify plant leaf diseases using image classification.
- Support multiple crops and plant diseases.
- Provide treatment recommendations based on predicted diseases.
- Explore the application of AI and deep learning in agriculture.
- Support early identification of potential plant health problems.

## ✨ Key Features

- **AI-Based Disease Detection:** Predicts possible plant diseases from leaf images.
- **Multi-Crop Support:** Designed to cover 8 crops and 40 diseases.
- **Treatment Recommendations:** Provides guidance associated with the predicted disease.
- **Trained Deep Learning Models:** Includes models saved in H5, Keras, and TensorFlow SavedModel formats.
- **Class Label Mapping:** Uses a JSON file to store disease classification labels.
- **Docker Configuration:** Includes a Dockerfile for containerized deployment.

## ⚙️ How It Works

1. **Upload a Leaf Image:** The user provides an image of a plant leaf.
2. **Image Preprocessing:** The image is prepared for the model, according to the application's implementation.
3. **Disease Prediction:** A trained model analyzes the image and predicts a possible disease.
4. **Display Results:** The application presents the prediction.
5. **Treatment Recommendation:** Relevant treatment guidance is provided based on the predicted disease.

## 🛠️ Technology Stack

- **Programming Language:** Python
- **AI/ML Domain:** Machine Learning and Deep Learning
- **Model Framework:** TensorFlow/Keras model formats
- **Model Formats:** H5, Keras, and TensorFlow SavedModel
- **Version Control:** Git and GitHub
- **Large File Management:** Git LFS
- **Containerization:** Docker
- **Deployment Configuration:** Docker-based configuration for Hugging Face Spaces

## 📂 Project Structure

```text
AgriLeaf/
├── model/
│   ├── agrileaf_export/
│   │   ├── variables/
│   │   │   ├── variables.data-00000-of-00001
│   │   │   └── variables.index
│   │   ├── fingerprint.pb
│   │   └── saved_model.pb
│   ├── agrileaf_model.h5
│   ├── agrileaf_model.keras
│   ├── agrileaf_model_v2.h5
│   ├── class_names.json
│   └── train_model.py
├── .gitattributes
├── .gitignore
├── Dockerfile
└── README.md
```

### 📁 File Descriptions

- **`model/`** — Contains the trained model files and related resources.
- **`agrileaf_export/`** — Contains the exported TensorFlow SavedModel.
- **`variables/`** — Stores the saved model variable data and index.
- **`fingerprint.pb`** — Contains model fingerprint information.
- **`saved_model.pb`** — Contains the TensorFlow SavedModel graph and metadata.
- **`agrileaf_model.h5`** — A trained model saved in HDF5 format.
- **`agrileaf_model.keras`** — A model saved in Keras format.
- **`agrileaf_model_v2.h5`** — An additional saved model version.
- **`class_names.json`** — Stores the class labels used for classification.
- **`train_model.py`** — Contains model training or related training logic.
- **`.gitattributes`** — Defines Git file attributes and may include Git LFS tracking rules.
- **`.gitignore`** — Specifies files Git should ignore.
- **`Dockerfile`** — Defines the steps for building the Docker image.
- **`README.md`** — Provides project documentation.

## 🚀 Getting Started

### Prerequisites

Install the tools required for your environment:

- Git
- Git LFS
- Docker, if you want to run the Docker-based application locally

### 1. Clone the Repository

```bash
git clone https://github.com/Gaddam-megha/Agrileaf---AI-Based-Leaf-health-Analyzer-With-Treatment-Recommendation.git
```

### 2. Navigate to the Project Directory

```bash
cd Agrileaf---AI-Based-Leaf-health-Analyzer-With-Treatment-Recommendation
```

### 3. Download Model Files

If the repository uses Git LFS, run:

```bash
git lfs install
git lfs pull
```

This downloads the actual contents of files tracked by Git LFS.

### 4. Build the Docker Image

Make sure Docker is installed and running, then execute this command from the directory containing the `Dockerfile`:

```bash
docker build -t agrileaf .
```

### 5. Run the Docker Container

The following command assumes the application listens on port 7860 inside the container:

```bash
docker run -p 7860:7860 agrileaf
```

Open `http://localhost:7860` in your browser if the Docker configuration uses that port.

**Note:** The actual startup command and port depend on the `Dockerfile` and application configuration. Check these before running the commands.

## 📊 Project Details

| Item | Details |
|---|---|
| Project Name | AgriLeaf |
| Project Type | Final-Year Group Project |
| Domain | Artificial Intelligence and Machine Learning |
| Application Area | Smart Agriculture |
| Supported Crops | 8 |
| Supported Diseases | 40 |
| Reported Model Accuracy | 89% |
| Containerization | Docker |

*The reported accuracy reflects the project information provided by the team and should be interpreted in the context of its model evaluation and test dataset.*

## 🙋 My Contributions

As a member of the AgriLeaf final-year project team, I contributed to improving and maintaining the project by:

- Reviewing the existing project files and code.
- Making corrections to the downloaded project.
- Managing the updated project files and machine learning model files.
- Uploading and maintaining the corrected version in my GitHub repository.
- Working with Git, GitHub, and Git LFS to manage version control and large model files.

Through this project, I gained practical experience in collaborative software development, version control, model file management, and working with an AI-based agricultural application.

## 👥 Team Members

This project was developed collaboratively as a final-year group project.

- **G. Meghana**
- **D. Neha**
- **D. Abhishikth**
- **Y. Namitha**


**Department:** Artificial Intelligence and Machine Learning (AIML)  
**Batch:** A8

## 🔮 Future Enhancements

- Evaluate and improve disease prediction performance.
- Expand support for additional crops and diseases.
- Add multilingual support for farmers.
- Improve treatment recommendations with crop-specific guidance.
- Explore real-time disease detection through mobile cameras.
- Evaluate the models using diverse real-world leaf images.
- Develop a mobile-friendly interface for easier access.

## ⚠️ Disclaimer

AgriLeaf is an academic project intended for educational and informational purposes. Its predictions are not a substitute for professional agricultural diagnosis. Users should consult qualified agricultural experts before making important crop-treatment decisions or applying pesticides.

## 🙏 Acknowledgements

We acknowledge the open-source libraries, machine learning frameworks, documentation, and learning resources that supported our project development.

---

**AgriLeaf — Using AI to support healthier crops and smarter agriculture.** 🌱

### 🔗 GitHub Repository

[View the AgriLeaf Project on GitHub](https://github.com/Gaddam-megha/Agrileaf---AI-Based-Leaf-health-Analyzer-With-Treatment-Recommendation)
