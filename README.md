# Project Name

Book service

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.
### Prerequisites
Obtain detailed project requirements: [test.pdf](https://github.com/firozfau/book_service/blob/main/test.pdf)

### Prerequisites

Make sure you have Docker installed on your machine.
You can download it from [Docker's official website](https://www.docker.com/get-started).

### Dependency:
```bash
    1. python:3.9
    2. postgresql:16
    3. fastapi
```


### Clone the Repository

```bash
git clone https://github.com/your-username/your-project.git
```
### To navigate to your project directory use terminal:
```bash
cd path/to/your/project
```
### [in general way:] To run the Docker project, follow the steps below:
```bash
 'step-1:' docker compose up --build
 'step-2:' open browser check :http://127.0.0.1:8000/docs
  [If this URL is not working then ]  
 'step-3': press: control+c
 'step-4' : sudo docker compose up --build
```
### [Need sudo permission:]  To run the Docker project, follow the steps below:
```bash
 'step-1:' docker compose up --build
 'step-2:' docker pull python:3.9  
 'step-3:' docker scout quickview python:3.9
 'step-4:' sudo docker compose up --build
 'step-5:' open browser check :http://127.0.0.1:8000/docs
  [If this URL is not working then ]  
 'step-6': press: control+c
 'step-7' : sudo docker compose up --build
```

### Fast-API access URL:
```bash
 'URL:' http://127.0.0.1:8000/docs
```
### API-authorize Token:
```bash
 'Token:' Frzf7KnaKMac$EloGenoFire9CUP2mXpilo
```


### Note:
```bash
 Gender should be use text: 'Male', 'Female', 'Others', 'Unknown'
```

### project run without-docker:
```bash
 need install dependency tools and lib which you can find to the 'requirements.txt' 
```
```bash
 'step-1': execute postgresql schema in your localhost. file location is 'postgres_data/book_service'
 'step-2': open terminal and make command: 
          'cmd': python -m venv env
          'cmd': source ./env/bin/activate
          'cmd': pip install -r requirements.txt
          
 'step-3': Run proejct
          'cmd': uvicorn main:app --reload        
```
