# Lifestyle-Recommendation-System
The primary goal of our project is to revolutionize personal health monitoring through the development of a comprehensive mobile application. By seamlessly integrating vital sign and activity inputs, leveraging machine learning algorithms such as Logistic Regression and Random Forest, and utilizing Gradio for an intuitive user interface, our system aims to empower users with personalized insights into their overall well-being. The ultimate objective is to assist users in making informed decisions about their lifestyle and health habits, fostering a positive impact on their health journey.

![Healthy-1](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/44b05e86-20e4-487c-9f12-2cc959f99762)

## Video

https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/0f3cd2d9-cd7b-4645-ab75-f99ac787db4a

## Table of contents

Objectives

oneAPI

oneAPI Optimization

Proposed System

Key Components

Workflow

Output

Video Explanation

Acknowledgement

## Introduction

In today's fast-paced world, health awareness and proactive well-being management have become increasingly important. Our project introduces a novel approach to health monitoring, utilizing a mobile application that collects and analyzes various vital signs and activities. This transformative tool goes beyond mere data collection, providing users with tailored suggestions and valuable insights into their overall body condition. The integration of machine learning algorithms elevates the system's capabilities, enabling it to offer personalized recommendations for improved lifestyle and health choices.

## Objectives

Gather a diverse range of health-related inputs, including vital signs (heart rate, blood pressure, fall detection, calories) and lifestyle details (gender, age, occupation, sleep duration, sleep quality, physical activity level, stress levels, BMI category, daily steps, presence or absence of sleep disorders).Implement advanced machine learning algorithms, such as Logistic Regression and Random Forest, to analyze the collected data and derive meaningful insights into the user's well-being.Transform user health journeys by providing personalized, actionable suggestions based on the analyzed data, aiming to positively impact lifestyle and health habits.

 ## oneAPI

Intel’s oneAPI is an open, accessible and standards-based programming system that enables developer engagement and innovation across multiple hardware architectures, including CPUs, GPUs, FPGAs, AI accelerators, and more. These tools all have very different properties and are thus used for various operations–which oneAPI attempts to simplify by unifying them under one model. The oneAPI AI Analytics Toolkit [1] is implemented using the oneAPI Data Analytics Library (oneDAL), a powerful machine learning library that helps speed up big data analysis. oneDAL is an extension of Intel® Data Analytics Acceleration Library (DAAL) and is a part of oneAPI. 

![861_logo-oneapi-rwd](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/07c36d5d-60fa-4c5a-9856-2afe86fd4fca)


## oneAPI Optimization

Optimizing our system using oneAPI involves enhancing performance through parallel processing and hardware acceleration. By leveraging oneAPI, we ensure that our health monitoring application is not only efficient but also adaptable to different computing environments.

![Screenshot 2024-01-31 191147](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/810c54ba-a485-4f33-a998-39d74fe94e99)


## Proposed Systems

An intuitive platform that serves as the user interface, facilitating the input of health data and presenting personalized insights. Responsible for gathering a comprehensive set of health-related inputs, ensuring a holistic understanding of the user's well-being. Utilizes Logistic Regression and Random Forest algorithms to analyze the collected data, generating valuable insights and recommendations. Incorporates Gradio to create a user-friendly interface within the mobile application, making health monitoring accessible and engaging.

## Flowchart

![Screenshot 2024-01-31 155354](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/eaf72459-402e-45de-8816-ba41e3ce8145)

## Key Components

### Data Collection Module:

A labled dataset containing age,stress level,activity_level and blood_pressure is used for getting the life style suggetion.Gathers a wide range of health data, ensuring a holistic and detailed analysis.

### Machine Learning Module:

Implements advanced algorithms to derive insights from the collected data, providing valuable information for user well-being.

### Gradio User Interface:

Enhances user experience by providing an intuitive platform for inputting health data and receiving personalized suggestions.


## Workflow:

### Data Input:

Users input their health data through the user-friendly Gradio interface on the mobile application.

### Training Phase:

The SVM model is trained using the labeled dataset, learning the patterns and characteristics of genuine and fake reviews.
Feature extraction methods are applied to represent the reviews in a format suitable for SVM training.

### Integration with Gradio:

Gradio interface is implemented to take user input in the form of a product review.
The input is processed and fed into the trained SVM model for classification.
The model's output, indicating whether the review is genuine or fake, is displayed to the user.

### User Interaction:

Users interact with the Gradio interface by inputting product reviews of their choice.
The interface provides real-time feedback, instantly displaying the model's classification results.


## Output:

### Gradio Interface

Enhances user experience by providing an intuitive platform for inputting health data and receiving personalized suggestions.
![Screenshot 2024-01-31 154248](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/7cfd30a2-4286-4f78-9e28-67f215174056)
![Screenshot 2024-01-31 154353](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/90d90d34-d677-4ecd-a19d-915aa64050ed)


### Health Suggestion:
Users receive a personalized health report within the mobile application. The output includes visualizations, insights, and tailored suggestions based on their unique health profile.

### Video Explanation

For a comprehensive understanding of the system, we provide a detailed video explanation. This video walks users through the features, functionalities, and benefits of our health monitoring application, showcasing its transformative capabilities.

https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/dd83e3ff-f7eb-43b8-a623-89f8bda3ce3d

## Acknowledgement

The project uses the Gradio library to create an interactive interface. Special thanks to the contributors and maintainers of the open-source libraries used in this project.
