To access the Bio-image Analysis Notebook via Google Colab:

https://colab.research.google.com/github/jbkinney/22e_urp/blob/main/lecture_7/Lecture_7_bioimage_analysis.ipynb

There might be issues with running Part 1 in Colab environment; so might be preferable to pull the repo and run it locally. 

(Napari, the image viewer we introduce uses Qt (a cross platform software), and Qt needs a graphical environment to display the windows, and it seems that Google Colab does not provide it.)

For Part 2-4, to load image examples to the notebook. Copy the code below to give Colab access to Google drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Then upload the examples to the drive. Then we can read in from drive directly, e.g.:

```python
image_path = 'drive/My Drive/mitosis_mod.tif'
```

Instructions will be given in class as well. 
