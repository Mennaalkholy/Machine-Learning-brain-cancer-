# Brain Tumor MRI Classification — Comparative Analysis of CNN Models

Comparative study of deep-learning models for classifying brain tumor MRI images.

## Notebooks
- `PyTorch_Densenet,Resnet,Efficientnet.ipynb` — fine-tunes ResNet18, DenseNet121 and EfficientNetV2-S (PyTorch)
- `efficentnetB2_model.ipynb` — EfficientNetB2 (Keras/TensorFlow)
- `FinalMachine.ipynb` — final combined notebook

## Results (from saved notebook outputs)
| Model | Framework | Best test accuracy |
|---|---|---|
| ResNet18 | PyTorch | 98.25% |
| DenseNet121 | PyTorch | 97.71% |
| EfficientNetB2 | Keras | 97.87% (precision 97.87%, F1 97.86%) |
| EfficientNetV2-S | PyTorch | 94.36% |

## Run
Open the notebooks in Jupyter or Google Colab and run the cells in order.
