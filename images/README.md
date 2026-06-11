## Proposed Framework

MRI Images → Preprocessing → DenseNet121 Encoder → U-Net Decoder → Classification → Prediction

## Training Performance

### Accuracy vs Epochs

![Accuracy](images/accuracy.png)

The accuracy graph illustrates the model's learning progress across training epochs, demonstrating improved classification performance and effective feature learning for brain tumor detection.

### Loss vs Epochs

![Loss](images/loss.png)

The loss graph shows the convergence behavior of the model during training. A decreasing loss trend indicates stable optimization and improved model performance.

## ROC Curve

![ROC Curve](images/roc_curve.png)

The ROC curve evaluates the model's ability to distinguish between different tumor classes, highlighting its effectiveness in multi-class brain tumor classification tasks.
