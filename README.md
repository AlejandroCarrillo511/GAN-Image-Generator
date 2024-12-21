# GAN Image Generator for Football Dataset

This repository contains a GAN (Generative Adversarial Network) implemented in Python to generate football-related images. The project leverages TensorFlow and Kaggle datasets for training.

## How to Use

### 1. Open the Notebook
You can interact with the notebook and generate images using the following platforms:

- **Google Colab**: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<your-repository>/blob/main/Futbol_200_updated.ipynb)
- **Binder**: [Launch Binder](https://mybinder.org/v2/gh/<your-username>/<your-repository>/HEAD)

Replace `<AlejandroCarrillo511>` and `<GAN-Image-Generator>` with your GitHub username and repository name.

### 2. Run the Notebook

- Upload your `kaggle.json` file to access the Kaggle dataset.
- Execute all the cells to train the GAN or load a pre-trained model.
- Generated images will be saved automatically in the `generated_images` directory.

## Requirements

- Python 3.7+
- TensorFlow
- Kaggle API

## Generating Images

The notebook includes a function to save generated images:

```python
save_generated_image(image, filename="generated_image.png")
```
All saved images are located in the `generated_images` folder for easy access.

## Contributing

Feel free to fork this repository and submit pull requests to improve the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
