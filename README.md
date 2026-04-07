## Music Genre Classification using Linear Algebra

This project demonstrates how linear algebra concepts can be used to classify songs into different genres based on numerical features.

---

##  Overview

In this project, songs are represented as vectors using features such as:

- Tempo  
- Energy  
- Danceability  

These features are organized into a matrix, and linear algebra techniques are applied to analyze patterns and classify music genres like **Rock, Pop, Hip-Hop, and Classical**.

---

## Concepts Used

- Matrix Representation  
- Row Reduced Echelon Form (RREF)  
- Vector Spaces and Basis  
- Eigenvalues and Eigenvectors  
- Principal Component Analysis (PCA)  
- Projection onto Subspaces  

---

## Methodology

1. Convert song data into matrix form  
2. Apply RREF to simplify the matrix  
3. Perform mean centering  
4. Compute covariance matrix  
5. Find eigenvalues and eigenvectors  
6. Apply PCA for dimensionality reduction  
7. Project data into reduced space  
8. Classify new input based on distance  

---

## Input Format

The model takes input as a vector:

Example : [120, 0.7, 0.6]


<img width="806" height="814" alt="image" src="https://github.com/user-attachments/assets/d212de6e-e51f-437a-bb51-c271cb960c40" />
<img width="717" height="777" alt="image" src="https://github.com/user-attachments/assets/fd72dc0a-a1e9-44dc-96a5-29e330c8b8ee" />
<img width="764" height="793" alt="image" src="https://github.com/user-attachments/assets/e27576bb-16f7-45ff-8a5c-2d99433d5eab" />


## Output

The system predicts the genre of the input song.

Example : Predicted Genre : Pop

<img width="1064" height="760" alt="image" src="https://github.com/user-attachments/assets/a0bee53a-8e07-427a-aaa7-abecdd88f88e" />

---

## How to Run

### Option 1: Google Colab
- Open the `.ipynb` file in Google Colab  
- Run all cells  

### Option 2: VS Code (Jupyter)
- Open the notebook in VS Code  
- Run all cells  

## Note : It's better run this in Google Colab, you don't need to install anything.

---

## Requirements

- Python  
- NumPy  
- Matplotlib  
- SymPy  

---

## File

- `Music_Genre_Classification.ipynb`

---

## Author

**Anand S**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
