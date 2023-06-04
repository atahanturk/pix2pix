This is the code of the algorithm pix2pix which we used in our design project.

This repository contains all paired images we used in training and testing.

train.py and test.py contains algorithms of pix2pix in training and testing phases. Models contains the models that used in the code.
This code can be used like this in Colab or in a Linux machine:

##### !git clone https://github.com/atahanturk/pix2pix
##### import os
##### os.chdir('pix2pix/')
##### !pip install -r requirements.txt
##### !python train.py --dataroot ./datasets/pix2pix_images --name rgb2thermal_pretrained --model pix2pix --direction AtoB --display_id -1 --continue_train
