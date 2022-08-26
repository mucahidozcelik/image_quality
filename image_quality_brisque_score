pip install image-quality

import imquality.brisque as brisque
import PIL.Image 

from google.colab import drive
drive.mount('/content/drive')

path = '/content/drive/MyDrive/test_photos/12345.jpg'
img = PIL.Image.open(path)
brisque.score(img)

#
import glob
import cv2 as cv

folder = glob.glob("/content/drive/MyDrive/test_images/*.jpg")

for i in folder :
    img = PIL.Image.open(i)
    print(i , brisque.score(img))
