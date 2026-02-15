# Rock–Paper–Scissors ML

A TensorFlow-based image classification project that trains multiple models (CNN, grayscale CNN, VGG16, ResNet50) to recognize rock, paper, and scissors gestures, compares their performance, and tests the best model on custom images.

## Project Structure
- [rock-paper-scissors.ipynb](rock-paper-scissors.ipynb): Main notebook with data loading, training, evaluation, and custom image testing.
- [customphotos/](customphotos/): Place your own images for testing.
- [graphs/](graphs/): Output charts/plots.

## Requirements
- Python 3.8+
- TensorFlow
- NumPy
- Matplotlib
- Pandas
- scikit-learn

## How to Run
1. Open [rock-paper-scissors.ipynb](rock-paper-scissors.ipynb) in VS Code or Colab.
2. Run all cells in order.
3. Upload custom images when prompted in the notebook.

## Models Trained
- RGB CNN
- Grayscale CNN
- VGG16 Transfer Learning
- ResNet50 Transfer Learning

## Outputs
- Training/validation accuracy and loss plots
- Confusion matrix for RGB CNN
- Model comparison table and plots
- Best model saved to Google Drive (Colab)

## Notes
- Custom image testing uses Colab file upload.
