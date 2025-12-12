# Cat Breeds Classifier - Extended Breeds

A machine learning project for classifying 60 cat breeds using deep learning and transfer learning techniques.

## 🔗 Quick Links

- **Presentation**: [BISCUTE-presentation](https://github.com/ferdifdi/BISCUTE-presentation.pdf)
- **Web Application**: [BISCUTE](https://github.com/ferdifdi/BISCUTE)
- **Model**: [ferdifdi/cat-breed-60-classes](https://huggingface.co/ferdifdi/cat-breed-60-classes)

## 🚀 Quick Start

### Get the Pre-trained Model

```bash
cd models
git clone https://huggingface.co/ferdifdi/cat-breed-60-classes
```

## 📁 Dataset Structure

This project uses multiple datasets organized in the following directories:

### Main Datasets & How to Fill It

**1. cat-breeds-dataset/images/**
- Contains 67 cat breed categories
- Each breed has its own subdirectory
- Place images in the respective breed folders
- Obtains from https://www.kaggle.com/datasets/ma7555/cat-breeds-dataset


**2. catbreedsrefined-7k/CatBreedsRefined-v2/**
- Contains 20 refined cat breed categories
- Higher quality, curated dataset
- Place images in the respective breed folders
- Obtains from https://www.kaggle.com/datasets/doctrinek/catbreedsrefined-7k

**3. images/**
- Contains 12 additional breed categories:
  - Chartreux, Chausie, Khao Manee, Kurilian Bobtail
  - LaPerm, Neva Masquerade, Ocicat, Peterbald
  - Savannah, Selkirk Rex, Serengeti, Singapura
  - Obtains from https://www.kaggle.com/datasets/almanaqibmahmooddar/37-cats-breeds-dataset , and then we just take 12 new breeds, finally we delete the duplication

**4. preprocessed_new_breeds/**
- Preprocessed from images (background removing, cropping, resizing)

## 📝 Notes

- Image files are ignored by git (see `.gitignore`)
- Only folder structure is tracked via `.gitkeep` files
- Download/collect datasets separately before training
- Large model files may be ignored; download from HuggingFace
