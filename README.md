# Welcome to miniChatGPT!

    A light-weight example of chatGPT using neural nets and an intents file

   https://user-images.githubusercontent.com/60236247/235518311-ae1c71fc-baa5-40ec-ab00-6edfdc4fba2d.mov

## How to set up and run miniChatGPT

### 1. Clone Project

   > git clone [https://github.com/eruigu/miniChatGPT.git]

### 2. Setup Environment

   > install python3: check the version "python3 --version"

   > MacOS: pip3 install virtualenv

   > Linux (Debian): sudo apt install pythonx.x-venv (replace x with your version of python)

### 3. Create virtual environment

   > python3 -m venv venv

### 4. Activate virtual environment and update pip

   > source venv/bin/activate && pip install -U pip setuptools

### 5. Install wheel library

   > MacOS: pip3 install wheel

   > Linux (Debian): pip install wheel

### 6. Install dependencies

   > MacOS: pip3 install -r requirements.txt

   > Linux (Debian): pip install -r requirements.txt

### 7. Train chatbot model

   > cd into src/model_training/ and run python3 training.py
   >> This will create two .pkl (pickle) files: classes and words in src/backend/

### 8. Run the chatbot

   > python3 server.py: which is located in src/backend/
   >> this will create a .h5 model file in the current directory

### 9. The server is running on 127.0.0.1:8001

   > You can change the server config in server.py
