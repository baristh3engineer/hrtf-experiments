# hrtf-experiments

There are 3 basic blocks in the project.ipynb file:

dataset.py
model.py
train.py

Also, there are 96 sofa files in the HRIRs folder.

I did not get a result in my last attempt. There is an error in calculating Y_inv I think. I am trying to keep the model.py file fixed for now.

There is a problem in the dataset.py or train.py section.

Also, I expected 480 measurements in the sofa files. However, there are 440 measurements, which prevents the selection of 120 basic examples as in fig 2.
