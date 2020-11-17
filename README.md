# object-detection-using-dlib

### For giving annotations
$ python3 gather_annotations.py -d coins/ -a annot1.npy -i images1.npy

### For training
$ python3 train.py -a annot1.npy -i images1.npy -d coins1.svm

![](https://user-images.githubusercontent.com/44740048/99423729-dd1b9300-2926-11eb-978d-3735f79bf460.png)

### For testing

$ python3 test.py -d coins1.svm -i coins/T11.jpeg -a coin

![](https://user-images.githubusercontent.com/44740048/99423751-e1e04700-2926-11eb-8fc8-25f876ca73a6.png)

# OUTPUT

![](https://user-images.githubusercontent.com/44740048/99423772-e7d62800-2926-11eb-9300-97c6a15d3c9a.png)
