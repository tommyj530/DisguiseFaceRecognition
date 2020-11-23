# DisguiseFaceRecognition
Resnet 18 model is further trained using a relatively small custom-made dataset (fake vs real, masked vs unmasked, manually augmented masked vs unmasked) for a binary classification task (disguise or not). The task is to use different data augmentatio, loss functions and techniques to better fit the model in the domain of distinguish disguised faces, but at the same time avoid overfitting as much as possible, given a small dataset.
The custom-made dataset was created in a balanced manner from three different open-source datasets.
Fake vs Real https://www.kaggle.com/ciplab/real-and-fake-face-detection
Mask vs Unmasked https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset
Manually augmented mask vs unmasked https://www.kaggle.com/danielferrazcampos/face-mask-images
