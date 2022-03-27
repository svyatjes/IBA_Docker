# Матийко Святослав

# Task 1
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/1.png?raw=true)

# Task 2
- rm containers  
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/2_1.png?raw=true)

- rm images  
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/2_2.png?raw=true)
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/2_3.png?raw=true)

# Task 3
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/3.png?raw=true)

# Task 4
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/4.png?raw=true)


# Task 5
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/5.png?raw=true)

# Task 6
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/6.png?raw=true)

P.S: in the background you can see that the site has risen

# Task 7
- Dockerfile
```docker
FROM python:3.8
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
```
- build image  
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/7_1.png?raw=true)

- run container on 5000 port  
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/7_2.png?raw=true)

- site is work  
![alt text](https://github.com/svyatjes/IBA_Docker/tree/master/photos/7_3.png?raw=true)

P.S Also you can see Dockerfile in t7 folder 