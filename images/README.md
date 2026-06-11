## Proposed Framework

MRI Images → Preprocessing → DenseNet121 Encoder → U-Net Decoder → Classification → Prediction

## Training Performance

### Accuracy vs Epochs

![Accuracy](images/accuracy.png)

The accuracy graph shows steady improvement during training and validation, indicating effective learning and strong generalization across different brain tumor classes.

### Loss vs Epochs

![Loss](images/loss.png)

The loss graph demonstrates consistent convergence throughout training, with both training and validation loss decreasing over time, indicating stable model performance.

## ROC Curve

![ROC Curve](images/roc_curve.png)

The ROC curve illustrates the model's ability to distinguish between different tumor categories, highlighting its effectiveness in multi-class brain tumor classification.
