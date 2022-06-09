# Lymphoma-classification

TRANSFER LEARNING BASED MODELS FOR LYMPHOMA CLASSIFICATION

This repsitory consists of four notebooks, all of which contains transfer learning models that were developed to classify 3 subtypes of lymphoma.

The notebook 'Lymphoma classification - Original' consists of models developed from 5 different networks, namely DenseNet121, ResNet50, InceptionV3, DenseNet201, and ResNet152. These models were trained using the unaugmented, untransformed dataset.

The notebook 'Lymphoma - Heavily Augmented, Transformed' also consists of models developed from the same 5 networks, but these models were trained using a heavily augmented and transformed dataset.

The notebook 'Lymphoma classification - Augmented, Transformed' consists of models developed from the DenseNet121 and DenseNet201 networks. These models were trained using a transformed but less heavily augmented dataset.

The notebook 'Lymphoma classification - Augmented, Untransformed' also consists of models developed from the DenseNet121 and DenseNet201 networks, but these networks were trained using an augmented but untransformed dataset.

The original dataset can be found at https://www.kaggle.com/datasets/andrewmvd/malignant-lymphoma-classification/download
