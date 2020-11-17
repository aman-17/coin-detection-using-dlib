# object-detection-using-dlib

### For giving annotations
$ python3 gather_annotations.py -d coins/ -a annot1.npy -i images1.npy

### For training
$ python3 train.py -a annot1.npy -i images1.npy -d coins1.svm

### For testing

$ python3 test.py -d coins1.svm -i coins/T11.jpeg -a coin

