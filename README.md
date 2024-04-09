# Fourier | Music Streaming App


## Prerequisites:
Have redis installed and running:
1. `$ sudo apt update`
2. `$ sudo apt-get install redis-server`
3. `$ sudo service redis-server start`

> Refer to [docs](https://redis.io/docs/latest/operate/oss_and_stack/install/) if you have any problem running redis.

## Start App directly: 
1. `./run.sh`
---
OR RUN CLIENT AND SERVER INDIVIDUALLY 👇 

## For Server:
Run these commands in the following order:
1. `$ cd server`
2. `$ python3 -m venv venv`
3. `$ source venv/bin/activate`
4. `$ pip install -r requirements.txt`
5. `$ python app.py`

## For Client:
Run these commands in the following order:
1. `$ cd client`
2. `$ npm install`
3. `$ npm run dev`

## Database Schema:
[https://dbdiagram.io/d/Fourier](https://dbdiagram.io/d/Fourier-65378240ffbf5169f05399fe)   

## Video Demo
[Presentation of the Project (Backend)](https://youtu.be/ZIKCX-XWZD0)

[Presentation of the Project (Frontend)](#)

## Swagger API Spec:
[https://app.swaggerhub.com/fourier](https://app.swaggerhub.com/apis/hamees-sayed/fourier-music_streaming_app_open_api_3_0/1.0.0)
