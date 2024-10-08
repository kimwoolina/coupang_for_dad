# 아빠도 Coupang (Coupang for Dad)

## Introduction
The post-coronavirus era has been all about going virtual. How can we bridge the information gap between generations? We decided to go back to the days of old!

We created a voice-activated ordering service designed for older generations who have difficulty placing orders via touchscreen.

Want food delivered to your doorstep at dawn tomorrow? No app needed. Just give Coupang for Dad "A call"! Older consumers have a lot of purchasing power but are less savvy so Coupang can't reach them without the help others. With Coupang for Dad, we can reach them directly! 


## Duration
24.08.24 - 24.08.25 
    
## Project Arcitecture
<img width="667" alt="스크린샷 2024-08-25 오전 7 49 27" src="https://github.com/user-attachments/assets/968a92b7-88ef-47c9-ae3f-e6d5ac52b2c8">

## Workflow
<img width="1073" alt="스크린샷 2024-08-24 오후 9 43 21" src="https://github.com/user-attachments/assets/9ec88f04-93ca-4d0d-a8af-6ec676b15af4">

## TechStack
- **:art: Front-End**

  - Language
    - <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

  - Framework / Library
    - <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
    - <img src="https://img.shields.io/badge/ChatGPT--4o_API-000000?style=for-the-badge&logo=openai&logoColor=white">

  - Deployment
    - <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">


- :computer: __Back-End__

  - Language
    - <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
    - <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">

  - Framework / Library
    - <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">

  - Database
    - <img src="https://img.shields.io/badge/Firebase_Realtime_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black">

  - API
    - <img src="https://img.shields.io/badge/pixabayapi-0288D1?style=for-the-badge&logo=photoshop&logoColor=white" alt="pixabayapi badge"> 
    - <img src="https://img.shields.io/badge/Blend.ai_API-000000?style=for-the-badge&logo=blend&logoColor=white" alt="Blend.ai API badge"> 
    - <img src="https://img.shields.io/badge/Rapid_Food_Recipe_API-FF5722?style=for-the-badge&logo=food&logoColor=white" alt="Rapid Food Recipe API badge">
    - <img src="https://img.shields.io/badge/Naver_Papago_Translate_API-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="Naver Papago Translate API badge">

  - Tools
    - <img src="https://img.shields.io/badge/ngrok-1F1E1F?style=for-the-badge&logo=ngrok&logoColor=white">
    - <img src="https://img.shields.io/badge/ChatGPT--4o-000000?style=for-the-badge&logo=openai&logoColor=white">

## Running
Run the flask server in the `llm` directory by running `python -m flask --app server run`.
Next expose the local flask server using ngrok using `ngrok http http://127.0.0.1:5000 --domain=diverse-mint-burro.ngrok-free.app`. This will allow the local llm services to be accessible by the bland.ai pathway.

## How to Test
Visit the [reset link](https://us-central1-hackseoul20241.cloudfunctions.net/api/reset) and reset the app.

Visit our ["TV app"](https://hack06.vercel.app/) which is a mock of what a smart TV app could be when interacting with our service.

Make a phone call to the US phone number +14156501485 and talk to the Coupang agent, with a specialty in Korean food, to order whatever you would like.

## 🏆 Award
Grand Winner at the 2024 Coupang AngelHack Seoul
