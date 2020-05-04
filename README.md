# covid-assignment

Task1:<br>
1 - Freeze all Layers except FC Layer<br>
2 - replace FC layer with 2 FC layers (1st 1input = 25088, out = 790, 2nd in = 790, out 2)<br>
VGG-16<br>
Confusion Matrix of results<br>
Learning Rate = 0.001 Batch Size = 200 Epochs = 5<br>
Trained on entire data Test accuracy = 94% Validation Accuracy = 87%<br>

ResNet18<br>
LAyers manipulation same like VGG Confusion Matrix of results<br>
Learning Rate = 0.001<br>
Batch Size = 200<br>
Epochs = 20<br>
Training: class accuracy = ​[81.41361257 83.54114713]<br>

Task 2<br>
<br>
VGG<br>
Unfreeze every fifth layer in network<br>
And extended existing FC layers with 2 new layers same as fc layer in task 1 vgg.<br>
Training data:<br>
Learning Rate = 0.001 Batch Size = 200 Epochs = 5<br>
class accuracy = ​[89.43089431 97.17514124]<br>

ResNet<br>
Learning Rate = 0.001 Batch Size = 200 Epochs = 20<br>
Training class accuracy = ​[86.91099476 90.02493766]<br>
