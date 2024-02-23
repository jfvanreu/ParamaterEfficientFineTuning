# ParamaterEfficientFineTuning
Machine Learning project using parameter-efficient fine-tuning approach applied on foundational models.

In this project, we create a model to detect languages. This model is using the **Parameter-Efficient Fine-Tuning** (PEFT) technique.

The project is composed of **4 key phases**:

1. Load the language detection dataset
2. Tokenize the dataset and load a pre-trained model (DistillBert in our case). We also adapt the pre-trained model for classification.
3. Assess the accuracy of the pre-trained model on the language classification task.
4. Create a new model using the **LoRa** approach which only updates linear layers.
5. Assess the new model and compare with the pre-trained model.
6. Test the model on a few random strings.
