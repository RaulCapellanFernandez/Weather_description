# ⛅️ Weather Description Dataset and Webcam Image Description

Welcome to the Weather Description Dataset project! Our mission is to craft a comprehensive dataset for weather description using webcam images of landscapes. Here's how we'll do it:

## 🌦️ Creation of a Weather Description Dataset

### 1. Data Collection 📸

We'll kickstart our project by gathering webcam images of landscapes from the desired area. These images will be our main source of data.

#### 1.1 Data Retrieval 🌍✔️

Next, we'll dive into the ERA5 reanalysis data to fetch detailed information on selected weather variables (cloud variables in the beginning).

#### 1.2 Description Generation ✍️ 🛠️✔️

Using Language Models (LLMs), we'll create prompts to describe various types of clouds based on the values of the chosen weather variables. Here are the techniques we'll explore:

##### 1.2.1 LLAMA Models 🦙

We'll utilize LLAMA models for inference to generate descriptions, as the main open source LLMs at the moment.

##### 1.2.2 Chat GPT Models 💬 🛠️✔️

The API provided by OpenAI will be an option to use Chat GPT models for inference and description generation.

##### 1.2.3 RAG and Transfer Learning Strategies 🔄

We'll explore advanced techniques such as RAG and transfer learning to enhance the quality of descriptions for weather variables.

##### 1.3. Data Storage 💾✔️

All the valuable information generated will be stored in a parquet file or a database format for easy access and usage in the training process.

## 📷 Description of Webcam Images

Now, let's dive into the world of webcam image description

### 2. Dataset Utilization 📚

With the weather dataset previously created with the images descriptions will be enough for trainning the image description algorithm.

### 2.1 Training Process 🚀✔️

It´s planned to use transformers algorithm to this process but this is something that could change during the development depending of the results or the actual state of art during the project.
Two options are planned to the training part:

#### 2.1.1 Generating a New Model 🆕✔️

We'll engineer a cutting-edge model designed to describe webcam images, powered by our curated dataset.

#### 2.1.2 Transfer Learning 🔄

We'll adapt a pre-trained model using transfer learning techniques to integrate it with the weather characteristics of our dataset.


## 🌍 Final Applications

This are possible applications for this product:

- Could replace expensive cloud sensors with our model for more cost-effective and accurate results 🌤️
- Useful in solar plants for detecting sunlight levels and optimizing production ☀️
- Relevant for various smart city activities, enhancing efficiency and sustainability 🏙️
