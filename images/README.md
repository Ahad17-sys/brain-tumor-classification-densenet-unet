## Proposed Framework

MRI Images → Preprocessing → DenseNet121 Encoder → U-Net Decoder → Classification → Prediction


## Training Performance

### Accuracy vs Epochs

<p align="center">
  <img src="images/accuracy.png" width="450">
</p>

The accuracy graph shows steady improvement during training and validation, indicating effective learning and strong generalization across different brain tumor classes.

### Loss vs Epochs

<p align="center">
  <img src="images/loss.png" width="450">
</p>

The loss graph demonstrates consistent convergence throughout training, with both training and validation loss decreasing over time, indicating stable model performance.

## ROC Curve

<p align="center">
  <img src="images/roc_curve.png" width="450">
</p>

The ROC curve illustrates the model's ability to distinguish between different tumor categories, highlighting its effectiveness in multi-class brain tumor classification.
