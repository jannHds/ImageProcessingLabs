# Lab 2: Digital Image Fundamentals

This lab explores the basic concepts of digital image processing using Python, including image sampling, quantization, arithmetic operations, and set operations on grayscale images.

## Objectives

- Understand digital image representation.
- Explore the effect of sampling on spatial resolution.
- Explore the effect of quantization on intensity resolution.
- Perform arithmetic operations on grayscale images.
- Apply bitwise set operations to images.

## Practical Tasks

### Task 1: Sampling and Quantization

Different sampling factors and quantization levels were applied to observe their effects on image quality.

- **Sampling:** Demonstrates how reducing spatial resolution affects image details.
- **Quantization:** Demonstrates how reducing the number of intensity levels affects grayscale representation.

### Task 2: Image Arithmetic and Set Operations

The following operations were implemented:

- Subtraction of two grayscale images.
- Addition of a constant value (175) to an image.
- Set Difference (`A & ~B`)
- Symmetric Difference (`A ^ B`)
- Intersection (`A & B`)

## Tools and Libraries

- Python
- NumPy
- Matplotlib
- Pillow (PIL)
- scikit-image
- Jupyter Notebook

## File

`Lab2_Digital_Image_Fundamentals_2.ipynb`

## Conclusion

This lab demonstrates how sampling and quantization influence digital image quality and how arithmetic and bitwise operations can be applied to grayscale images using Python.
