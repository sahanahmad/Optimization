# When do Convolutional Neural Networks Stop Learning?
CNN Early-Stopping Research
• Developed CNN early-stopping method via layer-wise data variation analysis — reducing training computation
by 58% across 6 architectures with no accuracy loss; validated on 3 standard computer vision datasets, 10
biomedical imaging datasets (MedMNIST V2)
• Ranked 1st in the Board of Regents Support Fund, Louisiana (RCS FY 2022-23) and received a $149,351 grant

The official PyTorch implementation of When do Convolutional Neural Networks Stop Learning? .

Required Packages:

python 3.6.3

numpy 1.19.2

pandas 1.1.5

pytorch 1.3.1

scipy 1.5.2

seaborn 0.11.1

termcolor 1.1.0

torchvision

scikit-learn

***USAGE:***
Simply use the code by running:

`python3 main.py --dataset <DATASET> --alg <MODEL> --data <PATH_TO_DATA>`

For example, to train a ResNet on CIFAR10 and the data is saved in `./data/`, we can run:

`python3 main.py --dataset cifar10 --alg res --data ./data/`


To use CBS models please modify the file name by following:

CNN+CBS:        models_CBS.py ->  models.py

ResNet18+CBS:   resnet_CBS.py ->  resent.py

VGG16+CBS:      Vgg_CBS.py    ->  Vgg.py



