# Assignment_3
# MATH/CSCI 485 - Sandesh Manjunath Raykar

This repository contains assignments for MATH/CSCI 485 Advanced Topics in Data Science at California State University, Chico.

## Assignment 3 - Image Compression via Block-wise SVD

This assignment explores how Singular Value Decomposition (SVD) can be used to compress grayscale images. The idea is simple: instead of applying SVD to the whole image at once, the image is broken into small 8x8 blocks and SVD is applied to each block separately. By keeping only the top k singular values per block, we can reconstruct the image using less data.

The notebook covers loading and preprocessing the image, writing the compression function, computing compression ratio and reconstruction error for k from 1 to 8, plotting the results, and an optional experiment comparing different block sizes.

## How to run

Open the notebook in Google Colab and run all cells from top to bottom. No additional setup is needed as all libraries used are available by default in Colab.

## Repository structure

Assignment_3 folder contains the Jupyter notebook with source code and outputs, and a PDF report with analysis and results.
