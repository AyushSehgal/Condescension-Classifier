# Condescension-Classifier

## Collaborators 
Ayush Sehgal, Shreyans Sethi, Gayatri Babel

## Description
This project serves as an NLP exploration into quantifying condescension in New York Times articles. This was made as part of the Annotation Project in the Info159: Introduction to Natural Language Processing course at UC Berkeley.

The project includes 1000 data points pulled from [NY Times Archive](https://archive.nytimes.com/www.nytimes.com/ref/membercenter/nytarchive.html). Articles were rated on their headline and description as found in the archives page. Only articles between 2011-2022 were used. This data split into train, dev, test sets can be found in the **data folder**. 

In depth guidelines for an individual to rate each articles are provided in **guidelines.pdf** where we use a rating system ranging from 1, being not condescending to 5 being very condescending. We have also defined what we mean by condescending in the document. 

All the work done to develop the classifier with feature engineering is present in the **classifier.ipynb**. The classifier as it stands today reaches a final test accuracy of 79%, which beats the baseline majority class classifier, which has an accuracy of 76%. 

In **analysis.pdf** we report how the classifier did and reflect on its performance. 

Finally, **datasheet.md** contains reflection on the experimentation process as well as on the process of choosing the dataset. 
