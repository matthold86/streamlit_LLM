# Streamlit Text Translation Application

## What is Streamlit?
Streamlit is an open-source Python library designed to simplify the process of creating and deploying interactive web applications for data science and machine learning projects. By allowing developers to turn data scripts into shareable web apps using only Python, Streamlit streamlines web development, eliminating the need for complex web development skills. With minimal setup and straightforward syntax, Streamlit is ideal for building and prototyping applications quickly, prioritizing speed and ease of use for the developer.

## Project Summary
This project is a quick introduction to deploying applications using Streamlit and integrating web applications with a Hugging Face LLM. This application uses the `Helsinki-NLP/opus-mt-en-es` English-to-Spanish translation model from Hugging Face. It takes input text in English, translates the text to Spanish, then outputs the results below input textbox. A link to the public IP address of the EC2 instance and port where the application is deployed is provided below. If the EC2 instance has been terminated due to inactivity, screenshots of the deployed application are provided in the subsequent sections.

[Streamlit English-Spanish Translation Application](http://34.201.91.74:8501/)



## User Interaction

1. Load the web application.
![image](https://github.com/matthold86/streamlit_LLM/assets/114833075/d13670de-850b-4041-b0b9-486fdefc0ae0)

2. Enter input text and press `Translate`.
![image](https://github.com/matthold86/streamlit_LLM/assets/114833075/83647f6f-8e65-4101-b947-246932084af7)

3. The results will be pasted below the input text.
![image](https://github.com/matthold86/streamlit_LLM/assets/114833075/8f59a6a9-a7b1-4407-b4b3-6f35097b92e4)

## Deployment

This application is deployed on an Amazon EC2 (Elastic Compute Cloud) instance, which provides scalable computing capacity in the Amazon Web Services (AWS) cloud. Deploying a Streamlit application on EC2 involves setting up a suitable environment by selecting an instance type that matches the application's CPU, memory, and storage requirements. This repository was cloned onto the EC2 instance enabling configuration to be specifically talilored to the requirements.txt file in this repository. Security groups and firewall settings are adjusted to allow web traffic on port 8501, which is the default for Streamlit apps. This setup utilizes the reliability and flexibility of AWS infrastructure and ensures that the application can efficiently handle varying loads with the ability to scale resources dynamically.

![image](https://github.com/matthold86/streamlit_LLM/assets/114833075/bb933b6f-6b7c-42ff-8d06-79b38d2d5fb9)





