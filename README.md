DialogFlow interface <br>
![chatbot](https://github.com/mahdihammi/Chatbot-food-delivery/assets/89527502/ce7fe6b1-6587-4d22-a28b-2ca855d777b6)

Chatbot <br>
![dialog1](https://github.com/mahdihammi/Chatbot-food-delivery/assets/89527502/610b91a9-cc6d-4790-bd23-ccae2ee5a3be)
![dialog2](https://github.com/mahdihammi/Chatbot-food-delivery/assets/89527502/88616d89-b118-4c6e-a2a1-87a46d7fabe2)

Mysql database <br>
![mysql](https://github.com/mahdihammi/Chatbot-food-delivery/assets/89527502/ca2419e0-4420-4a3c-b9dd-b125895dda0b)



<br>
Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
