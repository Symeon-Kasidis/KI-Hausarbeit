# KI-Hausarbeit

1. Download the original Dataset for kaggle. I am not allowed to publish it here because of the license

link: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset

2. remove all corrupt images from the dataset as of making writing this following images were corrupt:

cat/666
cat/8456

3. the project should have thsi structure:
|---archive
  |---PetImages
    |---Cat
    |---Dog
|---unlabeled.ipynb
|---requirements.txt

4. as of writing this pytorch supports python 3.12 but not 3.13. 3.13 is only supported on experimental Version (this might have changed)

5. install all dependecies from requirements.txt with pip install -r requirements.txt. If that fails then wou will need to add following packages manually torch, torchvision, matplotlib.pyplot, random, torchaudio

6. if you have cuda then you will ned to change teh packages accordingly. Use this table from the Pytorch Website: https://pytorch.org/get-started/locally/

7. This was onyl tested with CPU because my GPU is not supported. If your GPU throws errors i cant debug them