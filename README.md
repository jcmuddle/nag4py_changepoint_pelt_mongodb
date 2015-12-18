# Mongodb + PELT + nag4py
PELT changepoint analysis for a mongodb stock price collection using nag4py.

## Introduction
This repository containts several files, which, when combined, give an example of detecting changepoints in a stock price where the data has come from a mongodb collection.
The three key components of this example are:
* mongodb Python API - pymongo
* Killick et al's PELT algorithm for changepoint detection in n time.
* nag4py which allows one to easily call the PELT algorithm.
