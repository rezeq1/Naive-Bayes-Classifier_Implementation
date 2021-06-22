# Naive Bayes Classifier Implementation

This program contains Naïve Bayes Classifier implementation using the Laplacian patch .
The data file contains both continuous and categorical attributes.

## Input files description :
1) Dataset general info : General information about the database from which the file data is taken.
2) Structure : A file describing the attributes that make up each record in the database (including the target value which appears last in the list).

    a.The target attribute will always be called "class," and will be last in the file and in each record.

    b.from the file who of the attributes it is numeric or categorical.

          ▪ Numeric
              @ATTRIBUTE [AttTitle] NUMERIC

          ▪ Categorical
              @ATTRIBUTE [AttTitle] {some comma separated categories}
              
3) Train : A file containing records used to build the classifier.
4) Test  : A file that contains records that you will need to classify .
