# Generador de Imágenes GAN para Dataset de Fútbol

Este repositorio contiene una red GAN (Generative Adversarial Network) implementada en Python para generar imágenes relacionadas con el fútbol. El proyecto utiliza TensorFlow y datasets de Kaggle para el entrenamiento.

## Cómo Usar

### 1. Abre el Cuaderno
Puedes interactuar con el cuaderno y generar imágenes utilizando las siguientes plataformas:

- **Google Colab**: [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlejandroCarrillo511/GAN-Image-Generator/blob/main/Futbol_200_updated.ipynb)
- **Binder**: [Iniciar Binder](https://mybinder.org/v2/gh/AlejandroCarrillo511/GAN-Image-Generator/HEAD)

### 2. Ejecuta el Cuaderno

- Sube tu archivo `kaggle.json` para acceder al dataset de Kaggle.
- Ejecuta todas las celdas para entrenar la GAN o cargar un modelo preentrenado.
- Las imágenes generadas se guardarán automáticamente en el directorio `generated_images`.

## Requisitos

- Python 3.7+
- TensorFlow
- Kaggle API

## Generación de Imágenes

El cuaderno incluye una función para guardar las imágenes generadas:

```python
def save_generated_image(image, filename="generated_image.png"):
    filepath = os.path.join(output_dir, filename)
    plt.imshow(image)
    plt.axis("off")
    plt.savefig(filepath, bbox_inches="tight")
    print(f"Imagen guardada en: {filepath}")
```

Todas las imágenes guardadas se encontrarán en la carpeta `generated_images` para un acceso fácil.

## Contribuir

Siéntete libre de hacer un fork de este repositorio y enviar pull requests para mejorar el proyecto.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

