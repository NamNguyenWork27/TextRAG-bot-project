# TextRAG-bot-project
## Introduction

Have you ever wished for a superhero sidekick who could swiftly read and comprehend documents for you? Meet **TextRAGBot** - a tool designed to utilize RAG for document reading and interaction via a user-friendly chatbot interface built with Chainlit.

🚀 This project is engineered to operate seamlessly on both Google Colab and locally, ensuring accessibility for everyone!

**Note**: This project is part of my submission for the first module of an AI Course.

![The screen(screen_shot/UI.jpg)]
## Prepare
1. **Clone the repository** 
```sh 
    git clonde https://github.com/NamNguyenWork27/TextRAG-bot-project.git
    cd TextRAG-bot-project
``` 
2. **About Google Colab**
- [Click here to open the Colab notebook](https://colab.research.google.com/) and log into your account.
- Chang the run time to your notebook from to GPU

3. **Install the required dependencies:**
All essential packages are listed in the 'requirements.txt' file. To install them:
- On Google Colab: Follow the instructions provided in the notebook files (.ipynb). Ensure you switch the runtime of your notebook from CPU to GPU.
- Locally:
```sh
    pip install -r requirements.txt
```
## Usage
Running TextRAGBot is easier than making a cup of coffee. ☕
1. **On Google Colab**
 I prepared 2 files .ipnynb [RAQ_project_without_UI.ipynb](https://colab.research.google.com/drive/1AOt-BcxmXcjQAMW3uKL96xmO9dAGBdNo) and [RAG_project_with_ChatUI.ipynb](https://colab.research.google.com/drive/1TODUmE7rtedFZEtrMtBQ0hP4NUBFaFhO)
 2. **Run locally:**
 - Start the application:
```sh
    chainlit run chainlit_app.py
```
- Open your web browser and go to **http://localhost:8000**.
- Upload a PDF or text file and start asking questions. Sit back and enjoy as TextRAGBot works its magic! ✨
  
  **Note:** Make sure that your device has GPU enough to run this project locally.

## Conclusion
**Thanks very much** for checking out my textRAGbot project! I hope that you had a great experience. If you have any questions or feedback, feel free to reach out.
