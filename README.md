# KI-Hausarbeit

1. Download the original Dataset for kaggle. I am not allowed to publish it here because of the license

link: https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset

2. remove all corrupt images from the dataset as of writing this following images were corrupt:

- cat/666
- cat/8456
- dog/11702

3. the project should have thsi structure:

```
|---archive
  |---PetImages
    |---Cat
    |---Dog
|---unlabeled.ipynb
|---requirements.txt
```

4. as of writing this pytorch supports python 3.12 but not 3.13. 3.13 is only supported on experimental Version (this might have changed)

5. install all dependecies from requirements.txt with pip install -r requirements.txt. If that fails then you will need to add following packages manually torch, torchvision, matplotlib.pyplot, random, torchaudio, Jupiter notebook

6. if you have cuda then you will need to change the packages accordingly. Use this table from the Pytorch Website: https://pytorch.org/get-started/locally/

7. This was onyl tested with CPU because my GPU is not supported. If your GPU throws errors i cant debug them

8. you can start the code by typing  ``jupyter notebook`` and opening the unlabeled.ipynb after that just execute all blocks but wait for the previous block to finish this is important for the block that ingests the files and the traing loop that gets executed  before the generate Images block