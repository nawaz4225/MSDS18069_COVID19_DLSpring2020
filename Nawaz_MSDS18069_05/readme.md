Experiment 1:

Model: VGG16(No Layer Freezed)
Epochs  = 8
Learning Rate = 0.01

Focal Loss: gamma=2, alpha=0.25

Best Model Stats:  Validation Accuracy: 88.853503 %
precision =  0.9071047094852387 Recall    =  0.8757812499863159 F1 score =  0.891167769382776

Experiment 2:
Model: VGG16(All Freezed Layers)
Epochs  = 8
Learning Rate = 0.001

Focal Loss: gamma=2, alpha=0.25

Best Model Stats:  Validation Accuracy: 63.694268 %
precision =  0.6462035541091082 Recall    =  0.6249999999902344 F1 score =  0.6354248904327325

Experiment 3:

Model: VGG16(Random Layer Freezed)
Epochs  = 8
Learning Rate = 0.001

Focal Loss: gamma=2, alpha=0.25

Best Model Stats:  Validation Accuracy: 88.535032 %
precision =  0.9023721155252159 Recall    =  0.8737499999863477 F1 score =  0.8878303858169434

Experiment 4:

Model: ResNet18(All Layer Freezed)
Epochs  = 8
Learning Rate = 0.01

Focal Loss: gamma=2, alpha=0.25
Best Model Stats:  Validation Accuracy: 84.713376 %

precision =  0.859170833991625 Recall    =  0.832187499986997 F1 score =  0.8454638757076973

Experiment 5:

Model: ResNet18(Random Layer Freezed)
Epochs  = 8
Learning Rate = 0.01

Best Model Stats:  Validation Accuracy: 83.121019 %
precision =  0.8556851311814758 Recall    =  0.8254687499871021 F1 score =  0.8403053420816827
