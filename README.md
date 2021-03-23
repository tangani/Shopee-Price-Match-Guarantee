# 🕵️‍♀️Determine the category of items using images

This is an image classification challenge hosted on kaggle.com

## 1.Problem definition

> How well can the model predict the if the images provided belong to certain categories. This can also be used to show which items customers desire with are not in the business' catalogue.



## 2. Data description

The data contained here was obtained from Kaggle https://www.kaggle.com/c/bluebook-for-bulldozers/data

The data for this competition is split into three parts:

* Train.csv is the training set
* Valid.csv is the validation set
* Test.csv is the test set, which won't be released until the last week of the competition.

The key fields are in train.csv are:

**posting_id**: the uniue identifier of the image post
**image**: name of the image in the train_images/test_images folder
**image_phash**:
**title**: Title of the image category
**label_group**: group I.D number or category of the image

There are several fields towards the end of the file on the different options a machine can have.  The descriptions all start with "machine configuration" in the data dictionary.  Some product types do not have a particular option, so all the records for that option variable will be null for that product type.  Also, some sources do not provide good option and/or hours data.

## 3. Evaluation

Submissions will be evaluated based on their mean F1 score. The mean is calculated in a sample-wise fashion, meaning that an F1 score is calculated for every predicted row, then averaged.

## 4. Features

The features of this data are given in detail in the data dictionary on kaggle https://www.kaggle.com/c/shopee-product-matching/data
