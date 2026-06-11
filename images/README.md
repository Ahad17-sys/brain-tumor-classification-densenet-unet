## Proposed Framework

The proposed framework is designed for automated brain tumor classification from MRI images using a hybrid DenseNet121 and U-Net architecture. The workflow begins with MRI image acquisition and preprocessing, including resizing and normalization. DenseNet121 is utilized for deep feature extraction, while the U-Net inspired decoder enhances spatial feature learning. The extracted features are then passed through classification layers to categorize MRI scans into Glioma, Meningioma, Pituitary Tumor, or No Tumor classes. The model is subsequently trained, evaluated, and tested to assess its classification performance.

**Workflow:**

MRI Images → Preprocessing → DenseNet121 Encoder → U-Net Decoder → Classification → Prediction

## Training Performance

### Accuracy vs Epochs

The accuracy graph demonstrates the model's learning capability over multiple training epochs. The increasing trend in both training and validation accuracy indicates effective feature learning and strong classification performance across different tumor categories.

### Loss vs Epochs

The loss graph illustrates the optimization process during training. A consistent reduction in training and validation loss reflects stable convergence and improved model generalization.

## ROC Curve

The ROC curve evaluates the model's discriminative ability for multi-class classification. The curve highlights the effectiveness of the proposed DenseNet121 and U-Net hybrid architecture in distinguishing between different brain tumor classes and normal MRI scans.
