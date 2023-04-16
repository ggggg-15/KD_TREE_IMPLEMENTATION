# KD_TREE_IMPLEMENTATION
To find the points in a data after we enter the range


To run this file, we used google colab
open google collab, upload the above files(only Kd_tree_indexing) in the drive 
then run the following lines in a notebook(for example check run.ipynb):


from google.colab import drive
drive.mount('/content/drive')

!cp /content/drive/MyDrive/Kd_tree_indexing/estaciones.json .
!pip install geopandas

!python /content/drive/MyDrive/Kd_tree_indexing/ecobici.py

!python /content/drive/MyDrive/Kd_tree_indexing/findrange.py
