# AI-Chatbot

---

## Overview

This is a Fullstack project that provides a chatbot that can assist users with chat and coding. The project uses React and Redux on the front end, with the React Router library for routing. The back end is built with Express, Node.js, and the OpenAI API. The chat feature is built using ChatEngine.io, and authentication is handled with login/sign up forms.

---

## Set Up and Installation

To get started with this project, you'll need to have Node.js, npm, and npx installed on your machine. Once you have those installed, you can follow these steps to run the project locally:


1. Clone the repo

2. Install latest `node` and `npx`

3. Run `npm install`

### ChatEngine Set Up

* Create a free account with chatengine.io: Create a new project (Free),

* Note the project API Keys: Project ID & Private Key

* In the newly created project (ChatEngine), create a new user for the chatbot [eg, Ai_Bot-James]

* Edit the .env files: Frontend: Rename `.env.local_example` to `.env.local` 
Backend: Rename the `.env_example` to `.env`

* In `.env.local`: Insert the port number 1337 and also the chatEngine Projecvt ID

* In the `.env` file (server): insert the Private Key, Project ID, and OpenAI API key: Also Add the bot username and password that you created here [e.g BOT_USER_NAME=Ai-bot-George BOT_USER_SECRET=1234]

---

## Start Up

* Open two terminals:
* To run the Frontend: in the AiChatApp folder run `npm run dev`
* To run the server: change directory to the server and run `npm run dev`
* After App start up, create a new user and login

### On the Chat App

1. Create a new chat rooms with the name “AiChat_” and “AiCode_”
2. In each chat go to the member section and add the newly created bot User to the chat [BOT_USER_NAME=Ai-bot-George]
You can start a new conversation with the bot in each chat room.
--- 

### Video Explainer

![ezgif-1-8622ec70ca](https://user-images.githubusercontent.com/20837551/227766514-a9bb6f19-0f96-4b0d-8414-86998e178c47.gif)


---

## Technology Used

Frontend: Chat Engine, React, Javascript, Redux, React Router, Redux Toolkit Query (RTK Query)
Backend: NodeJS, ExpressJS, OpenAi API

---

## Features

1. Login/Signup Authentication and Authorization: The project includes a simple authentication system with login and sign up forms. Users can create accounts and log in to access the chatbot's features. - User management - [Name & Profile Picture]

2. Code assistance from chatbot: The chatbot can also assist users with coding by suggesting code snippets and answering programming-related questions. This feature is built using the OpenAI API, which provides natural language processing and machine learning capabilities.

3. General AI chat assistance: The chatbot can assist users with conversation by responding to their messages and suggesting responses. The chat feature is built using ChatEngine.io, which provides real-time messaging functionality.

4. Text autocompletion feature: users can wait for a few seconds while typing a prompt and would get likely suggestions
Usage.

---

## Contact

Please feel free to contact me via my email badmus.oriyomi1@gmail.com or through my LinkedIn profile 
linkedin.com/in/oriyomibadmus .

---
