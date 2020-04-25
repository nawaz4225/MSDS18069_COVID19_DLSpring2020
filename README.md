# covid-assignment

Task1:
1 - Freeze all Layers except FC Layer
2 - replace FC layer with 2 FC layers (1st 1input = 25088, out = 790, 2nd in = 790, out 2)
VGG-16
Confusion Matrix of results
Learning Rate = 0.001 Batch Size = 200 Epochs = 5
Trained on entire data Test accuracy = 94% Validation Accuracy = 87%

ResNet18
LAyers manipulation same like VGG Confusion Matrix of results
Learning Rate = 0.001
Batch Size = 200
Epochs = 20
Training: class accuracy = ​[81.41361257 83.54114713]

Task 2

VGG
Unfreeze every fifth layer in network
And extended existing FC layers with 2 new layers same as fc layer in task 1 vgg.
Training data:
Learning Rate = 0.001 Batch Size = 200 Epochs = 5
class accuracy = ​[89.43089431 97.17514124]

ResNet
Learning Rate = 0.001 Batch Size = 200 Epochs = 20
Training class accuracy = ​[86.91099476 90.02493766]
