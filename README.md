# ECGR8119_FinalProject

Created by Chris Beam and Micah Bingham

This contains ipynb files to:
    
* Create a GAN using the CIFAR-10 dataset and a control MobileNetV2 classifier.
    
* Create a fake dataset using the trained GAN

* Create a MobileNetV2 classifier trained on both the CIFAR-10 dataset and the fake dataset.

    * This is also replicated for various sizes using a trained SRGAN

* Create a SRGAN to make synthetic high resolution images.

The folder layout should also include a fake_dataset, logs, models, and outputs folders to store any information generated from these files.

There is also a requirements.txt file that contains all the needed modules.