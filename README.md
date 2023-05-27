# Singular Value Decomposition (SVD)

## Introduction
The Singular Value Decomposition (SVD) algorithm is a powerful tool for dimensionality reduction and data compression. This repository provides an implementation of the SVD algorithm in Python and demonstrates its application in image compression.

## How SVD Works
SVD decomposes a matrix into three separate matrices: U, Σ, and V^T. U contains the left singular vectors, Σ is a diagonal matrix containing the singular values, and V^T represents the right singular vectors. The SVD algorithm allows us to approximate the original matrix by selecting a subset of singular vectors and values.

## Image Compression with SVD
One of the key applications of SVD is image compression. By choosing an appropriate number of singular values, we can reconstruct the image with reduced storage and transmission requirements. In this repository, we provide code that performs SVD on grayscale images and constructs approximate images with different ranks.

## Getting Started
To use the SVD algorithm and experiment with image compression, follow these steps:

1. Install the necessary dependencies (NumPy, Matplotlib) if not already installed.
2. Clone this repository to your local machine.
3. Open the provided Jupyter notebook or Python script.
4. Run the code to see the SVD in action and visualize the reconstructed images at different ranks.

# Implementation
<a href="https://github.com/Ayoub-etoullali/SVD-Singular-Value-Decomposition/blob/main/Implementation%20of%20SVD%20in%20Python%20from%20scratch.ipynb">
  (1) Implementation of SVD in Python from scratch </a> <br>
<a href="https://github.com/Ayoub-etoullali/SVD-Singular-Value-Decomposition/blob/main/Implementation%20of%20SVD%20in%20Python%20using%20Numpy.ipynb">
  (2) Implementation of SVD in Python using Numpy </a> <br>
 <a href="https://github.com/Ayoub-etoullali/SVD-Singular-Value-Decomposition/blob/main/Application%20of%20SVD.ipynb">
  (3) Application of SVD </a> <br>

## Further Exploration
SVD has applications beyond image compression. It can be utilized in various domains, including database analysis and video compression. To deepen your understanding, we encourage you to explore additional resources on SVD and practice implementing the algorithm in different scenarios.

## Video tutoriel
<div align="center">
  <a href=" https://www.youtube.com/watch?v=emUZuGDkemk">
   <img src="https://github.com/Ayoub-etoullali/SVD-Singular-Value-Decomposition/assets/92756846/000aa16e-7314-40c9-9c90-80562ad3a90f" alt="HTML tutorial" style="width:42px;height:42px;">
  </a>
       <p>
       <sup>  <strong>Video -</strong> Singular Value Decomposition</sup>
       </p>
</div>

<br>

## Conclusion
In conclusion, the SVD algorithm is a powerful technique for dimensionality reduction and data compression. This repository provides an implementation of SVD in Python and demonstrates its application in image compression. By adjusting the number of singular values, you can control the level of approximation in the reconstructed images. We invite you to delve deeper into SVD and its versatile applications. Happy coding!

## References
  - https://www.accel.ai/anthology/2022/8/17/svd-algorithm-tutorial-in-python <br>
  - https://www.youtube.com/watch?v=5VDuVVPwh3w&t=27s <br>
  - https://www.geeksforgeeks.org/singular-value-decomposition-svd/ <br>
  - https://www.askpython.com/python/examples/singular-value-decomposition <br>

## The project team 👨‍💻
<kbd>Ayoub ETOULLALI</kbd> 
<kbd>Hasnae AIT TAARABT</kbd> 
<kbd>Houda CHAHIL</kbd> 
