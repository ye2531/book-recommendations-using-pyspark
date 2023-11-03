# Book Recommendations using PySpark

## Introduction

This ongoing project aims to build a book recommendation system using PySpark. To simulate a distributed environment Apache Spark cluster built with Docker is used.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset). It comprises 3 files.

* Users: contains the user data (location and age). 

* Books: contains content-based information (book title, book author, year of publication, publisher, cover image URL), 

* Ratings: contains the book rating information. Ratings are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## Setting up the Apache Spark Cluster with Docker

To create a distributed environment for this project, Apache Spark cluster is built using Docker. The code and detailed instructions can be found in the [spark-standalone-cluster-on-docker](https://github.com/cluster-apps-on-docker/spark-standalone-cluster-on-docker) repository.
