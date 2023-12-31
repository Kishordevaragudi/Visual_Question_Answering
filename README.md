# Visual_Question_Answering

Visual Question Answering (VQA) system using state-of-the-art deep learning models. I am Exploring how to leverage the power of the Hugging Face's ViLT (Vision-and-Language Transformer) model to answer questions about images.

I am introducing the ViLT model, which combines text embeddings with a Vision Transformer (ViT) architecture, enabling us to perform joint vision-and-language tasks. We'll dive into the research behind ViLT and understand how it achieves efficient and expressive pre-training for VQA.

how to implement the ViLT model in two different ways: as an API using FastAPI and as an interactive app using Streamlit. FastAPI allows us to build a robust API that can receive image and text inputs and return the predicted answer. Streamlit, on the other hand, provides a user-friendly interface with an image uploader and text input field, giving users an interactive experience to ask questions about images.

Deep understanding of how to utilize the ViLT model for visual question answering and how to create both an API and an interactive app to leverage this powerful model.

## How run the Project
1. Clone the github repo using a command
#### git clone https://github.com/Kishordevaragudi/Visual_Question_Answering.git
2. create a virtual environment in your local system using python
#### conda create -p venv python==3.9 -y
3. Install the packages by runing the requirement.txt
#### pip install -r requirements.txt
7. run the file using a command
#### streamlit run app.py

## Output result 

![Screenshot 2023-08-31 100913](https://github.com/Kishordevaragudi/Visual_Question_Answering/assets/105155723/189e5e14-ba83-447e-858c-c5a52c7dd8e0)
![Screenshot 2023-08-31 101028](https://github.com/Kishordevaragudi/Visual_Question_Answering/assets/105155723/c939c14e-fca0-482c-9116-2b52d04742af)
![Screenshot 2023-08-31 101228](https://github.com/Kishordevaragudi/Visual_Question_Answering/assets/105155723/d338d9e6-a7b7-4488-ae59-ecfe04bea1b9)

