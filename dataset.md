## About the original dataset - PlantVillage
- The PlantVillage dataset consists of 54303 healthy and unhealthy leaf images divided into 38 categories by species and disease.
- TensorFlow provides direct support for the PlantVillage dataset, enabling easy integration into TensorFlow-based models. 
- Link : https://www.tensorflow.org/datasets/catalog/plant_village
- The images span 14 crop species: Apple, Blueberry, Cherry, Corn, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, Tomato. 
- In containes images of 17 fungal diseases, 4 bacterial diseases, 2 mold (oomycete) diseases, 2 viral disease, and 1 disease caused by a mite. 
- 12 crop species also have images of healthy leaves that are not visibly affected by a disease.

## About the dataset used 
- dataset finally used in the project : https://data.mendeley.com/datasets/tywbtsjrjv/1
- In this data-set, 39 different classes of plant leaf and background images are available.
- The data-set containing 61,486 images. We used six different augmentation techniques for increasing the data-set size.
- The techniques are image flipping, Gamma correction, noise injection, PCA color augmentation, rotation, and Scaling.

## About the paper - 
- Human society needs to increase food production by an estimated 70% by 2050 to feed an expected population size that is predicted to be over 9 billion people.
- Currently, infectious diseases reduce the potential yield by an average of 40% with many farmers in the developing world experiencing yield losses as high as 100%. 
- However, the fact that the global food supply is annually reduced by an average of 40% (Oerke 2006) demonstrates that our collective battle against diseases and pests of crop plants is not won.

## Note - 
The original dataset is not available from the original source (plantvillage.org), therefore we get the unaugmented dataset from a paper that used that dataset and republished it. Moreover, we dropped images with Background_without_leaves label, because these were not present in the original dataset.
