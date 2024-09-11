# MSFCLNet
MSFCLNet
### Requirements
Please, install the following packages
- numpy
- torch 
- torchnet
- torchvision-0.2.0
- tqdm
### Options
- `lr`: learning rate
- `lrp`: factor for learning rate of pretrained layers. 
- `batch-size`: number of images per batch
- `image-size`: size of the image
- `epochs`: number of training epochs
- `evaluate`: evaluate model on validation set
- `resume`: path to checkpoint
### Demo VOC 
```sh
python3 demo_voc.py data/voc --image-size 448 --batch-size 32 -e --resume checkpoint/voc/voc_checkpoint.pth.tar
