# Triplet_loss
Implementation of triplet loss with mnist

## Triplet loss part :
### Goal :
Try to embed mnist on a 3d shpere (this is for visualisation in fact the dimension isn't important)
Vectors of a same categorie must be close and others far

### How : 
Online triplet mining to select vectors that are close but shoudn't be that close
Optimal distance on a sphere is know with another script EquiDistribuedPoints

### Test :
It work great !!!
Img in coming

## Few shot learning part :
### Goal :
Detect if there is a boucle in a number or not

### How :
Try to separate number with boucles and other in two hemisphere on the sphere

### Test :
I have a data set with only on 8 on it but I use some data augmentation.
I put this data in a network and train triplet loss on it 
I show the test data and see if 8 are in the good hemisphere or not

### Results :
Model collapsing with keras and hard to know why.
I switched on pytorch

### To do :
Try without any 8 in the learning data
