# Blood Group Detection Using Deep Learning
![blood images](https://media.cnn.com/api/v1/images/stellar/prod/200714121605-hp-only-20200714-blood-groups-card.png?q=w_3201,h_1800,x_0,y_0,c_fill)
## Problem Statement
Determining a person's blood group is essential for medical diagnostics and emergency care. Current methods often rely on manual laboratory procedures that are time-consuming and require specialized expertise. This project leverages supervised machine learning to automate blood group detection, using deep learning models trained to classify blood types based on image data, thereby enhancing accessibility and efficiency.

## Manual Process of Blood Group Detection
The traditional process of blood group detection involves serological testing. Blood samples are mixed with specific anti-A, anti-B, and anti-Rh serums to observe agglutination and identify antigens. This process determines the blood type (A, B, AB, or O) and the Rh factor (positive or negative). In some complex cases, DNA analysis may be required to confirm the presence of certain antigens at a genetic level. Although effective, these manual processes can be slow and demand experienced personnel and laboratory resources.

## Utility of the Project
This project aims to simplify and speed up the blood group detection process. By automating the classification using deep learning models, it offers a non-invasive, quick, and reliable alternative. Such advancements could be invaluable in urgent medical scenarios and in areas lacking laboratory infrastructure, reducing the reliance on manual testing and enabling faster decision-making in healthcare settings.

## Data Sources and Approach
We employ two main datasets in this project:
- **Blood Image Dataset**: Comprising labeled microscopic images of blood samples, used for training a deep learning model that identifies blood groups based on visual characteristics.
- **Fingerprint Image Dataset**: An innovative dataset linking fingerprint images with blood group classifications, enabling the development of a model that detects blood types from biometric patterns.

## Project Steps
- [x] **Data Preprocessing**: Cleaning and preparing the datasets to ensure high-quality input for training.
- [x] **Model 1 - Blood Image Classification**: Building a deep learning model to classify blood groups using microscopic blood images.
- [x] **Model 2 - Fingerprint Image Classification**: Creating a second deep learning model focused on fingerprint images for blood group classification.
- [x] **Comparison of Models**: Evaluating both models' performance to determine the most accurate and reliable approach.
- [x] **Deployment**: Integrating the top-performing model into a web-based application for user accessibility.
- [x] **Testing**: Rigorously testing the chosen model to ensure robust performance under various conditions.

