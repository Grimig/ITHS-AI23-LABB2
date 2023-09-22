## ITHS-AI23-LABB2

- test- and datapoints are found in .\resources


## Implementing synthetic data and ML to further humankinds ability to differentiate between a Pikachu or an obese Pichu.

### Objective
The purpose of this lab is to utilize the tools you have learned in Python to implement a simplified machine learning algorithm.

### Overview
In this lab, you have been given simulated data on the lengths and widths of Pichus and Pikachus. Your task is to create an algorithm that can classify a new data point as either Pichu or Pikachu based on the given data.

---

### Basic Task
Follow this flowchart to build the basic algorithm.
- Test Data Coordinates: `(25,32), (24.2,31.5), (22,34), (20.5,34)`

#### Expected Results
- Sample with (width, height): `(25, 32)` classified as Pikachu
- Sample with (width, height): `(24.2, 31.5)` classified as Pikachu
- Sample with (width, height): `(22, 34)` classified as Pikachu
- Sample with (width, height): `(20.5, 34)` classified as Pichu

---

### Additional Tasks
Complete these tasks once you have correctly classified the test data.
1. Allow the user to input a test point and have the algorithm determine its class.
    - Include error handling for negative numbers and non-numeric inputs. Make sure to provide user-friendly error messages.
2. The nearest-point approach we have used may misclassify when the points of each class overlap.
    - Now choose the ten nearest points to your test point.
    - The class of the test point is determined by majority voting among the nearest points.
