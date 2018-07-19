

### SageMaker Image classification lst format
This notebook `Image-classification-lst-format-cat-dog.ipynb` demos an end-2-end system for image classification training with image and list files. cat-vs-dog dataset is used as a transfer learning dataset. The network re-initializes the output layer with the number of classes in the dataset and retrains the layer while at the same time fine-tuning the other layers. Various parameters such as network depth (number of layers), batch_size, learning_rate, etc., can be varied in the training. Once the training is complete, the notebook shows how to host the trained model for inference.
