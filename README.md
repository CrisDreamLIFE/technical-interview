# technical-interview

Pasos para correr sistemas:

    1 ) Frontend:
        * sudo docker build -t event-project-frontend:lastest .
        * sudo docker run -d -p 4200:80 event-project-frontend:lastest

	2) Backend: 
        * sudo docker build -t event-project-backend:lastest .
        * sudo docker run -d -p 8000:80 event-project-backend:lastest

    3 ) Abrir navegador de preferencia y entrar a la url: localhost:4200